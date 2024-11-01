## Диаграмма вариантов использования

![use-case-diagram](diagrams\use-case-diagram.png)
<details>

  <summary>PlantUML</summary>

//www.plantuml.com/plantuml/png/lLVTRXj55BxVfvWxo8LNtVMFcmgXIdq2a7fNAOeI0v6AKoMEkE4YZX6b6EggHE82YRPluFf7tgxjzIkSUIE-EJFJyKnsSO08HUvgvvppdU_ydBFJX-UzmxFUnRTFeqzeGMEQuRUcZEO2Zp5jv2N-dT2IvkfOZWHUCbh80Ornc2aR-IEUMVIqyrLFz4x5sSdNt_J4ySbPvwXtSjgD03ocN5vH8I_bC8eEZtgdPuBUK45B-Gi02a2E8P-hTt5ulYNxg0mQu4Gh-GBFN2jPuJMEnZG5lqBsvHKBhwtmDsM5Fm3YDsKXdrc5Fsb3SnMbPdX0KnDoXYTJOoe0fmy7Sg0yS8gKAAUC0V_0oKAXL8A-apyp4MlXtiVMvYrocZDiWIfaDY47j0JwUoeS76K6XKsi_Jlbasl1bL54gsrBrItIA_XVGR3MnyOu0xEr728BEZZP1z6ricOyDbB5Hlv0QuC_cq44ALmFgACeSZKMdtrVgndxyBYSfjPb1PC3_-XDL6QcPTVLCjCNbN9NvaeThx18Xdm9Wnm77w0n555qSTuvEZplY4yVFn99dCGgxecjZ1qcdZ8X-ngNuUPxAicF7oKUGYjE1BsMGvFpXSvqWP8z1xihEn6eEEWMJxg0XV86NVn2pJENSmL7N4weoHyeKnZSuYlZCdKkqzYD8eTeLEeUgnIiM0tEQSLqBfMJZOg7ANAW8-xqV2-mLJxU0d_gci_av4dNZ1qcqK5WeWoBPe3ai6Qc-zn8yue3O0bA4i3KRq48maBWyLv9QG6vJKth1bhojvm0MW4KycgeOg1oprMzi3Y1M01nG2jLMrL2G9K4s0XmcdhVScsuJxQDq0Q2CfyHpiAYjG8kNtnPurs6814G7aivAWzhFq1ggsm3fQzRM73_WXsjR2yZgh1ZxJV8OBOzp4QS-Eogp0ir4RgMy74pdNO4xqN-7DVPWSkXl3HB5n5mOzWDuI3I4A49XDVmFbVSJ2S0PyvVMkn3PSo9c723JDK0nl9NodckJ3HG7lBcS0GoZ8frRvstVD-cU4iULA30-xJ6lcTkQLlRTaWSzJ8xUm1tbZflhLp7BFmlgjUBoVqGxtvP8lfRNy_TyUq7a2b3BkI8evlVh0yowahaERYIWpqVZTV1xnoEolfFZgIp6JBY6kypd-lA-Icy8Mhk1FLfDECq6FvNbDkHvm4EiR9jBBFOqm0pqIHoc0rDhahsHreFCjBuPxqxywzhbEqgQnJX2oFYuzFlkl7d_-OB8nu8Zc0fNwg4gRtYGMBfxrPfxLPfxr3vBmjtf_F6RdxxPIgtwRqjZ3Iz0unwATMaBUABPwoHj1xe1RpXY_jQZenEC_ceqwnGQJcLSXJSKJTyYPdWGD-PjkzftAYKRzzOKG3lnbgxU5PZcf6-VeeQlwRc6egtssJ4Q1lZkl-Qt2kzP1fXMYMycurN0Nxt2p3ITsuJLIkAt1qRP_hxi7sbreVx4Lrpclwd_VEmqpt6_v3_0W00

</details>

## План реализации сценариев

### MVP

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|1. Регистрация и авторизация|1.1|Авторизация в системе|Регистрация не предусмотрена. Пользователи будут зарегистрированы заранее, им будут выданы учетные записи|
|2. Приемка|2.1|Просмотр списка заявок||
|2. Приемка|2.2|Регистрация новой заявки||
|2. Приемка|2.2.1|Редактирование заявки||
|2. Приемка|2.3|Регистрация нового образца||
|2. Приемка|2.3.1|Редактирование образца||
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
|2. Приемка|2.7|Расчет стоимости сертификации|До реализации расчет вручную|
|3. Работа над образцами|3.6|Плоттинг-редактор|Встроенный в приложение визуальный редактор плоттинга. До реализации делают по старинке вручную и грузят картинку|
|6. Аналитика и отчетность|6.1|Выгрузка отчета по выпущенным сертификатам|Некритично на ранних этапах эксплуатации|
