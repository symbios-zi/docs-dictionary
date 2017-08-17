# Перевод спорных терминов из документации

**action** - метод контроллера
**dependency injection** - внедрение зависимости
**facade** - фасад
**instance** - экземпляр
**middleware** - посредник 
**migration** — миграция
**service container** - сервис-контейнер
**service provider** - сервис-провайдер
**trait** - трейт
**unit-test** — юнит-тест
**view** - шаблон

### Главная проблема
**type-hint**
"Type hinting" - это контроль типов. "type-hint" в контексте Laravel это как правило означает подачу в аргументы какого-либо класса. Т.е. , например "First, let's look at accessing the session via a Request instance, which can be type-hinted on a controller method" - это что-то вроде "Один из методов доступа к сессиям - при помощи экземпляра класса Request, который можно указать в качестве аргумента метода контроллера." . Если подобное обыгрывание невозможно, то можно type-hint оставить непереведённым.
