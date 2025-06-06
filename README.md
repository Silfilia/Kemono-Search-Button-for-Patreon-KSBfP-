# Кнопка поиска на Kemono для Patreon

[![ru](https://img.shields.io/badge/%D1%8F%D0%B7%D1%8B%D0%BA-%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9%20%F0%9F%87%B7%F0%9F%87%BA-white)](README.md)
[![en](https://img.shields.io/badge/lang-English%20%F0%9F%87%AC%F0%9F%87%A7-white)](README-EN.md)

> [!WARNING]
> Все права на оригинальное программное обеспечение принадлежат их соответствующим правообладателям. Скрипт не связан с оригинальными правообладателями.

Этот скрипт добавляет кнопку поиска на страницы авторов на Patreon, которая ведет на страницу автора на **Kemono**.

## Установка скрипта:

1. Установите **[Tampermonkey](https://www.tampermonkey.net/)** (или другой менеджер пользовательских скриптов на ваш выбор) | (Альтернатива для Safari: **[UserScripts](https://apps.apple.com/app/userscripts/id1463298887)**).
2. **[«Установите Скрипт»](https://github.com/Silfilia/Kemono-Search-Button-for-Patreon-KSBfP-/raw/refs/heads/main/KSBfP.user.js)**

## Функции:

- Добавляет **кнопку поиска на Kemono** на страницы авторов Patreon.
- Кнопка ведет на страницу автора на **Kemono**.
- Работает, извлекая имя автора с страницы и генерируя соответствующий URL для поиска.

## Полезные ссылки:

1. **Репозиторий скрипта:** [Ссылка](https://github.com/Silfilia/Kemono-Search-Button-for-Patreon-KSBfP-)

## Как настроить стиль кнопки:

Вы можете настроить внешний вид кнопки, используя собственный CSS.

```css
#kemono-search-button {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(8px);
  color: #000;
  font-weight: bold;
  border-radius: 10px;
}
