# Исследование надёжности заёмщиков

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.


Работа проводилась с файлом /datasets/data.csv, где :

- [x]  children — количество детей в семье
- [x]  days_employed — общий трудовой стаж в днях
- [x]  dob_years — возраст клиента в годах
- [x]  education — уровень образования клиента
- [x]  education_id — идентификатор уровня образования
- [x]  family_status — семейное положение
- [x]  family_status_id — идентификатор семейного положения
- [x]  gender — пол клиента
- [x]  income_type — тип занятости
- [x]  debt — имел ли задолженность по возврату кредитов
- [x]  total_income — ежемесячный доход
- [x]  purpose — цель получения кредита

# Шаг 4. Общий вывод

Были обнаружены и заменены медианными значениями пропуски в таблице, так же проведена работа с "артефактами". Возможные причины их появления в таблице - нехватка информации от заказчика. Вещественные типы данных были переведены в целочисленные, так же из таблицы были удалены все дубликаты. Мы лемматизировали цели кредита и структурировали в более читабельный вид информацию. Были проанализирлванны зависимости между различными факторами и кредитоспособностью клиентов банка.
