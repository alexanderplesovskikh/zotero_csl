# ZoteroCSL 🧪📝

## Обзор
Библиографические стили стандарта [Citation Style Language (CSL) 1.0.2](https://docs.citationstyles.org/en/stable/specification.html) с использованием расширения [CSL-M: citeproc-js 1.1.73](https://citeproc-js.readthedocs.io/en/latest/csl-m/) для форматов: 
* ГОСТ 7.0.5—2008
* российских научных журналов экономического профиля (Terra Economicus, Journal of Institutional Studies, Journal of Economic Regulation)

💻 Изначально разработаны для использования с библиографическим менеджером [Zotero](https://www.zotero.org/). Могут использоваться с любым другим программным обеспечением, поддерживающим стандарт CSL.

🧪 Разработано в Лаборатории экономики климатических изменений и экологического развития (CLECO) Сибирского федерального университета.

© **Авторы:** Александр Плесовских *(написание кода, тестирование, поддержка)*, Роман Гордеев *(консультирование и тестирование)*, Антон Пыжев *(идея, управление проектом, тестирование)*.

![Zotero hero image](https://github.com/alexanderplesovskikh/zotero_csl/blob/main/zotero.png)

## Стиль 1: «Строгий» ГОСТ 7.0.5—2008

Разработанный стиль отличается от реализации стиля [ГОСТ 7.0.5—2008](https://github.com/romanraspopov/GOST-styles-for-Zotero):

| Параметр | Стиль 1: «Строгий» ГОСТ 7.0.5—2008 | [ГОСТ 7.0.5—2008](https://github.com/romanraspopov/GOST-styles-for-Zotero) |
| --- | -------------------- | -------------------- |
| ✅ Диапазон страниц отделяется тире вместо дефиса | 1. Замолодчиков Д. Г., Грабовский В. И., Краев Г. Н. Динамика бюджета углерода лесов России за два последних десятилетия // Лесоведение. 2015. № 6. С. 16`—`28. | 1.	Замолодчиков, Д. Г. Динамика бюджета углерода лесов России за два последних десятилетия / Д. Г. Замолодчиков, В. И. Грабовский, Г. Н. Краев // Лесоведение. – 2015. – № 6. – С. 16`-`28. |
| ✅ Между атрибутами год, том, номер выпуска и т.д. отсутствует тире | 1. Translating climate risk assessments into more effective adaptation decision-making: The importance of social and political aspects of place-based climate risk / A. P. Kythreotis, M. Hannaford, C. Howarth, G. Bosworth // Environmental Science & Policy. 2024. Vol. 154. Art. no. 103705. DOI: 10.1016/j.envsci.2024.103705 | 1. Translating climate risk assessments into more effective adaptation decision-making: The importance of social and political aspects of place-based climate risk / A. P. Kythreotis, M. Hannaford, C. Howarth, G. Bosworth // Environmental Science & Policy. `–` 2024. `–` Vol. 154. `–` P. 103705. |
| ✅ Поддержка DOI | 1. Recognition of climate-related risks for prehospital emergency medical service and emergency department in Finland – A Delphi study / H. Karstila, R. Ruuhela, R. Rajala, P. Roivainen // International Emergency Nursing. 2024. Vol. 73. Art. no. 101421. `DOI: 10.1016/j.ienj.2024.101421` | 1.	Recognition of climate-related risks for prehospital emergency medical service and emergency department in Finland – A Delphi study / H. Karstila, R. Ruuhela, R. Rajala, P. Roivainen // International Emergency Nursing. – 2024. – Vol. 73. – P. 101421. |
| ✅ Поддержка Art. no. (Статья №.) | 1. Translating climate risk assessments into more effective adaptation decision-making: The importance of social and political aspects of place-based climate risk / A. P. Kythreotis, M. Hannaford, C. Howarth, G. Bosworth // Environmental Science & Policy. 2024. Vol. 154. `Art. no. 103705.` DOI: 10.1016/j.envsci.2024.103705 | 1.	Translating climate risk assessments into more effective adaptation decision-making: The importance of social and political aspects of place-based climate risk / A. P. Kythreotis, M. Hannaford, C. Howarth, G. Bosworth // Environmental Science & Policy. – 2024. – Vol. 154. – `P. 103705.` |

Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote et al., 2011].

> ### Список источников:
> 1. Modelling forest carbon balances considering tree mortality and removal / R. Grote, R. Kiese, T. Grünwald [et al.] // Agricultural and Forest Meteorology. 2011. Vol. 151. No. 2. Pp. 179—190. DOI: 10.1016/j.agrformet.2010.10.002

▶ [Стиль CLECO v.4 [Автор, Год] по ГОСТу (сортировка рус. англ.).csl](https://github.com/alexanderplesovskikh/zotero_csl/blob/main/%D0%A1%D1%82%D0%B8%D0%BB%D1%8C%20CLECO%20v.4%20%5B%D0%90%D0%B2%D1%82%D0%BE%D1%80%2C%20%D0%93%D0%BE%D0%B4%5D%20%D0%BF%D0%BE%20%D0%93%D0%9E%D0%A1%D0%A2%D1%83%20(%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%20%D1%80%D1%83%D1%81.%20%D0%B0%D0%BD%D0%B3%D0%BB.).csl)


## Стиль 2: «Практичный» ГОСТ 7.0.5—2008

Отличается от Стиля 1 порядком авторства: перечисление авторов предшествует заголовку публикации. На практике такой вариант более распространен, хотя, строго говоря, противоречит стандарту.

Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote et al., 2011].

> ### Список источников:
> 1. Grote R., Kiese R., Grünwald T. et al. Modelling forest carbon balances considering tree mortality and removal // Agricultural and Forest Meteorology. 2011. Vol. 151. No. 2. Pp. 179—190. DOI: 10.1016/j.agrformet.2010.10.002

▶ [Стиль CLECO v.5 [Автор, Год] Автор в начале (сортировка рус. англ.).csl](https://github.com/alexanderplesovskikh/zotero_csl/blob/main/%D0%A1%D1%82%D0%B8%D0%BB%D1%8C%20CLECO%20v.5%20%5B%D0%90%D0%B2%D1%82%D0%BE%D1%80%2C%20%D0%93%D0%BE%D0%B4%5D%20%D0%90%D0%B2%D1%82%D0%BE%D1%80%20%D0%B2%20%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D0%B5%20(%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%20%D1%80%D1%83%D1%81.%20%D0%B0%D0%BD%D0%B3%D0%BB.).csl)


## Стиль 3: Terra Economicus, Journal of Institutional Studies, Journal of Economic Regulation
Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote, Kiese, Grünwald, Ourcival, Granier, 2011].

> ### Список источников:
> 1. Grote R., Kiese R., Grünwald T., Ourcival J.-M., Granier A. (2011). Modelling forest carbon balances considering tree mortality and removal. *Agricultural and Forest Meteorology* **151**(2): 179—190. (DOI: 10.1016/j.agrformet.2010.10.002)

▶ [CLECO (Journal of Institutional Studies, v.2).csl](https://github.com/alexanderplesovskikh/zotero_csl/blob/main/CLECO%20(Journal%20of%20Institutional%20Studies%2C%20v.2).csl)

## Установка в библиографическом менеджере Zotero
Для установки скачайте необходимый стиль:

`Правка > Настройки > Цитирование > + > Перейдите к скачанному стилю > Открыть > OK`

## Совместимость с Zotero
Стили протестированы в последней версии Zotero. Некоторые стили не являются валидными из-за расширения CSL-M: citeproc-js, такие стили тем не менее протестированы в Zotero и корректно работают в нём.

## Дополнительные материалы
Полезные советы по настройке облачного хранилища, организации работы в библиографическом менеджере Zotero и многое другое в [Руководстве к стилям CLECO.pdf](https://github.com/alexanderplesovskikh/zotero_csl/blob/main/%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE%20%D0%BA%20%D1%81%D1%82%D0%B8%D0%BB%D1%8F%D0%BC%20CLECO.pdf)

