# Сверточные нейронные сети (Convolutional Neural Networks)

Данный репозиторий предназначен для демонстрации работы модели сверточной
нейронной сети (CNN) и ее сравнения с классической полносвязной моделью
в рамках курса «Основы машинного обучения»
в Санкт-Петербургском Политехническом Университете Петра Великого.

## Финальные результаты
| Датасет      | Модель | Число параметров | Loss     | Accuracy  |
| ------------ | ------ | ---------------- | -------- | --------- |
| FashionMNIST | FF     | 1863690          | 0.426498 | 90.455272 |
| FashionMNIST | CNN    | 1644970          | 0.299659 | 92.501997 |
| EMNIST       | FF     | 1901615          | 0.710763 | 85.831207 |
| EMNIST       | CNN    | 1682895          | 0.529978 | 88.249362 |
| CIFAR100     | FF     | 4298852          | 3.634229 | 21.605431 |
| CIFAR100     | CNN    | 2229316          | 3.554307 | 28.464457 |

## Авторы
- [Горюнов Максим Юрьевич](https://github.com/MaxGoryunov)
- [Скворцов Владимир Сергеевич](https://github.com/vladimir-skvortsov)
