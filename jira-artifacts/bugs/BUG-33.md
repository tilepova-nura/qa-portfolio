# BUG-33: Ошибка при сортировке для error_user

**Шаги для воспроизведения:**
1. Авторизоваться под пользователем error_user / secret_sauce
2. На главной странице выбрать любой фильтр сортировки (Name A to Z, Name Z to A, Price low to high, Price high to low)

**Фактический результат:**
Появляется всплывающее окно с сообщением: "Sorting is broken! This error has been reported to Backtrace." Сортировка не работает.

**Ожидаемый результат:**
Товары должны сортироваться в соответствии с выбранным фильтром. Ошибка не должна появляться.

**Серьёзность:** Critical
**Приоритет:** High
**Окружение:** Все браузеры, пользователь error_user

**Видео:** [BUG-33_video.mp4](../screenshots/BUG-33_video.mp4)

**Связанные задачи:** [TC-08](../test-cases/TC-08.md), [Чек-лист №2](../checklists/checklist-02-auth-ui.md) (проверка 1.14)
