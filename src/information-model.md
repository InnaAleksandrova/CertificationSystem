## Диаграмма классов

![Диаграмма-классов](diagrams\class-diagram.png)

<details>

  <summary>PlantUML</summary>

//www.plantuml.com/plantuml/png/bLRFRlj44BxxALQ-S6gbNYCEFS2LTx1IaqHDR8XTGAegDKa9g2r4_96Aa0eK8hYwJjnk_h_2x1intsRjRiZINt-7rhLdPhzllfdPwN6I1jtqhDFsFg3Vw55Tgn7bjA22LYIf43JdbqprL8_Mb7jUlHqaYV3fZZ9uiZdpXGWIqGq_FmkJL9nxz3FR-fG9ZnxmL7qrK3r1prM8z2vUJWBg9MLiBjJGnr6V1VNJe17YgBz00o2qKBUqKZSq4_nfJKlsllJeJxPk68SaK-mpwoNZgXwC_2hLrJPQ3VafuRVMVXdbGeC-yeU-e2aVFnAqBgcmV-RHZrI0Dz2Nj893BcZ3RtCg0BQRtswqdU4V1kWRag2_s9BLgNuPTq-JPXYcdgKRRS2V2gQL8KXOR05cUJuZ5PtjjzkIgP7b2X9ft0ZJPjWzh-WyEDLPqwhKTyelSpMW9OuqHEjXDsrzsge7QIkEFehhPvqmOjAc0dinaE--B9FJMgMGCwX9rEaufencj73PTZGkMFW1siJKv0OHaeCdj39bHxPIftFI2XfHdBIINTtL9ReSofTgecTG3aYKbQL3QqYQ2bhoOuKKjIs36WNDuO9p-AVG9S8GgUyvGpDLUymG-WjxbYtqL7bYxl1hem_kWo04m5-l1GdqZxh2TuJPGUzKRQB7QCan2rhpcmHnfZ3djvbGtz4SVCeculWRBMapxCJjkC4jqlxugw3JYdIhGDzxCoCC3gGoQNLRAWvHl-RdawtxcDPiNEgwi0RCTSo9MODUxFdW8mxXZ5QKwQEdGAFPNkJVb4CGzzaEZxUV_8zvvVbpStVvlJVA61s5x54QDTGZCOHmRiGtnRmT_NTQW3VgpnwJcY3fQiHgj9nTewzZz2G3JdN0tADVqQhLY8E5f9dTiZzfY9ma29e5XFOBeqOt-A8LDNOcUhBdBQqXTTfTj2vUBazr3H4gsAGPnwb1tPicrgrobpMXhhPN6L8l6TeURkJ_MSpmH7NAYvzcLW7jjOtb9JsltC_-aI_YWmD-7Xv-ufUxbYkOOmHnCK6Nt3C6xV-XzlTVjbLDNsle6bfWCs9G66naDgapsBb1QjNz_zyZIYoRiM_Tsswx-n9oErijuxPNjVK45-4EIeAbBbKKfvmU_Q06qDjS4oWHoEDkCxdeOavqnN1FSRKargp9yhKL1OGZZSELEhGoFmwZ4_p3zYy0

</details>

### Описание сущностей предметной области

|Сущность|Описание|Связи|
|--|--|--|
|Заявка|Заявка, которую приемщик оформляет, чтобы зафиксировать запрос клиента на сертификацию|Включает от 1 до N образцов|
|Образец|Сертифицируемый образец. Сейчас только драгоценный камень|Образец можнт принадлежать только одной заявке|
|Рабочий лист|Сущность, отражающая форму ввода специалистами оценки, гравировки, съемки данных на соответствующих этапах|На данный момент один рабочий лист создается к рабочему листу. Возможно в будущем появится возможность создавать несколько рабочих листов. 1. Для независимой оценки несколькими экспертами. Возможно в будущем нужна будет возможность печатать рабочий лист для отчетности|
|Сертификационный документ|Финальный сертификационный документ, который печатается после проведения работ|Один документ к одному образцу|
|Результаты диагностики|Результаты работы диагноста|Один к рабочему листу|
|Результаты геммологической экспертизы|Результаты работы геммолога|Один к рабочему листу|
|Гравировка|Результаты гравировку|Одна к одному образцу/рабочему листу|
|Съемка|Результаты съемки, это медиафайлы|Одна съемка для одного образца. Пока что|



