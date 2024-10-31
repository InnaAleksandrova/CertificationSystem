## Диаграмма вариантов использования

![use-case-diagram](diagrams\use-case-diagram.png)
<details>

  <summary>PlantUML</summary>

//www.plantuml.com/plantuml/png/lLVDRjj64BxpAVQMvY2Yf2Gg3eeYG9wW1N8BO1YssXf8vS2MqKiFiLGqJTL6GMgWXm9jyWQo9K4q9LElCFj6_MQMwnNNPEMYHc4e17TclldcPuQR9oVzlUF-wRSlWWUqe0dDyBkcbEOAZmcjzIlyUqbBclEn7YkyfBJGGvhWC6KR_IEUQV2Y-rLVzO_KyU7Nt_JLmU5nTxz_UDGB03oXJ0yerw_qA0Zszlj7nuh-efoM-XS0v82SG3xdTxLtiY6xKGODSAALVeDdPfIiy1n74vg2NwxFz424vrRu6rlX3u3uJKKePrRXJrhJdACq37TfMeISuYdKX0h0wMfN3za3fqX46QK2-0TE5enI2_fH_on4h8LxdrYR3yXf9h0vgf3QXEpI4kWNb3iuIWMbCB7s7zcdr48gmqJhRIlLkLI87g1h_DduGL6v2l9H4BWAgS--RpIgqJmbIzS_HY6hp8til5PcorWhTrMfrIdL0T7hjp38S705ZP4AWjEJxlxUILTzykofYi8eLFIEBcqYRU_BK2XzPd05RlwGS_piQLH2IC98qNizAfAyaDG2Qw1VWzt0DZ0A1BhvynvWeRn6qxsHyRl6smgEE2PMqpzGoXZIaQl2PUnSng6R70cnK6cM0uibi0zGcfeGO683UzuhMXtThoJWiUdx0gfz2oaki6P5pxWnahK2m0gKo8E9xq08mbpXSI7pke3SnfVSGel-aHD0Qu1yNatEADB_cfEEPGN478X3Md61k0w0gWYmvU6qPCTnS9H9iJUDK4j5gSS8zVKmsXwNBxvioFv0a0W8ZwKULuUruo4bd6sWd9a-LDA4O4Shsv28ocyxk_SBp4u9inL67hiQyvpRsjGIFcwdqyxHfq6vPvlYmEMGOvH5XmYaCUoOEuZOGv04leVtENChEW4uS_cwOK6niIJYKXfaobCKwbyfW_xQHWFbaOo_8v3IrOrxwppnV2V2VYd33nHudpR4zyojMclRyObtGlk97CATfIwh9pCng_9NhDIBqICVxr5L8ixS5-iEyUruaB50BlHOeflVhWyowafKSZ3GmuTbD1cxtoKSplfFZgIp6GdYDTvdPQuhvoSl3L5xAsYPHZkClU5_HvaTUHbW7olTmBBREVOm8qCYWzd8vAfgVyHDBoEjVzUxi_8LYT9jPSMuuJkXmeEZxthXvxoYrMF5b03-bZF0Yy9JIRQhTBQf_8VrkDLvQpk_dIgLktJA1aOStmD6iv9gr57XwKlHY9B7PbskvMfxhSU5JZkwqMdNg2HEfHebU20N_vGkSM2kAPjN8sahoZPlXIX0wLROE7tP49g1kVMfXhp6nIlUxf8H81Q6pJ9Eq-78rw7oXbS8uphX_MogUl1xNbo1kV0MKIL1u2wuE3DxVVC-Qmvt0ZgNfFrlU-D9jtU0_q_-3G00

</details>

## План реализации сценариев

### MVP

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|1. Регистрация и авторизация|1.1|Авторизация в системе|Регистрация не предусмотрена. Пользователи будут зарегистрированы заранее, им будут выданы учетные записи|
|2. Приемка|2.1|Регистрация новой заявки||
|2. Приемка|2.1|Редактирование заявки||
|2. Приемка|2.2|Регистрация нового образца||
|2. Приемка|2.2.1|Редактирование образца||
|2. Приемка|2.3|Печать документа заявки|Печатная форма документа Заявка|
|2. Приемка|2.4|Поиск по заявкам и образцам||
|3. Работа над образцами|2.3|Печать документа заявки|Печатная форма документа Заявка|

### 1 релиз

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|2. Приемка|2.5|Печать QR-кода для образца|До реализации приемщик будет вручную писать номер образца для его идентификации на бумажке, прикрепленной к образцу|


### 2 релиз

|Функциональный блок|Номер|Наименование|Комментарий|
|--|--|--|--|
|2. Приемка|2.6|Расчет стоимости сертификации|До реализации расчет вручную|
