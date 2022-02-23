# monocular-depth-estimation-with-densenet
## Построение карты глубины по видеопотоку с монокамеры
### Откуда взята идея
  - Датасет - [DIODE: A Dense Indoor and Outdoor DEpth Dataset](https://arxiv.org/pdf/1908.00463.pdf)
  - Алгоритм - [Статья с medium](https://medium.com/mlearning-ai/monocular-depth-estimation-using-u-net-6f149fc34077), [Пример с Keras](https://keras.io/examples/vision/depth_estimation/) и [High Quality Monocular Depth Estimation via Transfer Learning](https://arxiv.org/pdf/1812.11941.pdf)

### [`Структура Модели`](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/model_view.png)
### Сравнительный анализ датасетов

### Результат
## <p align="center">NYU Dataset</p>
**<p align="center">4 epochs / 10% of nyu dataset used</p>**

![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_4_epochs/depth_map_test_01.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_4_epochs/depth_map_test_02.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_4_epochs/depth_map_test_03.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_4_epochs/depth_map_test_04.png)


**<p align="center">6 epochs / 10% of nyu dataset used</p>**

![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_6_epochs/depth_map_test_01_1.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_6_epochs/depth_map_test_02_1.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_6_epochs/depth_map_test_03_1.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_6_epochs/depth_map_test_04_1.png)


**<p align="center">8 epochs / 10% of nyu dataset used</p>**

![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_8_epochs/depth_map_test_01_2.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_8_epochs/depth_map_test_02_2.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_8_epochs/depth_map_test_03_2.png)
![*NYU Dataset Results*](https://github.com/vetasavitskaya/monocular-depth-estimation-with-densenet/blob/main/results/images/nyu_8_epochs/depth_map_test_04_2.png)
### Зависимость от гиперпараметров
