## Проект для визуализации данных из различных наборов с использованием библиотек Python, таких как Pandas, Matplotlib и Seaborn.

## 📁 Структура проекта:
```text
project/
├── main.py          # Главный скрипт для запуска программы
├── interface.py     # Консольный интерфейс пользователя
├── logic.py         # Логика визуализации и обработки данных
├── files/           # Папка с исходными данными
│   ├── Cleaned_ships_data.csv
│   ├── IRIS.csv
│   └── Data_Science_Salary_2021_to_2023.csv
└── README.md        # Этот файл
```

## 📊 Наборы данных:
### Проект работает с тремя наборами данных:
- **`Cleaned_ships_data.csv`** - данные о кораблях
- **`IRIS.csv`** - классический набор данных ирисов Фишера
- **`Data_Science_Salary_2021_to_2023.csv`** - данные о зарплатах в Data Science

## 🚀 Функциональность
### Задание 1: Визуализация данных о кораблях и ирисах:
- **`2-D график зависимости средней загрузки от длины`** - линейный график зависимости грузоподъемности от длины корабля
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/695954e4-5b30-47e2-972f-4794d8a7cf6d" />
- **`Распределение кораблей по типам`** - круговая диаграмма типов кораблей
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/994cb612-b6b2-470e-8cf7-1ee5a52e06c2" />
- **`Гистограмма по годам постройки`** - распределение кораблей по годам постройки
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/7e6f8cb3-0c0c-43d8-bdfc-a2c846e22292" />
- **`2D гистограмма: годы постройки vs грузоподъемность`** - двумерная гистограмма
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/735f400c-1d7a-4aab-8f53-810376fbf344" />
- **`Парная диаграмма для ирисов`** - pairplot для анализа взаимосвязей характеристик ирисов
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/62e404a7-407d-4852-9da2-ad67d3b334a5" />
- **`Скрипичные диаграммы для ирисов`** - violin plot для визуализации распределения характеристик по видам ирисов
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/ea93843b-41e3-46ec-a168-70d1b9013cea" />

### Задание 2: Визуализация данных о зарплатах в Data Science:
- **`Распределение зарплат по уровням опыта`** - violin plot зарплат по уровням опыта
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/58fe8e84-bb0d-401b-8c34-846fe89d848d" />
- **`Топ-10 самых высокооплачиваемых должностей`** - горизонтальная столбчатая диаграмма
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/42bae38e-d839-4683-84bf-eced245be3d9" />
- **`Динамика зарплат по годам`** - линейные графики тенденций зарплат по годам
  <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/3ccc6d61-59e0-4384-a4b6-b7cd9e9ebebd" />

  

## 🛠️ Установка и запуск:
### Клонируйте репозиторий:

```bash
git clone https://github.com/Demonrux/APL_lab2
cd project
```
### Установите необходимые зависимости:

```bash
pip install pandas numpy matplotlib seaborn
```
Убедитесь, что файлы данных находятся в папке files/

### Запустите программу:

```bash
python main.py
```
## 🎮 Использование
### После запуска программы появится консольное меню с номерами от 1 до 10. Выберите нужный вариант для отображения соответствующей визуализации:
- **`Опции 1-6`**: Визуализации для данных о кораблях и ирисах
- **`Опции 7-9`**: Визуализации для данных о зарплатах
- **`Опция 10`**: Выход из программы

## 📋 Требования
- Python 3.6+
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📝 Примечание
Убедитесь, что все CSV-файлы находятся в правильной директории (files/) перед запуском программы.

