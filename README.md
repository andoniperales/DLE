# DLE

Diccionario de la Lengua Española (DLE) from Real Academia Española lookup tool on the terminal using Selenium.

## Required modules

```
pip install fake_headers selenium
```

## Other requirements

You'll need the chromedriver binary: https://chromedriver.chromium.org/downloads. On Linux, you can place it in /usr/local/bin, as long as it's in your $PATH.

## Usage

```
python dle.py {term}
```
OR
```
import dle
dle.definicion({word})
```
