# Instashell v1.5.3
## Создатель: github.com/thelinuxchoice
## Переводчик [RU]: github.com/XIshArkIX [готово]

Instashell - это скрипт для выполнения атаки брут форс (Brute Force) для Instagram. Этот скрипт может обойти ограничение на неправильные пароли, поэтому он может тестировать бесконенчое количество паролей.

![instashell](https://user-images.githubusercontent.com/34893261/37567580-c98d3a58-2aa7-11e8-9022-a5bc86326302.png)

### Перед использованием:
```bash
git clone https://github.com/XIshArkIX/instashell
cd instashell
chmod +x install.sh
sudo ./install.sh
```

### Использование:
```bash
chmod +x instashell.sh
sudo ./instashell.sh
```

#### Особенности:
* Сохранение/продолжение сессий
* Анонимная атака с использованием сети TOR
* Многопоточность (400 паролей в минуту, 20 потоков)
* Проверка на существование аккаунта
* Словарь в комлекте
* Авто установка зависимостей

### Как это работает?

Скрипт использует Android ApkSignature(цифровая подпись Android) для выполнения аутентификации, дополнительно используя сеть TOR, чтобы сменить IP адрес после блокировки и продолжить атаку.
