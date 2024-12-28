// Проверка версий.
python3 --version       
python3.10 --version
// если не 3.10 то
// Версия Python должна быть 3.10
brew install python@3.10

// если нет env папки для старта проэкта
// Активация env переменной
python3.10 -m venv env
source env/bin/activate
// Установка django на проэкт
pip install django
// Установка tensorflow
pip install tensorflow
// Распознание лиц
pip install opencv-python
// Обязательно в любом случае
// если нет папки медиа создание папки
mkdir media
// дать право доступа к ней
chmod 755 media
// Создание модели
python3 save_model.py
// Запуск всего проэкта
python3 manage.py runserver