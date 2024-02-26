# Переводчик экрана

Для того, чтобы пользоваться этой программой необходимо сделать следующие действия

1. Зависимости:

## Linux

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Windows

```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```

2. Tesseract
   Ставится на разных ОС по разному, поэтому просто оставлю ссылку:
   https://github.com/tesseract-ocr/tesseract

3. Желательно запустить один раз сервер для переводчика (обязательно из виртуального окружения):
`libretranslate`