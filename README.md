# Инструкция по запуску

Приложение тестировалось на Python 3.8, но должно работать и на новых версиях.
Требуется версия Python с установленной библиотекой Tkinter.
На Windows Tkinter поставляется с обычной установкой.
На Linux и macOS может потребоваться дополнительная установка.

Перед запуском рекомендуется создать виртуальное окружение:
```
python -m venv .env
.env\Scripts\activate - на Windows.
source .env/bin/activate - на Linux/macOS.
```
После активации виртуальной среды должна появиться подпись (.env) слева в командной строке.

Необходима установка дополнительных библиотек с помощью `pip install -r requirements.txt`
Далее приложение запускается с помощью команды `python main.py`.
