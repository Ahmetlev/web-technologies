ИНСТРУКЦИЯ ПО ПРОЕКТУ:

1. Откройте файл index.html в браузере (или через Live Server в VS Code).
2. Экспортируйте группу экранов телефонов из Figma (Group 1 -> Export PNG) и сохраните в папку img/ под именем:
   hero-mockups.png
   (Примечание: в CSS уже задан поворот transform: rotate(12deg); если вы экспортируете группу уже повернутой из Figma, просто удалите строку transform: rotate(12deg); в css/style.css у класса .hero__img).
3. Header закреплен в верхней части экрана (position: fixed).
4. Footer прижат к нижней части страницы через Flexbox (body { display: flex; flex-direction: column; min-height: 100vh; } и .main { flex: 1 0 auto; }).
