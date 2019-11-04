# StackOverflow Assistant

<p align="center"> 
<img src="https://jessehouwing.net/content/images/size/w2000/2018/07/stackoverflow-1.png" width="800">
</p>

Telegram-бот для поиска релевантных тем на StackOverflow. Основной функционал:

* отвечает на вопросы, связанные с разработкой, выдавая наиболее релевантные темы на StackOverflow. Обучен на поиск по следующим языкам программирования:
	* C#
	* C++
	* Java
	* JavaScript
	* PHP
	* Python
	* R
	* Ruby
	* Swift
	* Visual Basic
* симулирует режим chit-chat на свободные темы.

## Необходимые библиотеки

* **ChatterBot**;
* **nltk**;
* **numpy**;
* **pandas**;
* **requests**;
* **scikit-learn**.

Установка библиотек:

`$ pip install -r requirements.txt`

## Структура проекта

* **dialogue_manager.py** - класс для создания диалогового менеджера;
* **main_bot.py** - класс, реализующий функциональность бота;
* **utils.py** - вспомогательные утилиты;
* **StackOverflow Assistant.ipynb** - ноутбук для обучения модели классификации интентов и тегов.

## Установка

1. Распаковать обученные embedding'и:

`$ tar xvf word_embeddings.tar.xz`

2. Выполнить ноутбук StackOverflow Assistant.ipynb и сериализовать получившиеся модели

3. В Telegram начать беседу с @BotFather, написав **/newbot**. Указать название и имя пользователя для нового бота и получить токен

4. Запустить бота, указав полученный токен:

`$ python3 main_bot.py --token=YOUR_TOKEN`


## Демонстрация работы

@shkarin_stackoverflow_bot

Бот запущен на виртуальной машине Amazon EC2.