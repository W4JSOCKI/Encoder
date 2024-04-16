# Autoenkoder kolorujący obrazy twarzy celebrytów

Ten projekt zawiera autoenkoder, który został wytrenowany na zdjęciach twarzy celebrytów w skali szarości, a następnie używany jest do pokolorowania innych zdjęć twarzy.

## Wyniki

Poniżej znajdują się wyniki pokolorowania trzech różnych typów obrazów:
1. Pokolorowane obrazy ze zbioru uczącego.
   
![Pokolorowane obrazy ze zbioru uczącego](result_images/Images_from_learning_set.png)

2. Pokolorowane obrazy spoza zbioru uczącego.
   
![Pokolorowane obrazy spoza zbioru uczącego](result_images/Images_from_testing_set.png)

3. Pokolorowany obraz o innym rozmiarze niż obrazy ze zbioru uczącego.
   
![Pokolorowany obraz o innym rozmiarze](result_images/Image_with_different_input_size.png)

## Jak używać

Aby uruchomić autoenkoder i pokolorować obrazy twarzy, wykonaj następujące kroki:

1. Sklonuj repozytorium na swój komputer.
2. Zainstaluj wymagane biblioteki i zależności.
3. Uruchom wszystkie komórki w notatniku Autoencoder.ipynb

## Wymagania

Aby uruchomić ten projekt, wymagane są następujące biblioteki:

- numpy
- matplotlib
- Pytorch
- PIL


## Dane treningowe
https://www.kaggle.com/datasets/jessicali9530/celeba-dataset
