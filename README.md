# ZoteroCSL 🧪📝
## Обзор
Библиографические стили стандарта [Citation Style Language (CSL) 1.0.2](https://docs.citationstyles.org/en/stable/specification.html) с использованием расширения [CSL-M: citeproc-js 1.1.73](https://citeproc-js.readthedocs.io/en/latest/csl-m/) для форматов: 
* ГОСТ 7.0.5—2008
* российских научных журналов экономического профиля (Terra Economicus, Journal of Institutional Studies, Journal of Economic Regulation)

💻 Изначально разработаны для использования с библиографическим менеджером [Zotero](https://www.zotero.org/). Могут использоваться с любым другим программным обеспечением, поддерживающим стандарт CSL.

🧪 Разработано в Лаборатории экономики климатических изменений и экологического развития (CLECO) Сибирского федерального университета.

© **Авторы:** Александр Плесовских *(написание кода, тестирование, поддержка)*, Роман Гордеев *(консультирование и тестирование)*, Антон Пыжев *(идея, управление проектом, тестирование)*.

## Стиль 1: «Строгий» ГОСТ 7.0.5—2008

Разработанный стиль отличается от реализации стиля [ГОСТ 7.0.5—2008](https://github.com/romanraspopov/GOST-styles-for-Zotero):


Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote et al., 2011].

> ### Список источников:
> 1. Modelling forest carbon balances considering tree mortality and removal / R. Grote, R. Kiese, T. Grünwald [et al.] // Agricultural and Forest Meteorology. 2011. Vol. 151. No. 2. Pp. 179—190. DOI: 10.1016/j.agrformet.2010.10.002

▶ [Стиль CLECO v.4 [Автор, Год] по ГОСТу (сортировка рус. англ.).csl](https://gitverse.ru/alexandermcme/ZoteroCSL/content/main/%D0%A1%D1%82%D0%B8%D0%BB%D1%8C%20CLECO%20v.4%20%5B%D0%90%D0%B2%D1%82%D0%BE%D1%80%2C%20%D0%93%D0%BE%D0%B4%5D%20%D0%BF%D0%BE%20%D0%93%D0%9E%D0%A1%D0%A2%D1%83%20(%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%20%D1%80%D1%83%D1%81.%20%D0%B0%D0%BD%D0%B3%D0%BB.).csl)


## Стиль 2: «Практичный» ГОСТ 7.0.5—2008

Отличается от Стиля 1 порядком авторства: перечисление авторов предшествует заголовку публикации. На практике такой вариант более распространен, хотя, строго говоря, противоречит стандарту.

Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote et al., 2011].

> ### Список источников:
> 1. Grote R., Kiese R., Grünwald T. et al. Modelling forest carbon balances considering tree mortality and removal // Agricultural and Forest Meteorology. 2011. Vol. 151. No. 2. Pp. 179—190. DOI: 10.1016/j.agrformet.2010.10.002

▶ [Стиль CLECO v.5 [Автор, Год] Автор в начале (сортировка рус. англ.).csl](https://gitverse.ru/alexandermcme/ZoteroCSL/content/main/%D0%A1%D1%82%D0%B8%D0%BB%D1%8C%20CLECO%20v.5%20%5B%D0%90%D0%B2%D1%82%D0%BE%D1%80%2C%20%D0%93%D0%BE%D0%B4%5D%20%D0%90%D0%B2%D1%82%D0%BE%D1%80%20%D0%B2%20%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D0%B5%20(%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0%20%D1%80%D1%83%D1%81.%20%D0%B0%D0%BD%D0%B3%D0%BB.).csl)


## Стиль 3: Terra Economicus, Journal of Institutional Studies, Journal of Economic Regulation
Пример формирования библиографии:

> Определение баланса углерода в экосистемах является важной проблемой в экологических исследованиях [Grote, Kiese, Grünwald, Ourcival, Granier, 2011].

> ### Список источников:
> 1. Grote R., Kiese R., Grünwald T., Ourcival J.-M., Granier A. (2011). Modelling forest carbon balances considering tree mortality and removal. *Agricultural and Forest Meteorology* **151**(2): 179—190. (DOI: 10.1016/j.agrformet.2010.10.002)

▶ [CLECO (Journal of Institutional Studies, v.2).csl](https://gitverse.ru/alexandermcme/ZoteroCSL/content/main/CLECO%20(Journal%20of%20Institutional%20Studies%2C%20v.2).csl)
