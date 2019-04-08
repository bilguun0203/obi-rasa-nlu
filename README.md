# OBI Rasa NLU

[`obi-assistant`](https://github.com/bilguun0203/obi-assistant)-д шаардлагатай бичвэрээс зорилго тодорхойлох модель үүсгэхэд шаардлагатай файлууд.

## Ашиглалт

1. Virtual env үүсгэх (заавал биш)

   ```
   python -m venv .venv
   ```

2. Шаардлагатай сангуудыг суулгах

   ```
   pip install -r requirements
   ```

3. Сургах

   ```
   make train-nlu
   ```

4. Шалгах HTTP сервер ажиллуулах

   ```
   make run-nlu
   ```

5. HTTP сервер лүү хүсэлт илгээх
   ```
   curl -X POST localhost:5000/parse -d '{"query":"сайн уу", "project": "current"}'
   ```
