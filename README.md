## Тестовое задание на позицию стажёра-фронтендера

### Добро пожаловать на второй этап!
Прежде всего, хочу выразить вам наше искреннее восхишение: вы справились с первым испытанием, и это здорово! На этом этапе перед вами стоит новый вызов — разработка SPA приложения на React. Не стесняйтесь экспериментировать и пробовать новое, ведь именно так рождаются инновации.

**Мы понимаем, что у каждого свой уровень знаний и опыт, и не ожидаем от вас абсолютного совершенства. Главное — не бойтесь ошибаться и принимайте это как часть обучающего процесса. Ваше стремление и готовность учиться ценятся выше, чем безупречный код.**

Самое важное — получайте удовольствие от процесса! Это отличная возможность показать свои навыки, расширить знания и, возможно, открыть себе что-то новое. Мы верим в ваш потенциал и ждем от вас интересных решений.

Желаем вам удачи и пусть этот опыт будет полезным и веселым!

### Продуктовые требования для главной страницы сайта рецептов
**МАКЕТ** https://www.figma.com/file/9bcQdalyTZBI9wWB8a7sVq/%D0%9C%D0%B0%D0%BA%D0%B5%D1%82?type=design&node-id=0%3A1&mode=design&t=2USvwJ82zATXoXPn-1

**API** https://dummyjson.com/docs/recipes

**Исходный код решения должен быть выложен с вашего аккаунта на Github с Readme файлом с инструкцией по запуску.**

#### Представление Рецептов
- Отображается список рецептов, каждый из которых включает:
  - Название блюда
  - Изображение блюда (если доступно)
  - Время приготовления
  - Сложность приготовления (обозначенная звёздами)
  - Кухня/страна происхождения

#### Фильтрация и Сортировка
- Фильтры для рецептов по:
  - Кухне (например, "Все страны и регионы")
  - Типу блюда (завтрак, обед, ужин, закуски, напитки)
  - Сложности приготовления (любая, низкая, средняя, высокая)

#### Взаимодействие с Рецептом
- Переход на страницу с полным описанием рецепта по клику на карточку рецепта.

#### Пагинация
- Реализация пагинации для удобной навигации по рецептам.

#### Прочие Функции
- Кнопка для предложения случайного рецепта, например "Мне повезёт!".

### Страница Рецепта

#### Основная Информация
- **Название блюда**
- **Кухня**: Категория кухни, к которой относится блюдо (например, Европейская).
- **Общее время приготовления**: Указано в минутах (например, 30 минут).

#### Ключевые Характеристики
- **Теги**: Лейблы, такие как "Pizza","Italian", указывающие на категорию блюда.
- **Калорийность**: Предоставление информации о калорийности блюда в ккал и граммах (например, 444 ккал, 100 грамм).
- **Количество порций**: Число порций, на которые рассчитан рецепт (например, 4 порции).

#### Инструкции по Приготовлению
- Шаги приготовления, такие как:
  "Preheat the oven to 475°F (245°C).",
  "Roll out the pizza dough and spread tomato sauce evenly.",
  "Top with slices of fresh mozzarella and fresh basil leaves.",
  "Drizzle with olive oil and season with salt and pepper.",
  "Bake in the preheated oven for 12-15 minutes or until the crust is golden brown.",
  "Slice and serve hot."

#### Описание
- Подробное описание рецепта, взятого из API

#### Изображение
- Пространство для изображения блюда.

#### Навигация
- Кнопки навигации для возврата к списку рецептов или перехода к следующему/предыдущему рецепту.

## Технические требования
- Приложение разработано с использованием React (При необходимости стетменеджер Redux).
- Использован официальный API https://dummyjson.com/docs/recipes
- Роутинг выполнен с использованием React Router.
- Фреймворк UI любой на ваше усмотрение (как пример Ant Design или Semantic UI).
- Можно и на чистом css, главное, чтобы соответствовало макету.
- Пакетный менеджер yarn.
- Приложение должно запускаться по адресу localhost:3000 командой `yarn start`.
- При переходах по карточкам страница не перезагружается.
- Исходный код решения должен быть выложен с вашего аккаунта на Github с Readme файлом с инструкцией по запуску.

#### Опциональные задания
- Использование TypeScript.
