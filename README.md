# Скрипт для закачки и настройки библиотек для KiCad

## Описание

устанавливает стандартные библиотеки KiCad и пользовательские библиотеки, прописывает пути к библиотекам и переменным

## Установка
установите git, tee и wget

apt install git wget tee

закройте программу KiCad

для установки создайте папку для библиотек

в консоли выполните:

wget https://raw.githubusercontent.com/immortalserg/kicad_download_lib/master/download_kicad_lib

chmod +x download_kicad_lib

./download_kicad_lib

дождитесь окончания работы скрипта

## Библиотеки

- официальные KiCAD
- AB2 Tech
- DiGiKey
- Sparkfun
- Библиотеки УГО по ГОСТ
- Simisto 
- Elessar Cuthalion
- Contextual Electronics
- Anton Donets
- Алексис Локвуд
- Club Vaudois de Robotique Autonome
- Benoit Frigon
- MySensors
- realthunder

## Версии

### 0.1.4 от
- добавлены библиотеки MySensors
- добавлены библиотеки realthunder
- исправлены пути к библиотекам
- добавлен путь в конфиг

### 0.1.3 от 15.08.2019

- добавлены библиотеки Benoit Frigon
- исправлены пути в конфиг. файлах

### 0.1.2 от 10.08.2019

- добавлены библиотеки Алексис Локвуд, симлинки на 3d модели Simisto которые используются в библиотеках Алексис Локвуд
- либы от Club Vaudois de Robotique Autonome (CVRA), работают не все 3d модели ибо линки на переменную проекта

### 0.1.1 от 08.08.2019

- добавлены библиотеки Anton Donets 
- добавлено в имя файлов бэкапа конфигов дата и время создания бэкапа
- добавлен путь к DipTrace установелнный в wine (для использования 3d моделей из DipTrace)

### 0.1 
