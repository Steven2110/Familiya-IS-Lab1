# VidjayaStiven-IS-Lab
Intelligent System laboratory work
Виджая Стивен 932001 2022

## Предметная область: ЭС по выбору автомобиля
## Команда:
Андрюшина Мария 932001

Виджая Стивен 932001

Танумихарджя Рафаэл Мэтью 932001

Цурова Тамара 932001

## Ссылка на наше веб-приложение
https://car-picker-is-lab1.herokuapp.com/
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/80201768/160152216-9704fcab-60c9-4fbd-a38f-c8824139f3bf.png">


## Как использовать наше веб-приложение через локальный порт:
1. Клонируйте репозиторий. / Clone Repository.
2. Откройте консоль / Open terminal
3. Установите библиотеку flask `pip install flask`
4. Установите библиотеку pymongo `pip install pymongo`
5. Запускайте питонский файл `main.py` / Start debugging `main.py` file.
6. Нажмите ctrl (в Windows) / cmd (в Mac) и нажмите ссылку из консоли. / Press ctrl (on Windows) / cmd (on Mac) and click on the link from the console.
7. В вашем браузере вы можете начать использовать наше веб-приложение. / You can start use our web application in your browser.

## Видео нашей программы
Backend Version: **1.0.0**

Video: https://disk.yandex.com/d/B-rylhY4VN4_aw

Frontend Version: **1.0.2**

Video: https://disk.yandex.com/i/YfWNNcAgIFYLJQ

## Тестирование
Пользователь хочет найти варианты автомобилей, со следующим характеристиками:

1. **Цена**: От 3.000.000 До 5.000.000
2. **Стиль**: SUV или Sedan
3. **Тип топлива**: Бензин
4. **Тип передачи**: Механическая или Автоматическая
5. **Бренд**: Mazda или Mercedes-Benz или BMW или Honda или Kia
6. **Цвет**: Чёрная, Красная
7. **Год производства**: Не старше 2015
8. **Размер**: Средняя
9. **Категория**: Экономичная

## Результаты
Наша ЭС возвращает все самые подходящие варианты, а так же другие подходящие варианты соответственно Базе Знаний: 

1. Та же самая цена, стиль, тип топлива, тип передачи, год производства, размер и категория
2. Не принимая во внимание Бренды и Цвета

Все результаты пока находятся внутри папки Car_API и папки Test_Result_File.

Файл *test_best_match.txt* - это результаты всех подходящих вариантов машин

Файл *test_close_match.txt* - это результаты всех других подходящих вариантов машин

## Стек технологий
1. Язык программирования: 
   * Фронтенд/Интерфейс: HTML, CSS
   * Бэкенд/Сервер: Python
2. Базы Данных: MongoDB
3. Веб-фреймворк: Flask
4. Хостинг: Heroku