# Домашнее задание №4

Код:  [Colab](https://colab.research.google.com/drive/1XKFa_DzlJDejt9F7eQDlQhBAPRKhyI2x?usp=sharing)

### Скриншот из MultiQC. Исходные риды имеют хорошее качество. 


<img src="images/multiqc.jpg" alt="multiqc.jpg" width="700"/>


### Таблица со статистикой по каждому из 6-ти образцов:

* ID образца

* Тип образца (перепрограммированние или контроль)

* Общее кол-во исходных чтений

* Кол-во и процент чтений, которые были успешно откартированы на геном (уникально или нет)

* Кол-во и процент уникально откартированных чтений

* Общее кол-во чтений, которые попали на гены

<img src="images/result_table.jpg" alt="result_table.jpg" width="700"/>

### Таблица ALL.counts с кол-вом попаданий ридов для каждого гена:

<img src="images/all_counts_table.jpg" alt="all_counts_table.jpg" width="450"/>

# БОНУС

Код:  [Colab](https://colab.research.google.com/drive/1dsrZ7rG84w6nVxQgCjSy_3OAG1qC49rO?usp=sharing)

## Графики из анализа DESeq2 (бонус)


### Тепловая карта

<img src="images/heatmap_dds.png" alt="heatmap_dds.png" width="500"/>

На диагонале отличий нет, внутри теста и контроля отличий мало.

### MA-plot

<img src="images/ma_dds.png" alt="ma_dds.png" width="500"/>

### Для нескольких генов, которые наиболее значимо поменяли свою экспрессию - графики со значениями 'normalized counts' в контрольных и перепрограммированных образцах

<img src="images/diff_gene_1.png" alt="diff_gene_1.png" width="500"/>


<img src="images/diff_gene_2.png" alt="diff_gene_2.png" width="500"/>

Видим значительное отличие в экспрессии между тестом и контролем.
