# ResearchMethods

## 1. Первый запуск

### 1.1 Установка окружения
Перед запуском необходимо установить виртуальное окружение, например venv:
```
python -m venv venv
```
После этого необходимо запустить окружение:
```
venv/scipts/activate
```
Может быть ошибка с текстом 
```
... не распознана как команда или командлета...
```
Ее прогуглить, там будет рекомендация, сделать по ней.

После запуска окружения в терминале изменится вид:
До:
```
PS C:\Projects\ResearchMethods>
```
После:
```
(venv) PS C:\Projects\ResearchMethods>
```
Приписка venv означает, что вы включили виртуальное окружение и нет внешних зависимостей проекта.
 
### 1.2 Установка библиотек 
Убедитесь, что находитесь в одной папке с файлом **requirements.txt**
Для этого прописать 
```
ls
```

Для входа в папку использовать 
```
cd <название папки>
```

Для выхода на 1 папку наверх 
```
cd ..
```

В файле **requirements.txt** находится список бибилиотек с их версиями, на которых заработала программа.
Для установки необходимо прописать команду:
```
pip install -r requirements.txt
```

После этого начнется установка всех необходимых библиотек.

### 1.3 Запуск
 
Запуск производится командой 
```
jupyter notebook
```
На localhost запустится приложение и с ним можно работать.
 
 