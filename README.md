# application

Не знаю как все это дело разделить на разделы. 
Их можно группировать, но одни и те же данные могут быть в разных группых. 
Думаю легче записывать все подряд без групп, но указывать зависимости
А для интерфейса, мне кажется, нет смысла группировки данных. 
Пользователь вообще ничего не должен видеть

Самое главное:
### Фамилия
### Имя
### Отчество

### Пол
(можно как то автоматом определять пол?)

### Дата рождения
(возраст, соответствие биологического возраста с календарным)

Нужно, чтобы у каждого показателя была привязка ко времени
### Рост
### Вес

Здесь автоматически должно высчитываться имт

### Индекс массы тела Кеттле (ИМТ)

ИМТ = вес (кг) / рост в квадрате (м2)

* менее 18,5 – недостаточная масса тела
* 18,5–24,9 – нормальная
* 25,0–29,9 – избыточная
* 30,0–39,9 – ожирение
* 40,0 и выше – выраженное ожирение


### Аллергологический анамнез и непереносимость препаратов.

Отметить наличие непереносимости пищевых продуктов, медикаментов, вакцин и сывороток с указанием характера болезненных явлений при их употреблении. Наличие разнообразных аллергических реакций (вазомоторный ринит, крапивница, отек Квинке и др.) с указанием их сезонности и/или связи с другими внешними факторами.

У вас есть аллергия на медикаменты, пищевые продукты?

Тут отметить да, либо нет.
Далее он вручную вбивает на что у него аллергия. 



### пульс
например: 65 ударов в минуту


### давление
Систолическое и диастолическое давление. 
систолическое/диастолическое мм рт.ст.
например: 120/80 мм рт.ст.
* оптимальное АД < 120/80 мм рт. ст.
* нормальное АД 120–129/80–84 мм рт. ст. 
* высокое нормальное АД 130–139/85–89 мм рт. ст. 
* АГ 1-й степени (мягкая АГ) – 140–159/90–99 мм рт. ст. 
* АГ 2-й степени – 160–179/100–109 мм рт. ст. 
* АГ 3-й степени – АД выше 180/110 мм рт. ст.

### пульсовое давление
отдельное высчитывается пульсовое давление = систолическое - диастолическое

например 120-80=40 мм рт.ст.


Обязательно привязка к дате и ко времени у каждого значения.
надо найти способ узнавать в каком месте измерялось давление и учитывать атмосферное давление воздуха в этом месте

так же к каждому значение должна быть привязка погоды (температура, давление, влажность)



### Ввод результатов анализов
Должен ввести вручную или сфоткать как мы с тобой уже обсуждали. 

### Вредные привычки
Про алкоголь точно не узнаем правду, а вот про курение можно все разузнать. Сколько пачек в день? Какой стаж курения?

### настроение
три смайлика, учитывать каждый день
* веселый
* нормальный
* грустный


