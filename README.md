# BrainSystem
Проект по созданию самодельной брейн-системы для интеллекуальных игр

## Возможности системы
- до 4 игроков
- режимы с фальстартами и без фальстартов
- отсчет времени для Своей игры и Брейн-ринга
- режимы со звуком и без

## Использование
- управление через три кнопки: запуск, сброс и служебная кнопка
- включение/выключение звука - короткое нажатие на служебную кнопку
- переключение режима - длинное нажатие на служеюную кнопку, номер режима отображается в двоичном виде с помощью светодиодов

## Режимы
1) Без фальстартов, без отсчета времени
2) С фальстартами, без отсчета времени
3) Своя игра без фальстартов (отсчет 7 секунд)
4) Своя игра с  фальстартами (отсчет 7 секунд)
5) Брейн-ринг без фальстартов (1 минута + перезапуск на 20 секунд)
6) Брейн-ринг с фальстартами (1 минута + перезапуск на 20 секунд)

## Детали для сборки
- arduino-подобный контроллер (не менее 12 портов, 13 для звука с ШИМ)
- 4 коннектора для проводов
- 7 кнопок
- 4 цветных светодиода
- белые светодиоды для индикации запуска (опционально)
- аккумулятор, плата зарядки, преобразователь напряжения (все опционально, для автономной работы)
- провода (для кнопок желательно экранированные)

## Сторонние зависимости
Для прошивки требуются библиотеки [EncButton](https://github.com/GyverLibs/EncButton) и [TimerMs](https://github.com/GyverLibs/TimerMs)

## Обратная связь
По любым вопросам можете писать [t.me/VGorash](https://t.me/VGorash)
