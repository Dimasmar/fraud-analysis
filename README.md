# fraud-analysis
This was one of my case projects for Analytics Summer Camp at Genesis Academy

Supply: Професійні автори, які пишуть і публікують свої новели на
платформі. Вони створюють високоякісний контент, що стає доступним для
читачів.
Demand: Люди, які приходять на платформу, щоб читати новели.
Для читачів у нас є два мобільні додатки (iOS та Android) і веб платформа.
Для письменників ми пропонуємо окремий веб-продукт, а також маємо
CRM для внутрішнього використання.

### Монетизація

Модель монетизації побудована на внутрішній валюті — коїнах. Читачі
можуть починати читати новели безкоштовно (зазвичай до 5 глав у кожній
книзі доступні безкоштовно), але для продовження читання їм потрібно
розблоковувати глави за коїни.

Як отримати коїни:

Придбати за реальні гроші
Отримати як бонус (щоденний вхід, читання, перегляд реклами, виконання завдань)
Як витратити коїни:

Розблокування глав новел
Подарунки авторам - це ще один спосіб підтримати улюблених
письменників
Автори отримують винагороду, коли користувачі витрачають коїни на розблокування глав або на подарунки. Коїни конвертуються в реальні гроші для авторів. Чим більше читач витрачає коїнів на книгу, тим більше автор заробляє.

### Завдання

Відомі випадки, коли автори навмисно витрачають бонусні коїни на свої книги, перетворюючи їх на реальні виплати собі. Команда прагне мінімізувати ризики шахрайства на платформі. Потрібно розробити систему для виявлення таких книг. По завершенні завдання необхідно надіслати список фродових книг у форматі CSV. Пояснення логіки вашого рішення може бути представлене у зручному для вас форматі: текстовий документ, презентація, Notion, etc.

### Пояснення значень івентів:

purchase_success - успішна покупка пакету коїнів;
chapter_open - відкриття глави книги (може статися тільки якщо
вона доступна);
click_send_donate - відправка подарунка автору;
click_unlock_now / auto_unlock_chapter - користувач розблокував
главу книги, витративши коїни (може бути тільки один з цих
івентів: auto_unlock_chapter якщо увімкнено авторазблокування,
інакше - click_unlock_now).

### Розв'язок задачі: https://hurricane-syringa-927.notion.site/3-df4671dd09f643c3a8feeacf20e070c8?pvs=74
