# Text Summarizer Backand
##  Гребенщикова Маргарита 8В11

### Описание

> Создание краткой версии (реферата, аннотации) 
текстового документа с помощью алгоритма

> Реализовать API для взаимодействия с алгоритмам

## Техналогии

- [Python](https://www.python.org) - высокоуровневый язык программирования общего назначения
- [Flask](https://pypi.org/project/Flask/) - фреймворк для создания веб-приложений на языке программирования Python
- [Natural Language Toolkit](https://www.nltk.org) - пакет библиотек и программ для символьной и статистической обработки естественного языка

## Установка

Скланировать данный репазиторий

```sh
git clone https://github.com/mag30/Text-Summarizer-Backend.git
```

Подтянуть зависимости

```sh
pip install -r requirements.txt
```

Запустить API

```sh
python app.py
```

### Описание endpoints

>Description:  Summarize  Text
>Tags:         Summarize
>Accept:       json
>Produce:      json
>Param:        language_iso path string true "Language ISO"
>Param: payload json true "User request"
>Success:     200  {object}  ResponseOK "OK"
>Failure:      400  {object}  ResponseFailure "Bad request (client fault)"
>Failure:      500  {object}  ResponseFailure "Internal error (server fault)"
>Router:       /summarize/<string:language_iso> [post]


### Адрес API

>http://localhost:5000/

