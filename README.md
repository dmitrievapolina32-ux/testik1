# Лонгрид — публикация на GitHub Pages

## Шаг 1. Создай аккаунт на GitHub (если ещё нет)
Перейди на [github.com](https://github.com) и зарегистрируйся.

## Шаг 2. Создай новый репозиторий
1. Нажми зелёную кнопку **New** или перейди на [github.com/new](https://github.com/new)
2. Имя репозитория: `longread` (или любое другое)
3. Сделай репозиторий **Public**
4. Оставь остальные настройки по умолчанию и нажми **Create repository**

## Шаг 3. Загрузи файлы
В папке `лонг` должны быть:
- `index.html` — главная страница (откроется по умолчанию)
- `логотип.mp4`, `6565.mp4` — видео
- `Frame 1.png` … `Frame 6.png` — изображения

**Вариант А — через интерфейс GitHub:**
1. В репозитории нажми **Add file** → **Upload files**
2. Перетащи все файлы из папки `лонг` в окно
3. Нажми **Commit changes**

**Вариант Б — через терминал (если установлен Git):**
```bash
cd "/Users/polinadmitrieva/Downloads/лонг"
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ТВОЙ_USERNAME/longread.git
git push -u origin main
```

## Шаг 4. Включи GitHub Pages
1. В репозитории открой **Settings**
2. В меню слева выбери **Pages**
3. В разделе **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: main, папка **/ (root)**
4. Нажми **Save**
5. Подожди 1–2 минуты

## Шаг 5. Ссылка на лонгрид
После публикации лонгрид будет доступен по адресу:
```
https://ТВОЙ_USERNAME.github.io/longread/
```
Например: `https://polinadmitrieva.github.io/longread/`

Эту ссылку можно отправлять другим.
