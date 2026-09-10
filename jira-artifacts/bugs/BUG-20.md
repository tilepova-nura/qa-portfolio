# BUG-20: Избыточный текст в описании товара

**Шаги для воспроизведения:**
1. Открыть сайт Swag Labs
2. Авторизоваться под любым пользователем
3. На главной странице найти товар "Sauce Labs Backpack"
4. Обратить внимание на описание товара

**Фактический результат:**
Описание товара: "carry.allTheThings() with the sleek, streamlined Sly Pack that melds uncompromising style with unequaled laptop and tablet protection."

В описании присутствует бессмысленный текст "carry.allTheThings()", который похож на вызов функции и не является частью описания продукта.

**Ожидаемый результат:**
Описание должно быть чистым, без лишнего кода: "The sleek, streamlined Sly Pack that melds uncompromising style with unequaled laptop and tablet protection."

**Серьёзность:** Trivial
**Приоритет:** Low
**Окружение:** Все браузеры

**Скриншот:** [BUG-20_screenshot.png](../screenshots/BUG-20_screenshot.png)

**Связанные задачи:** [IMP-26](../improvements/IMP-26.md), [Чек-лист №3](../checklists/checklist-03-products.md) (проверка 2.7)
