# Анализ данных рынка недвижемости 2015 - 2020 год
---
**Цель исследования** - изучить данные рынка недвижимости , выявить возможные закономерности.

**В рамках исследования выдвинуты следующие гипотезы:**
- на стоимость квартиры влияют такие факторы, как:
    - общей площади;
    - жилой площади;
    - площади кухни;
    - количества комнат;
    - этажа, на котором расположена квартира (первый, последний, другой);
    - даты размещения (день недели, месяц, год).
- колличества объявлений в год сезонно
- стоимость жилья среди фаворит по колличеству объявлений в Санкт-Петербурге самая дорогая
- квартиры, находящиеся ближе к центре имеют более высокую стоимость

**Работа с данными:**
- выявлены и заполнены пропуски в данных;
- обработаны аномальные значения;
- обработаны явные и неявные дубликаты значений;
- обработы неккоректные типы данных.
---
**Гипотеза 1 - на стоимость квартиры влияет ряд приведенных ранее факторов.**

Для проверки гипотезы графически изучена корреляция данных.

Видна положительная зависимости цены от площадей и колличества комнат. 
В наибольшей степени цена квартиры зависит от общей площади, как практически симметрично зависим от жилой площади и площади кухни. 
В меньшей степени стоимость квартиры зависит от колличестав комнат, скорее всего это связанно с тем, что основная характериска, влияющая на цену - это квадратный метр, а планировка площади уже может быть разной, не всем нужно много маленьких комнаток, кто-то выберет допустим 2, но большие комнаты.

Не выявлена зависимость стоимость квартиры от даты публикации объявления.

Таким образом - **гипотеза подтверждена частично** и влияние на стоимость квартиры достоверно оказывает только характериски, связанные с площадью. 

**Гипотеза 2 - колличество объявлений в год сезонно.**

Построена гистограмма колличества объявлений по временной шкале. Виден спад в новогоднее время и дальнейший рост к лету. 

Таким образом - **гипотеза подтвержена** и колличество объявлений действительно имеет сезонный характер. 

**Гипотеза 3 - стоимость жилья в Санкт-Петербурге самая дорогая.**
    
Для проверки гипотезы собраны и отсортированны данные по необходимым признакам. 
    
**Гипотеза подтвержена** и жилье в Санкт-Петербурге действительно самое дорогое, самое дешевое жилье
по колличеству объявлений оказалось в Выборге.    

**Гипотеза 4 - квартиры, находящиеся ближе к центре имеют более высокую стоимость.**
 
Для проверки гипотезы собраны и отсортированны данные по необходимым признакам, произведены математические расчеты и построена корреляция.

## Навыки и инструменты:
Python, Pandas, Matplotlib, исследовательский анализ, визуализация данных, предобработка данных
**Гипотеза подтверждает**, по мере удаление квартиры от центра её стоимость уменьшается.       

---
**Заключение**: таким образом, обработаны и изучены данные рынка недвижимости. Выдвинут ряд предположений, который
    находит своё подтвержение в рамках анализа.  
