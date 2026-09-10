# BUG-01: Долгая загрузка для performance_glitch_user

**Шаги для воспроизведения:**
1. Открыть Swag Labs
2. Ввести Username: `performance_glitch_user`
3. Ввести Password: `secret_sauce`
4. Нажать "Login"
5. Засечь время до загрузки главной страницы

**Фактический результат:**
Загрузка занимает более 10 секунд.

**Ожидаемый результат:**
Страница загружается не более 5 секунд.

**Серьёзность:** Major
**Приоритет:** High
**Окружение:** Google Chrome v120, Windows 11

**Видео:** [BUG-01_video.mp4](../screenshots/BUG-01_video.mp4)

**Связанные задачи:** [TC-07](../test-cases/TC-07.md), [Чек-лист №2](../checklists/checklist-02-auth-ui.md) (проверка 1.3)
