aka `SpyDev14`, `_b.VV();`, etc.\
Твинки: [spy-dev-14](https://github.com/spy-dev-14)

# Обо мне
Привет! Меня зовут Влад, я студент колледжа на четвёртом курсе по IT направлению. В свободное от работы и учёбы время люблю писать программы, изучать программирование и компьютерные науки. Люблю разбираться как работает какая-то "магия", будь то устройство Python, сети / прочий IO, или процессор. Также иногда принимаю участие в разработке билдов Space Station 14.

<details>
  <summary>Интересные факты об asyncio и генераторах в Python</summary>
  
Вот вы например знали, что asyncio в Python под капотом работает на генераторах? Первая версия модуля asyncio для Python 3.5 строилась на синтаксисе `yield from`, затем в CPython для корутин была создана отдельная структура, на 90% схожая с кодом генератора. А генератор - это не просто "`Iterable`" - это именно объект с двусторонней связью. Вы в курсе, что вы можете написать "`x = yield y`", и отправить значение через `some_gen.send(5)`? `send` вернёт управление к yield и x получит переданное значение. А `next` для генератора - это просто `send(None)`! `yield from` же пробрасывает все операции к переданному вложенному генератору (`x = yield from inner_gen`). Также вы можете возбудить исключение внутри генератора через метод `.throw(Exception)`. Так и работал `asyncio` до появления собственного синтаксиса, который, кстати, по словам автора взят из C#!

И я могу ещё много про что рассказать: про объектную систему в Python (а она очень интересная), про концепцию ООП (особенно про инкапсуляцию), про реализацию функций в машинном коде (и от куда берётся ошибка рекурсии), про ссылочно-значимые типы, про стек и кучу, про работу с IO на Linux (вот вы знали, что работа с сетью, файлами, консолью и мышкой / прочей периферией реализована через одни и те же системные функции?), что работа asyncio на Linux & Windows отличается, потому-что на Windows нет epoll и Python имитирует его, что может приводить к ошибкам?
</details>

## Контакты
- Телеграм (приоритетный способ): [@bViewVariables](https://web.telegram.org/k/#@bViewVariables)
- Discrod: `spy.3082`

## Мои библиотеки (Python)
1. [`django-admin-registrar`](https://github.com/SpyDev14/django-admin-registrar): Автоматический регистратор моделей в админ-панели Django с возможностью указать админ-классы по умолчанию

## Мои лучшие pet-проекты
### Python/Django-стек
1. [Django-проект с новой архитектурой папок на Хакатон ТСПК 2026 г.](https://github.com/SpyDev14/AutoShop)
2. [Моя реализация](https://github.com/SpyDev14/TLTConvectorTraining) сайта ["ТЛТ Конвектор"](https://tlt-konvektor.ru/?ysclid=mwwb6a0h3n208366758)
3. [Сервис управления задачами сотрудников на Django REST Framework](https://github.com/SpyDev14/TaskManagerAPI)
### Python/FastAPI-стек
1. [Бекенд для обработки оплаты по вебхуку; админским и пользовательским API](https://github.com/SpyDev14/FAPIDemo)
### Другое
1. [Игра-бродилка с псевдо-трёхмерной графикой на чистом C#](https://github.com/SpyDev14/TheWalkingGame)
2. [Консольный тетрис на Rust](https://github.com/SpyDev14/tetris-rust)
3. [Веб-сервер на чистом C под Linux](https://github.com/SpyDev14/crazy-web-server)

## Мой вклад в Open Source
### Space Station 14
1. [Улучшение UI консоли заказов (совместно с @c4llv07e)](https://github.com/space-wizards/space-station-14/pull/34052)
2. [Улучшение UI меню факса (pr на основе моей работы)](https://github.com/space-wizards/space-station-14/pull/33825)
3. [Исправил адаптив окна ускорителя частиц](https://github.com/space-wizards/space-station-14/pull/34037)
4. [Исправил адаптив окна консоли связи](https://github.com/space-wizards/space-station-14/pull/33655)
5. [Исправил локализацию в окне консоли шаттла](https://github.com/space-wizards/space-station-14/pull/33651)
6. [Улучшил адаптив окна заряжаемого объекта](https://github.com/space-wizards/space-station-14/pull/34036)

### Nuclear 14
1. [Значительное улучшение локализации названий и описаний внутриигровых ролей](https://github.com/Forge-Station/nuclear-14/pull/87) (RU форк; первый pull-request)
2. [Добавил множество новых рецептов одежды, оружия, щитов и прочего для не использующихся верстаков (бронный, оружейный, и т.д); добавил новый материал - кожу, способы её получения; возможность рвать одежду на ткань и кожу, а также многое другое](https://github.com/Vault-Overseers/nuclear-14/pull/520)

### Metro 14
1. [Добавлены базовые тайлы](https://github.com/Metro-Observers/metro-14/pull/4)
2. [Добавлена куча новых тайлов](https://github.com/Metro-Observers/metro-14/pull/20)
3. [Звук начала раунда заменён на фрагмент главной темы Metro 2033 LL](https://github.com/Metro-Observers/metro-14/pull/9)
4. [Заставки главного экрана заменены на арты по Metro 2033](https://github.com/Metro-Observers/metro-14/pull/7)
5. [Добавлен генератор планеты `M14Underground` (карта метро)](https://github.com/Metro-Observers/metro-14/pull/8)


<!---
SpyDev14/SpyDev14 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
