# Практична робота №2 — Home (варіант 1)

Відкрити `index.html` у Google Chrome. Шрифти Poppins підвантажуються з Google Fonts (потрібен інтернет).

## Додати до наявного репозиторію labs

```bash
git checkout -b pw2
# Скопіювати папку pw2 в корінь репозиторію labs
git add pw2
git commit -m "Practical work 2: Figma Home landing page"
git push -u origin pw2
git checkout main
git merge pw2
git push origin main
```

Якщо основна гілка має назву `master`, замініть `main` на `master`. Команди виконувати в корені `labs`.

Демонстраційні елементи (форма підписки, кнопки) не мають серверної частини. Сторінка повторює композицію наданого скриншота; точність стилів та іконок потребує звірки з шарами Figma.
