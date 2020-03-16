# MaxFlow

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e76c633847554ee484a50f21a00db98d)](https://app.codacy.com/manual/kovinevmv/MaxFlow?utm_source=github.com&utm_medium=referral&utm_content=kovinevmv/MaxFlow&utm_campaign=Badge_Grade_Dashboard)

Программа расчета максимального потока в сети с использованием анимации.

## Описание

Программа снабжена графическим редактором графов, позволяющимпользователю создать вершины графа, дать им имена, создать дуги, соединяющие вершины, задать веса дуг, перемещать вершины (и связанные с ними дуги) по экрану для получения удобного расположения. Графический редактор позволяет сохранять созданный граф в файле и восстанавливать граф из файла. Для решения задачи пользователь задает сток и исток и запускает алгоритм. Программа на первом этапе решает задачу по шагам для лучшего понимания процесса решения и пересчёта весов дуг. Для улучшения визуализации прохождения потока по каждой ветке с помощью средств анимации отображается прохождение транспортного средства. Программа позволяет получить значение максимального потока и протокол работы, который можно сохранить, и демонстрирует прохождение максимального потока неограниченное время с прохождением транспортных средств.

**Язык программирования: С++ в среде Qt 5.7**

## Интерфейс

![Example](https://github.com/kovinevmv/MaxFlow/blob/master/docs/example.png?raw=true)

## Дополнительный функционал

* Сохранение созданного или отреактированного графа в виде файла:
	* Простой файл *.txt*, граф хранится как список инцидентности 
	* Форматированный файл *.grph*, сохранется положение вершин, цвет вершин, связи между вершинами, веса ребер и т.д.
	* Форматированный сжатый файл *.zgrph*, аналогичные возожности, что и форматированный, только со сжатием по алгоритму *deflate*
* Наличие примеров созданных графов 
* Справка с описанием работы алгоритма и работы с программой для пользователя






