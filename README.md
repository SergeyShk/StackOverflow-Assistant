# StackOverflow Assistant

<p align="center"> 
<img src="https://jessehouwing.net/content/images/size/w2000/2018/07/stackoverflow-1.png" width="800">
</p>

Telegram-бот для поиска релевантных тем на StackOverflow.

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
