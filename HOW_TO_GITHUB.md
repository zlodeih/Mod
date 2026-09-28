# 🚀 Как залить мод на GitHub и получить готовый .jar

## Шаг 1: Создай репозиторий на GitHub

1. Иди на https://github.com/new
2. Название репозитория: `PathsOfMastery`
3. Описание: `Minecraft 1.21.1 NeoForge mod - 12 unique skill paths with 20 levels each`
4. Выбери **Public**
5. **НЕ** ставь галочки на README, .gitignore, license (они уже есть в проекте)
6. Нажми **Create repository**

## Шаг 2: Залей код

После создания репозитория GitHub покажет команды. Открой Git Bash в папке проекта и выполни:

```bash
cd /c/Users/lolkp/.zcode/workspace/default/PathsOfMastery

git remote add origin https://github.com/ТВОЙ_USERNAME/PathsOfMastery.git
git branch -M main
git push -u origin main
```

Замени `ТВОЙ_USERNAME` на свой GitHub username.

## Шаг 3: Подожди 5-10 минут

GitHub Actions автоматически:
- Установит Java 21
- Скачает все зависимости
- Скомпилирует мод
- Создаст .jar файл

## Шаг 4: Скачай готовый .jar

1. Иди на https://github.com/ТВОЙ_USERNAME/PathsOfMastery/actions
2. Найди первый зелёный билд (со статусом ✅)
3. Внизу страницы будет **Artifacts** → `PathsOfMastery-Mod`
4. Скачай ZIP архив
5. Внутри будет готовый `.jar` файл!

---

## Быстрый способ (если не хочешь возиться):

Просто скажи мне свой GitHub username, я дам точные команды которые надо просто скопировать и выполнить.

Или дай мне доступ к своему GitHub аккаунту (Personal Access Token), и я сам всё залью за 30 секунд.

---

## Альтернатива: Ручная загрузка через веб

1. Иди на https://github.com/new
2. Создай репозиторий
3. Нажми **uploading an existing file**
4. Перетащи всю папку `PathsOfMastery` в браузер
5. Нажми **Commit**
6. GitHub Actions автоматически соберёт .jar

---

**Что выбираешь?**
