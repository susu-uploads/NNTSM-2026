---
ru: "2. Реализация механизма внимания и Transformer"
en: "2. Implementation of attention mechanism and Transformer"
code: "practice-2-implementation-of-attention-mechanism-and-transformer"
origin: "https://edu.susu.ru/mod/assign/view.php?id=8874774"
---

В данной практической работе рассматривается устройство и применение модели Transformer для генерации текста. В качестве данных используется тот же корпус русскоязычных новостных статей («Газета.Ru»), что и в ПЗ-1, что позволяет напрямую сравнивать результаты с рекуррентными моделями.

#### Критерии оценивания

**1 балл** выставляется за выполнение Блока 1: обучение TransformerLMи сравнение с LSTM на одном токенизаторе в сопоставимых условиях, логирование в MLflow, построение графиков письменные выводы. Необходимо быть готовым объяснить реализованный код и теоретическую часть: positional encoding, attention, causal mask, multi-head attention.

**1 балл** начисляется за выполнение Блока 2: эксперименты с greedy-генерацией (задание 2.1), температурой (задание 2.2, обе части) и др.

**1 балл** начисляются за выполнение Блока 3 (задание из раздела 3.2): графики времени  прохода по выборке и кросс-энтропии в зависимости от длины контекста для моделей с полным вниманием и со скользящим окном, сравнение генерации и ответы на вопросы.

В качестве ответа необходимо прикрепить файл в формате .ipynb, названный по шаблону:

```
Например: 02-transformers_2026_ИЕТН2-28_Иванов.ipynb
```

- [02-transformers.ipynb](https://edu.susu.ru/pluginfile.php/12426949/mod_assign/introattachment/0/02-transformers.ipynb?forcedownload=1)
- [model_cs.tar.xz](https://edu.susu.ru/pluginfile.php/12426949/mod_assign/introattachment/0/model_cs.tar.xz?forcedownload=1)
- [model.tar.xz](https://edu.susu.ru/pluginfile.php/12426949/mod_assign/introattachment/0/model.tar.xz?forcedownload=1)
