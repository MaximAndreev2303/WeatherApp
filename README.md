# WEATHER APPLICATION

![](static/icon/big%20screen.png)

Цей проект розроблено з метою ознайомлення із роботою API, принципом отримання даних від віддаленого серверу, вмінням їх обробляти, структурувати та застосовувати у своємо проєкті. А саме застосовувалось API такого веб-ресурсу як [OpenWeatherMap](https://openweathermap.org). Проєкт допоможе розібратися із роботою файлів JSON, як правильно отримувати та зберігати дані у файлах з типом .json. Та познайомити користувача з інтерфейсом застосунку розробленим за допомогою пакету [CustomTkinter](https://customtkinter.tomschimansky.com)

### Зміст:
- [Основні модулі проєкту](#modules)
- [Розгортання проєкту](#download)
- [Створення віртуального оточення проєкту](#venv)
- [Завантаження модулей до віртуального оточення](#download-venv)
- [Старт проєкту](#start-project)
- [Основні механіки проєкту](#mechanics)
- [Висновок по проєкту](#result)

### Modules:
Всі модулі
1. [customtkinter](https://customtkinter.tomschimansky.com)
2. [json](https://docs.python.org/3/library/json.html)
3. [colorama](https://pypi.org/project/colorama/)
4. [os](https://docs.python.org/uk/3.13/library/os.html)
5. [requests](https://pypi.org/project/requests/)
6. [pillow](https://pypi.org/project/pillow/)
7. [datetime](https://docs.python.org/3/library/datetime.html)


### Download:
Завантаження проєкту
- ##### Git clone:

    - Отримати посилання для клонування проєкту

    ![](static/icon/clone_link.png)

    - Відкрити VSCode --> у Explorer VSCode відкрити папку для збереження склонованого проєкту --> та у Terminal прописати команду: 
    - `git clone https://github.com/WorldIT-academy/WeatherApp.git`

    ![](static/icon/clone_command.png)

    - Відкрити каталог, який ви склонували у Explorer VSCode
    
- ##### Download ZIP
Ще проєкт можна завантажити в форматі ZIP і розархівувати папку.Після цього переносемо до Explorer VSCod-у.

### Venv:
Створення віртуального оточення і активація

__Для Windows в терміналі:__

- python -m venv (назва вашого оточення)
- source (назва вашого оточення)/Scripts/activate

__Для MacOs в терміналі:__

- python3 -m venv (назва вашого оточення)
- source (назва вашого оточення)/bin/activate


### Download venv:
Завантаження модулів до venv

__Для встановлення модулів для нашого проєкту потрібно:__

1. Через pip(для Windows) чи pip3(для MacOS) встановлюємо потрібні нам модулі в терміналі
    - pip install customtkinter
    - pip install json
    - pip install colorama
    - pip install datetime
    - pip install pillow
    - pip install os
    - pip install requests 
2. Для зручності та слідкування завантажених модулів можно завантажити файл requirements.txt
    - pip freeze > requirements.txt

### Start project:
Cтарт проєкту

1. Запускаємо проєкт через файл main.py
2. Після цього вводимо своє ім'я та місто
3. Дивимось прогноз погоди на сьогодні

### Mechanics:
Основні механіки проєкту

### Result:
Висновок

- У цьому проєкті було реалізовано ознайомлення з основами роботи з API, з використанням веб-ресурсу [OpenWeather](https://openweathermap.org/)
- Був процес отримання даних з віддаленого сервера, їх обробка та структурування в шаблоні проєкту
- Було створенно інтерфейс користувача за допомогою бібліотеки CustomTkinter для зручності користання застосунку
- Проєкт є корисним прикладом практичного застосування API в Python, а також розробки інтерфейсу користувача
