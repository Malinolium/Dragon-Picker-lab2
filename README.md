# Лабораторная работа 2 [in GameDev]
Отчет по лабораторной работе #2 выполнил(а):
- Гулиева Эльвира Аразовна
- 1935822
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
ознакомиться с основными функциями Unity и взаимодействием с объектами внутри редактора.

## Задание 1
### Пошагово выполнить каждый пункт раздела "ход работы" с описанием и примерами реализации задач
Ход работы:
Задание 1
В разделе «ход работы» пошагово выполнить каждый пункт с описанием и
примера реализации задач по теме видео «Практическая работа 1-4».
Ход работы (задание 1).
1) Создать новый проект из шаблона 3D – Core;
2) Проверить, что настроена интеграция редактора Unity и Visual Studio Code
(пункты 8-10 введения);
3) Создать объект Plane;
4) Создать объект Cube;
5) Создать объект Sphere;
6) Установить компонент Sphere Collider для объекта Sphere;
7) Настроить Sphere Collider в роли триггера;
8) Объект куб перекрасить в красный цвет;
9) Добавить кубу симуляцию физики, при это куб не должен проваливаться
под Plane;
10) Написать скрипт, который будет выводить в консоль сообщение о том,
что объект Sphere столкнулся с объектом Cube;
11) При столкновении Cube должен менять свой цвет на зелёный, а при
завершении столкновения обратно на красный.


![2022-09-28_17-40-48_Trim (1) (1)](https://user-images.githubusercontent.com/57430501/192826989-e7f74abd-d229-4aa8-9982-3dbe70c72c70.gif)



## Задание 2
### Продемонстрируйте на сцене в Unity следующее:

- Что произойдёт с координатами объекта, если он перестанет быть
дочерним?
- Создайте три различных примера работы компонента RigidBody?


```
```
- Если есть связка родительского объекта с дочерним, то при перемещении родительского объекта меняются его координаты, координаты дочернего объекта не меняются, хотя перемещаются оба объекта. Если удалить связку, координаты дочернего объекта складываются с координатами родительского.
![2022-09-28_19-07-17_Trim (1) (1)](https://user-images.githubusercontent.com/57430501/192833620-98fdc1aa-fb75-473a-b786-4b061a3db375.gif)

- Здесь показано три объекта с тремя разными примерами работы: шар с включенным параметром "Use Gravity", куб с отключенными параметрами и цилиндр с включенным параметром "Is kinematic"
![2022-09-28_19-31-41_Trim](https://user-images.githubusercontent.com/57430501/192837177-682b329b-8a67-4a64-a6db-b1eb7535e324.gif)

## Задание 3
### Реализуйте на сцене генерацию n кубиков. Число n вводится пользователем после старта сцены.
![image](https://user-images.githubusercontent.com/57430501/192858781-243d3e32-f2b6-4f0c-b6c2-c31f73ad8b8d.png)



```
```

## Выводы
- Абзац умных слов о том, что было сделано и что было узнано.
С нуля. Первый раз в жизни щупаю юнити, сквозь кровь, пот и боль задания готовы.
Ненавижу юнити

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
