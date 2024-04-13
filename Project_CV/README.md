# Определение возраста покупателей
[.ipynb](https://github.com/79nin/Data_Science_YP/blob/main/Project_CV/Project_CV.ipynb)
## Описание проекта
Требуется построить модель, которая по фотографии определит приблизительный возраст человека.

## Навыки и инструменты
- python
- pandas
- numpy
- matplotlib.pyplot
- PIL.Image
- tensorflow.keras.preprocessing.image.ImageDataGenerator
- tensorflow.keras.applications.resnet.ResNet50
- tensorflow.keras.layers.GlobalAveragePooling2D
- tensorflow.keras.layers.Dense
- tensorflow.keras.models.Sequential
- tensorflow.keras.optimizers.Adam
## Общий вывод
Обученная модель базируется на нейройнной сети ResNet50. Данная модель предсказывает возраст покупателя с точностью +- 7 лет, с ее помощью можно анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы, а также контролировать добросовестность кассиров при продаже алкоголя.
