<h1><strong>Выпускная квалификационная работа по курсу "Data Science" МГТУ им. Н. Э. Баумана</strong></h1>

<strong>Тема: Прогнозирование конечных свойств композиционных материалов.</strong>
***
<p>В процессе написания ВКР:
<ul type='circle'>
  <li>Изучены теоретические основы и методы решения поставленной задачи.</li>
  <li>Проведен разведочный анализ предложенных данных. Нарисованы гистограммы распределения каждой из переменной, диаграммы ящика с усами, попарные графики рассеяния точек. Для каждой колонки получены среднее, медианное значение, проведен анализ и исключение выбросов, проверено наличие пропусков.</li>
  <li>Проведена предобработка данных (удаление шумов, нормализация и т.д.).</li>
  <li>Обучены нескольких моделей для прогноза модуля упругости при растяжении и прочности при растяжении.</li>
  <li>Написана нейронная сеть, которая будет рекомендовать соотношение матрица-наполнитель.</li>
  <li>Разработано приложение с графическим интерфейсом на Flask, которое выдает соотношение матрица-наполнитель с помощью обученных нейронных сетей.</li>
  <li>Оценены точности моделей на тренировочном и тестовом датасете.</li>
  <li>Создан данный репозиторий в GitHub, в котором выложены все материалы по ВКР.</li>
</ul>
</p>
<strong> Web-приложение на Flask. Инструкция.</strong>
<p>В разработанном веб-приложении можно спрогнозировать с помощью обученных нейронных сетей соотношение "матрица-наполнитель" композиционных материалов на основе введенных пользователем значений.</p>
<p>Пользователь изначально попадает на главную страницу, на которой находятся описание приложения и меню выбора прогнозируемой переменной. При нажатии на кнопку прогноза необходимой переменной пользователь попадает на новую страницу. На странице прогноза выбранной переменной пользователю предлагается ввести значения параметров необходимых для прогноза, после ввода всех параметров и нажатии кнопки "отправить" пользователю в виде сообщения отображается прогнозное значение переменной, полученное с помощью прогноза нейронной сети.</p>

***

                                                                                         2022 Лухнева А.В.
