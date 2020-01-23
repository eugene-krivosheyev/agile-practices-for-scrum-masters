# Командный тренинг «Культура, процесс и инженерные практики разработки ПО для не-разработчиков»
_Как понять разработчиков и помочь им?_ 18 hrs/6 sessions.

![](vision.png)

# Objectives
## После тренинга участники смогут применять:
### Коммуникации с инженерами
- [ ] Понимание *языка разработчиков*
- [ ] Их *способы решения задач*
- [ ] Их *когнитивные ловушки*
### Культура и процесс
- [ ] *Производственная культура* для осознания личной и командной культур инженерами
- [ ] PBI *DoD* как механизм контроля внутреннего качества
- [ ] *Парная разработка* в формате Driver + Navigator и когда ее применять
### Работа с требованиями
- [ ] Понимание ценности в формате *User Story*
- [ ] Ключевые внешние *NFRs*
### Инженерные практики обеспечения внешнего качества
- [ ] *Автоматизированное тестирование*
### Инженерные практики обеспечения внутреннего качества
- [ ] *Внутренняя модель качества* из обоснованных внутренних NFRs и *технический долг*
- [ ] *Simple Design*
- [ ] *Рефакторинг* 
- [ ] *Code Review*
- [ ] *Статический анализ кода*
### Инженерные практики ускорения поставок
- [ ] *Автоматическая сборки* релиза
- [ ] *CI*
- [ ] *Версионирование схемы БД*
- [ ] *CD*
- [ ] *Культура DevOps* и *Continouos Feedback*

# Программа
## Зачем мы собрались? (3 часа всего / _из них_ 0.25 часа практики и обсуждений)
- [ ] Знакомство
- [ ] Договоренности
- [ ] Парковка кейсов и проблем участников: проблемные ситуации на производстве
- [ ] Ветка потока в github
## Уровни решений в производстве ПО
- [ ] Общая картина дисциплин "снизу-вверх"

---

## Ретроспектива по прошлой сессии (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Введение в разработку ПО (1.5/0.25)
### Разработчики не такие умные
- [ ] Модель уровней понимания и зоны черного ящика
- [ ] Закон расширения черного ящика: цикл Коулба
### Начинаем песональный глоссарий технологий и практик
- [ ] В отдельном документе Markdown для каждой пары
- [ ] *Свой* глоссарий важных для *вас* концепций
### Live Codeing Demo: ключевые технологические решения в разработке ПО и их история
- [ ] Кейс: онлайн-система ДБО
- [ ] OS и Hardware
- [ ] Исходники и синтаксис
- [ ] Компиляция и интерпретация
- [ ] Запуск приложения
- [ ] Процедурный стиль
- [ ] Библиотеки кода
- [ ] Объектный стиль
- [ ] Конфигурация vs hardcode
- [ ] Фреймворки и аспекты
- [ ] Автотесты и заглушки
- [ ] Автосборка

## Командная работа с кодом (1/0.5)
### DVCS local workflow
- [ ] Local repo
- [ ] Workspace
- [ ] Commit
- [ ] Branch and merge
- [ ] Log
### DVCS remote workflow
- [ ] Remote repo
- [ ] Clone
- [ ] Push
- [ ] Pull
### Configuration Management patterns
- [ ] Repo patterns: centralized/decentralized
- [ ] Branch patterns: GitFlow/TBD+FT
- [ ] Pull Requests
### Hands-on
- [ ] Github account
- [ ] Central Glossary github repo
- [ ] Teams make overall cross-team glossary with PRs

## Sound-check (0/0)
- [ ] Участники могут на своих машинах клонировать, собрать проект и запушить изменения

---

## Ретроспектива по прошлой сессии (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Введение в типовую архитектуру современных систем и автосборку (2.5/0.5)
### Кейс: онлайн-система персонального финучета
- [ ] Points Of View
- [ ] Архитектура клиент-сервер
- [ ] Удаленные вызовы и типы клиентов
- [ ] Типовые паттерны в рамках системы
- [ ] Помощь фреймворка
- [ ] Хранилища данных
### Автоматическая сборка проекта
- [ ] Maven build tooling
- [ ] Maven dependency tooling
### Hand-on
- [ ] Cloning project from application repo
- [ ] Building and running app

---

## Ретроспектива по прошлой сессии (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Backlog (1/0.5)
- [ ] Что такое беклог? Какие ключевые свойства?
- [ ] Элементы беклога – единица планирования и результ процесса коммуникации
- [ ] Как происходит управление элементами беклога? Порядок внесения новых элементов, уточнение и жизненный цикл.
- [ ] Элементы беклога: Themes, Epics, User Stories
### BPI
- [ ] Name
- [ ] Story
- [ ] Acceptance Criteria
- [ ] NFRs
- [ ] DoD
### Декомпозиция историй
- [ ] Почему важно декомпозировать истории? 
### Hand-on
- [ ] Requirements reverse engineering for application

## Что бизнес ждет от _производственной системы_ (1.5/1)
### Команды выбирают процессные паттерны и обосновывают через бизнес-метрики
- [ ] Подход SLA к балансу бизнес-метрик: scope, time, quality, price, ?. Time-boxing.
- [ ] Подход к частоте поставок: сервис/проекты
- [ ] Подход к запасам. JIT. Запасы в IT-разработке.
- [ ] Подход к структуре команд: feature teams/matrix. Свойства feature team.
- [ ] Подход к формализации/самоуправлению
- [ ] Подход к описанию процесса: процедурный/декларативный. Практика PBI DoD
- [ ] Подход к ответственности: персональная/коллективная
- [ ] Подход к коммуникациям: формальная/неформальная. Распределение знаний по артефактам.
- [ ] Подход к экспертизе: фокусировка/T-shaping. Практика Star Map.
- [ ] Подход к инженерным решениям: все запроектировать заранее/откладывай@делегируй
- [ ] Подход к гибкости в архитектуре: делать гибко/делать просто
- [ ] Подход к внутреннему качеству (техдолгу): фигак-фигак-и-впродакшн/техналог 
### Трансформация
- [ ] Работающие инженерные практики как результат трансформации
- [ ] Reference: [Как безопасно трансформировать культуру и процесс](https://www.dropbox.com/s/h9ghvkktirbxgdw/%D0%98%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D0%BF%D0%BE%D0%B4%D1%85%D0%BE%D0%B4%20%D0%BA%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BA%D1%83%D0%BB%D1%8C%D1%82%D1%83%D1%80%D1%8B%20%D0%B8%20%D0%B2%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%20Agile.pdf?dl=0)

---

## Ретроспектива по прошлой сессии (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Переход к процессу разработки и поставки: дизайн процесса через выбор практик (2.5/1)
- [ ] Структура итерации/спринта
- [ ] Современное отношение к дизайну процессов: от императивности и формальности к декларативности и гибкости
- [ ] Выбор практик как process design core
### CI/CD Pipeline Live Demo: пронос изменений по всему конвейеру с описанием задействованных практик
- [ ] Demo
- [ ] Retro
- [ ] Pair Programming
- [ ] ATTD + Cucumber + Selenium
- [ ] TBD + Feature Toggling
- [ ] TDD
- [ ] Simple Design
- [ ] Code Review
- [ ] Automated Build
- [ ] Test Coverage Metrics
- [ ] DB Versioning
- [ ] CI
- [ ] Automated Code Review and Metrics
- [ ] CD
- [ ] System and Business Metrics
#### Культура DevOps и Continouos Feedback
- [ ] Почему культура?
### Проектируем модель зрелости процесса через практики
#### Даны уровни зрелости процесса с т.з. бизнеса
1. Уровень: хоть как-то получаем хоть какой-то результат на prod
2. Уровень: управляем внешним качеством
3. Уровень: управляем внутренним качеством
4. Уровень: управляем TTM
5. Уровень: управляем успехом продукта
#### Когда
- [ ] Команды расставят практики из целей тренинга по уровням (+неуказанные)
- [ ] BPI DoD
#### Тогда на дебрифе
- [ ] Мерж в единый процессный беклог: долг по внедрению практик для дальнейшей проработки в рамках тренинга
- [ ] Кросс-ревью командных моделей зрелости
- [ ] Дополняем глоссарий
### Reference: [как практики помогает разработке](https://paper.dropbox.com/doc/Delivery-Pipeline-ci-cd-devops--AbaLMZphhnvfm0spHme2SHkYAg-OBLCVRSkMek24U7IXIHbq)

---

## Ретроспектива по прошлой сессии (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Что бизнес ждет от _производственной культуры_ (2/0)
- [ ] Понятие культуры компании
- [ ] Роль производственной культуры компании
- [ ] Групповая практика на определение производственной культуры по Шнайдеру
- [ ] [Типовые когнитивные ловушки инженеров](https://www.dropbox.com/s/o1bgzqldh25fpti/%D0%90%D0%BD%D1%82%D0%B8%D0%BF%D0%B0%D1%82%D1%82%D0%B5%D1%80%D0%BD%D1%8B%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%BE%D0%B2%20%D0%B2%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%BE%D0%B2%D1%8B%D1%85%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D1%8F%D1%85.pdf?dl=0)

## Финальная ретроспектива (0.5/0.5)
### Даны
- [ ] Полученные на тренинге знания
- [ ] Полученные на тренинге практический опыт
- [ ] Полученные на тренинге артефакты
### Когда
- [ ] Кросс-командная ретроспектива тренинга
### Тогда
- [ ] Закрытые цели тренинга, burndown
- [ ] Инсайты
- [ ] 𝚫+
- [ ] *Обоснованные* next actions на производстве
