# Домашнее задание по подключению готовой модели для определения наличия маски на лице.


## Описание:
Модель принимает файл с изображением лица человека и выдает ответ надета ли на нем маска.


## Инструкция по установке и использованию:
1. В [Ultralytics](https://docs.ultralytics.com) не все библиотеки работают на Python 3.12, поэтому лучше работать на весрии 3.11.
2. Установить библиотеки (pip install ultralytics, pip install roboflow).
3. На сайте [Roboflow](https://roboflow.com) выбрать датасет и подключить ее к модели(там есть инструкция, нужно копировать и вставить в код)
4. Далее нужно указать файл для анализа и файл куда модель сохранит результат. Я все это оформил методом, куда ввожу эти данные.


Дополнение:
1. Я выбрал модель [YOLOv8](https://github.com/ultralytics/ultralytics).
2. Выбранный [Датасет](https://universe.roboflow.com/yolo-1ulj8/masks-detection-kwy1r)
3. Выполнено версионирование(pip freeze > requirements.txt)


## Пример картинки и результата.
![no_mask2](https://github.com/grafgad/mask-detection2/assets/78178266/8f010318-791d-46de-86b1-133999d060e4) 
![prediction_no_mask](https://github.com/grafgad/mask-detection2/assets/78178266/a31004dd-ba6b-48f8-9448-532c621ff8da)
