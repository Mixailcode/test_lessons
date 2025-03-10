# Календар-планувальник для учнів

## Опис проекту
Календар-планувальник для учнів, який дозволяє вчителям створювати події та планувати заходи. Можливі типи подій:
- Екзамен
- Контрольна робота
- Шкільні заходи
- Батьківські збори
- Особисті події

---

## Функціональні можливості

### 1. Авторизація/Реєстрація
- Логін через email та пароль.
- Ролі користувачів: `teacher`, `student`, `parents`.
- Викладачі можуть створювати інших користувачів (учнів, батьків, інших викладачів).

### 2. Головна сторінка
- Календар подій з режимами перегляду:
  - Місячний
  - Денний
  - Тижневий
  - Річний
- Перегляд календарів інших користувачів (без деталей подій).
- Перевірка на конфлікти подій за часом.
- Позначення подій, що перетинаються.
- Відображення списку завдань на сьогодні зі статусами (`Виконано`/`Не виконано`).

### 3. Події (Events)
- Перегляд списку подій з фільтрацією:
  - Минулі/майбутні
  - Прийняті/відмовлені
- Пошук подій за назвою або датою.
- Деталі події:
  - Назва
  - Дата
  - Тривалість
  - Контент (прихований до часу події)
  - Місце/посилання (для онлайн-подій)
  - Учасники
  - Завдання (опціонально)
- Відповідь на запрошення (`відвідаю`/`не відвідаю`) та коментування подій.
- Створення подій:
  - **Викладачі**: екзамени, контрольні, шкільні заходи, батьківські збори тощо.
  - **Учні**: особисті події або запрошення інших учнів (без запрошення вчителів/батьків).
  - **Батьки**: лише перегляд доступних подій.

### 4. Завдання (Tasks)
- Перегляд списку завдань з фільтрацією та пошуком.
- Завдання можуть бути прив’язані до подій або незалежні.
- Користувачі можуть позначати завдання як виконані (інформація доступна лише для них).
- Сортування завдань за датою.

### 5. Профайл користувача
- Пошук користувачів за іменем або email.
- Перегляд та редагування профайлу:
  - Ім’я
  - День народження
  - Додаткова інформація
  - Фотографія профілю
- Викладачі можуть редагувати профілі інших користувачів.

---

## Додатковий функціонал (необов’язковий)

### 6. Статистика користувачів
- Загальна кількість запланованих завдань та виконаних із них.
- Кількість відвіданих подій.
- Найчастіші учасники зустрічей.
- Додаткові метрики активності.

### 7. Прикріплення файлів/посилань до подій
- Можливість додавати файли або посилання до подій.

### 8. Оновлення в реальному часі
- Сповіщення про нові події, якщо користувач знаходиться на сайті.

### 9. Синхронізація з іншими календарями
- Підтримка синхронізації з Google Calendar або іншими популярними календарями.

---

## Примітка
Елементи, позначені **, є додатковими та реалізуються після завершення основного функціоналу.
