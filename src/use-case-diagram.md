## Диаграмма вариантов использования

![use-case-diagram](diagrams\use-case-diagram.png)
<details>

  <summary>PlantUML</summary>

//www.plantuml.com/plantuml/png/lLVDRjj64BxlK-ojzK54IFqe3eeYG9wW1N8BO1YssXf8vS2MqKiFiLqqJTL6GMgWXm9DyWQA9K4C9L6liFj6_MPsrwkbID1jZS1G2ExCV3FppGyt3qy7-oU3i--VYi_KN8tL5B-LIjLCuZ5MQ_qS_rwhXPhHiHv9lAHghY_L68SfsUYVyKp5qzut0paubYT7ttuta8T79xs3mT5nNm1uh39zeNBzN0-5s3yO79z8zLRbQg5_0q0Eo37aCtgN-wSRiXjbX952OQbVufaP9IUymj5OJTGA7ixr1GkldF0Fii8V0F6Ri93FdCBVQgrcbAM9S4zDRCefdXmQXm9mzN5FNv87eeX5cKePy2-Sp0cb4lIz_fK3SHR-VUnite7JZ65pL25rXEof1T0_gDp3gTIYi8cpVyy-gHPS6GgqshPKtI6zXlyb12jpR8rJHBRIGx1WajFd27H5rep7HbHiy8UmrlXp3299wNk0ZeJmDPPV_DXeMFlYSNcOHfSLB0VXqLjHPcPaLzKosnVLSb_cAfsWi213lu91XeEFq1XA8SvEUmVxfptv-UD7CexYYFA-DhpuOU8fa-2NSHbkjaCaFtuK1mYTA9RgZHvQpkU6wHmbUu7eBjn4eE88Dt_I1ooKr-ZYbpJFNCub774veQP_KYbXS8ilhSl4kqmYFugSebLf1b4bY8hLu9mcZpg8dAmf7mwH4nrnfsSx1LloyGxu4zzybfCdVJjsc4GFWOcoKRGBICrR846OIpm-yD3F8NSvTRRGOWCtjQtikjlkIu1M0CK5f1Qn2CfV4D7OU4043wZVaef2t0Eg9BzM0QTj5YMJoWNUD4Bzf4h3Y71MPBjJYEMhhnkyX90a4i9ZeKVbQUqMaBhCzXXCS-z9RZn4fvQk2P7LTgln3BaCkm5cAuh3wAhCSsfbKqlusARJpSuz4GvWanru3Yb7tfR8W1l3ZRQ7I8e8RI2yWVSPnMOx0JWp_aHYaP4n4t7D3JAXoOdqxohZWR3PG7d88-y3ID7ZphrptWbzs-8jUCA00k-J1lkU-cthRBl5m54lksmluSw5pkicCpdBy5COz69yluXtluo8yutFNdr-kmN8X27dUiJPpRRh0qPzYG875_fo9qJZTV0dfSEi_-A3z3P3HbpXVHh6klH-yc28shMWOHZjA2aC_skLkP7d0IvYfPjOTYCd1SpO1971R6YvAjaVIRF0IElVzUuql6UfjAwiGk3J8AF3un_wqPV_vTCW7qZEOA5V4M6qLm98xFnwbKwzIhTEvNyit5hdhVhuTijKRjDx6nX9SWSOpT9GuwwCpfwnHjnvO1Rmcc_SApsoEftuHgTS1JV7DLyjhd5WRZARjoVkGfLjtYF1Rd2FR9mzQt0CmbmAPODV4tivnDjjqhNQrhWPliRtIgz-LfXK2UzcdLM3t_5s4-OcRBFg2E5llZWpot_peciETuMwOfe-qN9vsEiVul-j_m00

</details>

## План реализации сценариев

### MVP

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|1. Регистрация и авторизация|1.1|Авторизация в системе|Регистрация не предусмотрена. Пользователи будут зарегистрированы заранее, им будут выданы учетные записи|
|2. Приемка|2.1|Просмотр списка заявок||
|2. Приемка|2.2|Регистрация новой заявки||
|2. Приемка|2.3|Регистрация нового образца||
|2. Приемка|2.4|Печать документа заявки|Печатная форма документа Заявка|
|2. Приемка|2.5|Поиск по заявкам и образцам||
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
|2. Приемка|2.6|Печать QR-кода для образца|До реализации приемщик будет вручную писать номер образца для его идентификации на бумажке, прикрепленной к образцу|
|5. Завершение работ|5.2|Печать Акта о завершении работ|Акт не содержит подробную информацию о списке образцов, поэтому временно его можно делать вручную|


### 2 релиз

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|2. Приемка|2.3.1|Редактирование образца|Перенесено на 2 релиз, так как нужно выявить много ограничений и бизнес-правил, связанных с изменением свойств образца. На первых этапах сразу не будет большой объем сертификации, поэтому не самая критичная функциональность|
|2. Приемка|2.7|Расчет стоимости сертификации|До реализации расчет вручную|
|3. Работа над образцами|3.6|Плоттинг-редактор|Встроенный в приложение визуальный редактор плоттинга. До реализации делают по старинке вручную и грузят картинку|
|6. Аналитика и отчетность|6.1|Выгрузка отчета по выпущенным сертификатам|Некритично на ранних этапах эксплуатации|
