# VKINDER

## Чат-бот для знакомств в социальной сети VK

### Описание

Бот использует данные из VK и ищет людей, подходящих под следующие условия:

- Возраст,
- пол,
- город,
- семейное положение.
 
У тех людей, которые подошли по требованиям пользователю, получать топ-3 популярных фотографии профиля и отправлять их пользователю в чат вместе с ссылкой на найденного человека.

### Стек технологий

![Static Badge](https://img.shields.io/badge/python-%25?style=for-the-badge&logo=python&labelColor=FFC436&color=blue) ![Static Badge](https://img.shields.io/badge/rest_api-%25?style=for-the-badge&logo=rest_api&labelColor=9BABB8&color=9BABB8) ![Static Badge](https://img.shields.io/badge/postgresql-%25?style=for-the-badge&logo=postgresql&labelColor=F5F5F5&color=F5F5F5)

### Инструкция перед запуском

1.Установить виртуальное окружение команда ```python -m venv venv``` \
2.Установить requirements.txt команда ```pip install -r requirements.txt``` \
2.Запустить программу (файл ```interface.py```) ```python interface.py```<br>

### Основной сценарий

Чтобы начать работу с ботом, нужно ввести слово "Привет". Бот запросит ваш пол, город и возраст. На основе полученных данных бот выберет пару и выдаст 3 самых популярных фотографии со страницы пользователя. Популярность определяется количеством лайков и комментариев.