# Как запустить проект

## Требования

- Python 3.10+
- Jupyter Notebook или JupyterLab

## Установка

1. Склонируйте репозиторий:

   ```bash
   git clone <ссылка-на-репозиторий>
   cd <папка-репозитория>
   ```

2. Создайте и активируйте виртуальное окружение:

   ```bash
   python -m venv venv
   source venv/bin/activate      # Linux/macOS
   venv\Scripts\activate         # Windows
   ```

3. Установите зависимости:

   ```bash
   pip install -r requirements.txt
   ```

## Данные

Файл `Marketing_AB.csv` должен лежать в корне репозитория (или в той папке, откуда его читает ноутбук). Датасет доступен на Kaggle: [Marketing A/B Testing](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing).

## Запуск

1. Запустите Jupyter:

   ```bash
   jupyter notebook
   ```

2. Откройте `AB_Test_pet.ipynb` и выполните ячейки по порядку (Kernel → Restart & Run All).

## Примечания

- Все расчёты (z-тест, доверительные интервалы) выполняются быстро — тяжёлых вычислений в ноутбуке нет.
- График `conversion_by_frequency.png`, на который ссылается README, сохранён в `assets/`; при повторном запуске ноутбука он не перезаписывается автоматически.
