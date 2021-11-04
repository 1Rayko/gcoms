# Gcoms - простая утилита для github

## Установка Python И Git

### Arch 
```bash
sudo pacman -Sy python git  --noconfirm
```
### Debian, Ubuntu
```bash
sudo apt insttall python git -y
```
### Termux 
```bash
pkg install python git
```
---
## Клонирование утилиты себе на устройство
```bash
git clone git@github.com:kotik06/gcoms.git
```
---
## Установка утилиты
### Переход в директорию 
```bash
cd gcoms
```
### Установка скрипта в /usr/local/bin
```bash
chmod +x main && sudo cp main /usr/local/bin/gcoms
```
---
## Использование и запуск

1. Создайте свой репозиторий
2. Перейдите в его директорию
3. Запустите утилиту и укажите количество коммитов
```bash
gcoms
```
---
## Скриншоты 
![Alt text](https://raw.githubusercontent.com/kotik06/gcoms/main/1_1.png)
