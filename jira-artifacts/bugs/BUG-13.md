# BUG-13: Кнопка "Cancel" на странице Overview возвращает на главную страницу

**Шаги для воспроизведения:**
1. Перейти на страницу Checkout: Step One (https://www.saucedemo.com/checkout-step-one.html)
2. Заполнить все поля (First Name, Last Name, Zip/Postal Code)
3. Нажать "Continue" → переход на страницу Checkout: Overview
4. Нажать кнопку "Cancel"

**Фактический результат:**
Происходит переход на главную страницу (inventory.html). Все данные, введённые на Шаге 1, удаляются.

**Ожидаемый результат:**
При нажатии "Cancel" должен происходить возврат на Шаг 1 (checkout-step-one.html), а введённые данные должны сохраняться.

**Серьёзность:** Major
**Приоритет:** High
**Окружение:** Все браузеры

**Видео:** [BUG-13_video.mp4]([../screenshots/BUG-13_video.mp4](https://app.screencastify.com/watch/8mQSLniZH4aU4NVtr4qH))

**Связанные задачи:** [Чек-лист №10](../checklists/checklist-10-checkout-step2.md) (проверка 3.1)
