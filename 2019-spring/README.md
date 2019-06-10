# Материалы курса "Глубинное обучение", прочитанного на [ФКН ВШЭ](https://cs.hse.ru/) весной 2019г.

## Преподаватели
Лектор: [Антон Осокин ](https://aosokin.github.io/)

Семинаристы: Артем Бабенко, [Алексей Умнов](https://www.hse.ru/org/persons/141880775)

## Программа курса
* Введение ([лекция 1](lectures/DL19_lecture1_intro.pdf), [семинар 1](seminars/seminar1/DL19_seminar1.ipynb))
* Основные концепции
  - Механика нейросетей и backprop ([лекция 2](lectures/DL19_lecture2_backprop.pdf), [семинар 2](seminars/seminar2/DL19_seminar2.ipynb))
  - Виды архитектур ([лекция 3](lectures/DL19_lecture3_models.pdf), [семинар 3](seminars/seminar3/DL19_seminar3.ipynb))
  - Обучение и регуляризация ([лекция 4](lectures/DL19_lecture4_training.pdf), [семинар 4](seminars/seminar4/DL19_seminar4.ipynb))
* Продвинутые темы
  - Применения в компьютерном зрении ([лекция 5](lectures/DL19_lecture5_deepvision.pdf), [семинар 5](seminars/seminar5/DL19_seminar5.ipynb))
  - Применения для обработки языка ([лекция 6](lectures/DL19_lecture6_deepnlp.pdf), [семинар 6](seminars/seminar6/DL19_seminar6.ipynb))
  - Adversarial X ([лекция 7](lectures/DL19_lecture7_adversarialX.pdf), [семинар 7](seminars/seminar7/DL19_seminar7.ipynb))
  - Вероятностные модели ([лекция 8](lectures/DL19_lecture8_probmodels.pdf), [семинар 8](seminars/seminar8/DL19_seminar8.ipynb))
  - Дифференцируемое программирование ([лекция 9](lectures/DL19_lecture9_differentiableprogramming.pdf), [семинар 9](seminars/seminar9/DL19_seminar9.ipynb))
* Приглашенный доклад: Борис Янгель о нейросетях в автопилоте Яндекса 

## Disclaimer
Курс "Глубинное обучение" разрабатывался не как онлайн-курс, а как классический университетский курс с лекциями и семинарами.
Видео-запись осуществлялась только для внутреннего использования (Кристина, спасибо большое!).

Тем не менее, мы решили выложить все материалы в открытый доступ под [лицензией Apache 2.0](../LICENSE) на случай если они кому-то будут полезны.
Единственная просьба, **пожалуйста, не выкладывайте решения семинаров в открытый доступ!** 
  
## Материалы
Все материалы курса на **русском** языке!

Выложены следующие материалы:
* [Презентации лекций](lectures)
* [Jupyter ноутбуки семинаров](seminars) 

**Пожалуйста, не выкладывайте решения семинаров в открытый доступ!** Мы хотим переиспользовать материалы на следующих итерациях курса.

**Минутка рекламы:** на [ФКН](https://cs.hse.ru/) мы каждый год набираем студентов-магистров-аспирантов в нашу научную группу [Байесовских методов и глубинного обучения](https://bayesgroup.ru/admission/) — приходите к нам учиться и работать! Очно мы всегда стараемся дать больше, чем просто контент :-) 
 
## Технические требования семинаров
Все семинары разрабатывались для выполнения на обычных ноутбуках, т.е., не требуют значительных вычислительных ресурсов (в частности не требуют GPU). Тем не менее требования к железу ненулевые, и на некоторых компьютерах все работает очень медленно. Бесплатные вычислительные ресурсы (в том числе с GPU) можно получить, например, на сайте https://colab.research.google.com.

В рамках курса мы использовали python 3.6, [pytorch v1.0.1](https://github.com/pytorch/pytorch/releases/tag/v1.0.1), [torchvision v0.2.2](https://github.com/pytorch/vision/releases/tag/v0.2.2). Поддержка других библиотек и других версий python и pytorch не осуществлялась.
 
Для настройки библиотек мы рекомендуем использовать менеджер пакетов [Anaconda](https://www.anaconda.com/) (есть для Linux, OS X, Windows). Для установки в Linux, OS X и Windows смотрите инструкции на сайте http://pytorch.org/. 
 