## Диаграмма вариантов использования

![use-case-diagram](diagrams\use-case-diagram.png)
<details>

  <summary>PlantUML</summary>

//www.plantuml.com/plantuml/png/lLVDRjj64BxpAVRMvY0Yf7uK1qKH84_G0ha5C0nRRGsaSc3BwAM7s2gQfcgZ83NGGu4cUGF5aY264gbNc7sZVZFSpOehid9H8p0KWZipttppCyFDWxF1mUdW_FidmMUqe0dDyCieeRd2Oq9h_Gp_NjEIvdoinmel2Itqa2OuJDX6_und4ZpfVJDGWnDrUlpjTmDrT7pQEnmSd_G304yerPUKwsTw50G7XuEJKqLlAAUb_Wq0EI0daC_vNHsSRSW-AeD60eMLVe5dMYXPuHME9ZIb31ukzAK8hwpm3xR27m3ncufGpgp2txIcEKTPCDodgGavmLEe2HM0quTzFMGFaY8MfPG8u5yuMJ1ABUWx_QiGiHRkVM9jtYAdgS3cg49Y4x9FIw2_fzp1KM9GnCJQlnEVN0kf31EjjwrKjqYlu7y5GLOS6-C4p38zGXQAuFG5Y6PiBNXYX69p_a1hZJ-RGGIfN0_mKH2u6gilVcmqhBr_N4cpq1K5cuFIqPkWogoGNTNAR5_KorsPwtHAXKKoz4iOf3Zu08sH2eBpizxXmLbFVVxeeOh2AEIuhsrbx339b2daLt05Rdw7a_peOLH2w8IHejTwP7A-A3ATesJFmUxIJWGg3hhvupvWeRn65x-GUUPohk18oWar_HCbZ24jlZ8kO-So3jqeIeX6fLaEB9R0ta9fwZh81FQuRsO7uwGau74nI0QglOKK6woPQI4tbxAd05Y14damyGq8GPWhFDwpb1QGs_WwMsZHlt82Q0sGpwl96KNwdtFIiVs0c0Dno2MdZEi0g8e0MnvEIvOc1qUf57lJ2BLKb7YCK5yFe-rn-UhhXYma18c0y5ZgSNLOUnvIHx8zGQQb3vKq8TZHoZOaejfkEvad6s6tXDaA8uzTZNdERLtK4Zwsqsddw6vGxjccE70vH8ooEJa2QGmxvWuYzX0aWQ_XVSxSJ2S0PowVIomrDfP4N4k3J7cAGlqxfT1VssYWF9BnTmGIZ8frRvrtFDyTOR_auHUKZAODyJrpczVQTdtYtT1-SuTmPwdBwacBc5NvirZgnUYUZtUlAX4NxXDuW_ZsFCXO81TwBD7Dj-k3ZBeIbHnSwk6TCfgCtPySZcJz5qVIsOm4CSFxhCnrvVpafI5gxmGjqsY7iJVyhoYr8oy3x6Cb6rXsEySUPbIGI64sChcgs1znqyj8wx_rxgnyvw9aLranRlXEgF3ev8T--2MlQ7LVCIM0l-GCyABmL3gxLRgxLFx7UjpflBMRtrwLoaqwPGCZZcy1erb9DUggyFofQ4IT-yMwNCjTETDZezEEFkgqQrGwJgKQ1TV2jTmRhd5GN5CshqRILfHkNX9HWD8biN7-j24qW-B6fnho6fkR7zvkaX6ZROoRvTVeRkMzpWZZEk7jxATwy5jULq5npJLHTOB0NMjnLcpppLjiSRWNq9MawHDjYmUz_X7-K_eF

</details>

## План реализации сценариев

### MVP

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|1. Регистрация и авторизация|1.1|Авторизация в системе|Регистрация не предусмотрена. Пользователи будут зарегистрированы заранее, им будут выданы учетные записи|
|2. Приемка|2.1|Регистрация новой заявки||
|2. Приемка|2.1.1|Редактирование заявки||
|2. Приемка|2.2|Регистрация нового образца||
|2. Приемка|2.2.1|Редактирование образца||
|2. Приемка|2.3|Печать документа заявки|Печатная форма документа Заявка|
|2. Приемка|2.4|Поиск по заявкам и образцам||
|3. Работа над образцами|3.1||Поиск рабочего листа||
|3. Работа над образцами|3.4||Внесение результатов диагностики в рабочий лист||
|3. Работа над образцами|3.5||Внесение результатов геммологической экспертизы в рабочий лист||
|3. Работа над образцами|3.7||Получение текста гравировки||
|3. Работа над образцами|3.8||Внесение съемки в рабочий лист||
|4. Печать сертификационного документа|4.1||Печать сертификационного документа||
|5. Завершение работ|5.1||Закрытие заявки||

### 1 релиз

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|2. Приемка|2.5|Печать QR-кода для образца|До реализации приемщик будет вручную писать номер образца для его идентификации на бумажке, прикрепленной к образцу|
|5. Завершение работ|5.2|Печать Акта о завершении работ|Акт не содержит подробную информацию о списке образцов, поэтому временно его можно делать вручную|


### 2 релиз

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|2. Приемка|2.6|Расчет стоимости сертификации|До реализации расчет вручную|
|3. Работа над образцами|3.6|Плоттинг-редактор|Встроенный в приложение визуальный редактор плоттинга. До реализации делают по старинке вручную и грузят картинку|
|6. Аналитика и отчетность|6.1|Выгрузка отчета по выпущенным сертификатам|Некритично на ранних этапах эксплуатации|
