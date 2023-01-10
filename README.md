# Шаблон для анализа данных
------------

### Описание
------------
Базовый шаблон для проведения анализа данных на проекте

### Скачивание шаблона

```
git clone git@github.com:ArtemBonda/project_template_DA.git
```


### Структура каталогов проекта
------------  

```
├── data               <- Данные из других источников 
├── notebooks          <- Jupyter notebooks. 
├── src                <- Вспомогательный код для использования в проекте
|   ├── __init__.py    <- Использование пакета src модулем Python
├── README.md  
├── requirements.txt   <- Файл с зависимостями для окружения Python.
|                      Генерация с помощью `pip freeze > requirements.txt`
```


### Установка окружения и загрузка зависимостей
------------
- **Правило:** для каждого нового проекта создавать новое окружение зависимостей модулей Python для проведения анализа данных

**Pipenv** установит библиотеку и автоматически создаст *Pipfile* в каталоге проекта
```bash
pipenv install pandas
```
- переход в окружение
```shell
pipenv shell
```

- установка всех зависимостей из файла
```bash
pip install -r requirements.txt
```

- просмотр всех установленных пакетов
```bash
pip freeze
```
- удалить путь к окружению из *virtualenvs* при завершении проекта
```
pipenv --rm
```

## Полезные ссылки:
------------
- [pipenv](https://pipenv-fork.readthedocs.io/en/latest/install.html#installing-pipenv)
- [virtualenv](https://virtualenv.pypa.io/en/latest/)
- [Утилита для установки шаблонов по анализу данных](https://github.com/drivendata/cookiecutter-data-science)
