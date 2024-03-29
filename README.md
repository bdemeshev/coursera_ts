# курсера - курс по временным рядам

## план 9 недель

### Неделя 1

* Задачи и данные

    * Прогнозирование рядов
    * Обнаружение разладки
    * Кластеризация
    * Разложение ряда на составляющие

* Визуализация
* ACF, PACF — как коэффициенты в регрессиях?   
* Что сюда ещё включить? Больше практики? 

### Неделя 2. Прогнозирование без статистики
* регрессия
* наивная
* сезонная наивная
* STL-разложение
* theta-метод
* Обучающая, тестовая и валидационная выборка
* Кросс-валидация?

### Неделя 3. Экспоненциальное сглаживание

* Белый шум
* ETS-модель

### Неделя 4. Несезонная ARIMA без отклонений от здравомыслия

* Стационарность 
* Второй взгляд на ACF/PACF
* ARIMA уравнение
* Обратимость
* ARIMA процесс
### Неделя 5. Автоматическая ARIMA с сезонностью

* ARIMA сезонная 
* Тесты на стационарность
* AIC, BIC
* Процедура Хандакара-Хиндмана
### Неделя 6. Страшная неделя про синусы, косинусы и комплексные числа

* Дискретное преобразование Фурье
* Тригонометрическая сезонность
* успеть ли TBATS?
### Неделя 7. ORBIT без сахара

* Байесовский подход
* Local Global Trend 
* Теория в простом случае
* Примеры с размахиванием руками
### Неделя 8. PROPHET

* Теория в простом случае
* Примеры с размахиванием руками
### Неделя 5. Что осталось за кадром?

* Обнаружение разладки
* Кластеризация DTW


### Полностью выкидываем:

* Модели прогнозирования волатильности
* VAR/SVAR
* нейронные сети

### Хотелки:

Хотелки либо войдут в план курса, либо будут выкинуты :)

* Модель Кростона
* Фильтр Калмана
* pid controller?


## Источники мудрости:


по R:

https://robjhyndman.com/teaching/

https://otexts.com/fpp3/

https://github.com/rstudio-conf-2020/time-series-forecasting

* Анализ временных рядов с помощью R, Мастицкий С. Э.

Из моделей: bsts, prophet, выделение аномалий, DTW:

https://ranalytics.github.io/tsa-with-r/


Блог Мастицкого:

https://r-analytics.blogspot.com/search/label/%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D1%85%20%D1%80%D1%8F%D0%B4%D0%BE%D0%B2

https://r-analytics.blogspot.com/search/label/Prophet


* Karpov Courses, prophet:

https://www.youtube.com/watch?v=JQXCHE0H46U


это про графики, но оч круто!
https://github.com/rstudio-conf-2020/dataviz


tensorflow probability sts
https://juanitorduz.github.io/intro_sts_tfp/


python:

https://medium.com/tensorflow/structural-time-series-modeling-in-tensorflow-probability-344edac24083

Causal Impact

https://github.com/tcassou/causal_impact


https://www.unofficialgoogledatascience.com/2017/07/fitting-bayesian-structural-time-series.html




Variational Inference, Review for statisticians:
https://arxiv.org/pdf/1601.00670.pdf


Куча ноутбуков по рядам:

https://github.com/ChadFulton/tsa-notebooks



Мёртвый пакет по структурным моделям:
https://github.com/kyleclo/structural



https://towardsdatascience.com/time-series-forecasting-with-statistical-models-in-python-code-da457a46d68a


http://multithreaded.stitchfix.com/blog/2016/04/21/forget-arima/


https://towardsdatascience.com/structural-time-series-forecasting-with-tensorflow-probability-iron-ore-mine-production-897d2334c72b


http://num.pyro.ai/en/latest/tutorials/time_series_forecasting.html
https://cran.r-project.org/web/packages/Rlgt/index.html


https://medium.com/@zhuofanecon/forecast-nonlinear-linear-time-series-in-numpyro-bsgt-example-2c3a0ea7afd2


http://www.stats.uwo.ca/faculty/aim/tsar/tsar.pdf


https://cran.r-project.org/web/packages/dlm/index.html

http://rsta.royalsocietypublishing.org/content/371/1984/20110550.short

https://www.quora.com/How-can-I-learn-Bayesian-time-series-analysis



https://github.com/uber/orbit



https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/lecture-notes/


https://cran.r-project.org/web/packages/forecastML/vignettes/package_overview.html

https://business-science.github.io/modeltime/


https://github.com/awslabs/gluon-ts/


RNN прогнозирование получасового спроса на электричество в R:
https://blogs.rstudio.com/ai/index.html#category:Time_Series



https://github.com/asael697/bayesforecast

https://github.com/asael697/varstan


https://github.com/business-science/modeltime.gluonts


данные с большим количеством нулей: intermittent demand with zeroes
https://stats.stackexchange.com/questions/373689

тест Диболда-Мариано
http://www.phdeconomics.sssup.it/documents/Lesson19.pdf


новый пакет для обработки дат
https://cran.r-project.org/web/packages/clock/vignettes/clock.html

* Посмотреть как реализована сдача домашек через stepik на
"Python для извлечения и обработки данных"
"R для лингвистов: программирование и анализ данных"