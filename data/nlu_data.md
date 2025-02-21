## intent:greeting

- сайн уу
- сайн байна уу
- өглөөний мэнд
- өдрийн мэнд
- оройн мэнд
- юу байна
- амар байна уу

## intent:get_time

- хэдэн цаг болж байна
- цаг хэд болж байна
- хэд болж байна
- хэдэн цаг болж байна вэ
- цаг хэд болж байна вэ
- хэд болж байна вэ
- цаг хэлээд өгөөч

## intent:get_date

- өнөөдөр хэдэн бэ
- өнөөдөр хэдэн сарын хэдэн бэ
- хэдний өдөр вэ
- өнөөдөр хэдний өдөр вэ
- хэдэн сар вэ
- хэдэн бэ
- хэдэн сарын хэдэн бэ

## intent:get_day

- ямар гараг вэ
- өнөөдөр ямар гараг вэ
- хэд дэх өдөр вэ
- өнөөдөр хэд дэх өдөр вэ
- долоо хоногийн хэд дэх өдөр вэ

## intent:get_weather

- [маргааш](day) хэдэн градус байх вэ
- [Улаанбаатарт](city) [өнөөдөр](day) хэдэн градус байх вэ
- [Дарханд](city) [нөгөөдөр](day) цаг агаар ямар байх вэ
- [Цэцэрлэгт](city) цаг агаар [маргааш](day) ямар байх вэ
- [маргааш](day) [Өндөрхаанд](city) цаг агаар ямар байх вэ
- [өнөөдөр](day) [Мөрөнд](city) хэдэн градус байх вэ
- гадаа хэдэн градус байна
- гадаа хэдэн градус байна вэ
- гадаа ямар байна
- гадаа ямар байна вэ
- цаг агаар ямар байна
- цаг агаар ямар байна вэ
- [өнөөдөр](day) цаг агаар ямар байна
- [нөгөөдөр](day) цаг агаар ямар байх вэ
- [Эрдэнэтэд](city) хэдэн градус байна
- [Алтайд](city) цаг агаар ямар байна
- [Улаангомд](city) гадаа ямар байна
- [Зуунмодод](city) хэдэн градус байна вэ
- [Чойбалсанд](city) цаг агаар ямар байна вэ
- [Ховдод](city) гадаа ямар байна вэ

## intent:get_currency

- [Евро](currency) хэдэн төгрөг байна вэ
- [Доллар](currency) хэд байна вэ
- [Иен](currency) хэдтэй байна вэ
- [Египетийн фунт](currency) ямар үнэтэй байна вэ
- [Евро](currency) хэдэн төгрөг байна
- [Шинэ зеланд доллар](currency) хэд байна
- [Өмнөд Африкийн ранд](currency) хэдтэй байна
- [Фунт](currency) ямар үнэтэй байна
- [Норвегийн крон](currency) хэд вэ
- [Рубль](currency) хэдэн төгрөг вэ
- [Индонез рупи](currency) хэдэн төгрөгтэй тэнцэж байна
- [Сингапур доллар](currency) хэдэн төгрөгтэй тэнцэж байна вэ

## intent:order

- [пицца](product) захиалъя
- [пицца](product) идье
- [пицца](product) захиалга
- [пицца](product) аваад ир
- [пицца](product) дууд
- [пицца](product) хүргэлт
- [пицца](product) хүргээд ир

## intent:order_size

- [Жижиг](size) хэмжээтэй
- [Дунд](size) хэмжээтэй
- [Том](size) хэмжээтэй
- [Жижиг](size) хэмжээтэйг
- [Дунд](size) хэмжээтэйг
- [Том](size) хэмжээтэйг
- [Жижиг](size) хэмжээтэй пицца
- [Дунд](size) хэмжээтэй пицца
- [Том](size) хэмжээтэй пицца

## intent:order_quantity

- [нэг](quantity) ширхэг
- [хоёр](quantity) ширхэг
- [гурван](quantity) ширхэг
- [дөрвөн](quantity) ширхэг
- [таван](quantity) ширхэг
- [зургаан](quantity) ширхгийг
- [долоон](quantity) ширхгийг
- [найман](quantity) ширхэг пицца
- [есөн](quantity) ширхгийг
- [арван](quantity) ширхгийг

## intent:cancel

- болилоо
- зогс
- цуцал
- цуцаллаа
- дуусга
- боль

## lookup:time

- маргааш
- өнөөдөр
- нөгөөдөр

## lookup:city

- Цэцэрлэгт
- Өлгийд
- Баянхонгорт
- Булганд
- Алтайд
- Чойрт
- Дарханд
- Сайншандад
- Чойбалсанд
- Мандалговьд
- Улиастайд
- Эрдэнэтэд
- Арвайхээрт
- Даланзадгадад
- Баруун-уртад
- Сүхбаатарт
- Зуунмодод
- Улаангомд
- Ховдод
- Мөрөнд
- Өндөрхаанд
- Улаанбаатарт

## lookup:currency

- Доллар
- Евро
- Иен
- Франк
- Крон
- Фунт
- Лев
- Унгарын форинт
- Рупи
- Хонконг доллар
- Египетийн фунт
- Рубль
- Тэнгэ
- Юань
- Вон
- Канад доллар
- Австрали доллар
- Чех крон
- Тайвань доллар
- Тайланд бат
- Индонез рупи
- Ринггит
- Сингапур доллар
- Дирхам
- Кувейт динар
- Шинэ Зеланд доллар
- Данийн крон
- Польшийн злот
- Украйны гривн
- Норвегийн крон
- Непалын рупи
- Өмнөд Африкийн ранд
- Туркийн лира
- Вьетнам дон
- Төгрөг

## lookup:size

- жижиг
- дунд
- том

## lookup:quantity

- нэг
- хоёр
- гурван
- дөрвөн
- таван
- зургаан
- долоон
- найман
- есөн
- арван

<!-- ## regex:quantity

- [0-9]{1,} -->

## lookup:product

- пицца
