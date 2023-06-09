# Исследование данных сервиса “Яндекс.Недвижимость” - исследование надёжности заёмщиков.

## Описание вопроса
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Итог:
* Зависимость между колчеством детей и возратом кредита в срок подтвердилась (разница 2%) относительно групп, но не общего процента. Общий процент от "возвратности" кредита среди групп с разным количеством детей равен 8.1%. Минимальне значение в 7.5% группа без детей. Максимальное значение в 9.7% группа с 4-мя детьми. Быстре выплачивают кредиты группа без детей.
* Зависимость между семейным положением и возвратом кредита в срок подтвердилась (разница 2%) относительно групп, но не общего процента. Группа людей, не имеющих "долговых обязательств" перед друг другом (Не женат / не замужем) - 9.7%, менее организованы , чем группа людей "вдовец / вдова" 6.6%.
* Зависимость между уровнем дохода и возвратом кредита в срок срок подтвердилась (разница 3%). Группа людей с категорией D (с заработком 30001–50000) выплачивают бысрее кредит, чем все остальные, даже категории А (с заработком 1000001 и выше), где количество дебиторов одинаковое.
* Гипотеза о зависимости целей на возврат, тоже подтвердились "операции с недвижимостью" 7.2% (разница 2%), следовательно кредиты на недвижимость выплачивают быстрее , чем "операции с автомобилем" 9.3.

## Навыки и инструменты:
Python, Pandas, предобработка данных, работа с дубликатами, пропусками данных, категоризация, визуализация данных

---
**Проект завершен, можно ознакомиться в файле [credit_scoring](https://github.com/VeniaminSh/Practicum_Projects/blob/main/2%20Project%20(Кредитный%20скоринг)%20-%20Исследование%20надёжности%20заёмщиков/credit_scoring.ipynb)**

