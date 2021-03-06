# Титаник
Работу выполнила Круглова Мария, гр. М8О-308Б-19.
## Описание набора данных
Ссылка на набор данных: https://www.kaggle.com/competitions/titanic/data

Набор данных состоит из трех файлов:
1. [Train dataset](data/train.csv) - этот файл мы и будем рассматривать
1. [Test dataset](data/test.csv)
1. [Submission example](data/gender_submission.csv)

### Train dataset
В нем находятся 10 колонок:
1. `PassengerId` - номер пассажира
1. `Survived` - целевая переменная. Выжил пассажир или нет
1. `Pclass` - номер класса
1. `Name` - имя
1. `Sex` - пол
1. `Age` - возраст
1. `SibSp` - количество родственников(за исключением детей) на борту
1. `Parch` - количество детей
1. `Ticket` - номер билета
1. `Fare` - стоимость билета


## Выполненные действия
1. Скачивание данных
1. Общий анализ данных - просмотр и выявление очевидных проблем в данных
1. Заполнение пропусков в данных
1. Анализ конкретных колонок, преобразование их в более удобные типы данных
1. Удаление ненужных или не имеющих смысловой нагрузки в рамках данной задачи признаков
1. Создание новых признаков
1. Построение матрицы корреляции числовых признаков
1. Построение графиков:

    1. Графики подсчета
    1. Коробочные графики(boxplot-ы)
    1. Гистограмма

## Выводы
По графикам видны некоторые линейные зависимости, которые облегчат в дальнейшем обучение линейных моделей.

## Проблемы при выполнении
Создание новых признаков в данном наборе данных нетривиально.