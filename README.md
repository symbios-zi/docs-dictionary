# Перевод терминов из документации

**action** - метод контроллера

**callback** - функция обратного вызова, анонимная функция, или просто функция

**dependency injection** - внедрение зависимостей

**facade** - фасад

**guards** - гварды

**helper** - хелпер

**instance** - экземпляр

**jobs** - задачи в очереди _(**job dispatching** - выполнение задачи в очереди)_

**middleware** - посредник 

**migration** — миграция

**route** - роут

**service container** - сервис-контейнер

**service provider** - сервис-провайдер

**trait** - трейт

**unit-test** — юнит-тест

**queue** - очередь

**render** - отображение _(**render a view** - отображаение шаблона)_

**service** - сервис

**throw exception** - бросить исключение

**view** - шаблон

**Composer** - Composer _(переводить не стоит)_

**view composer** - вью-композер

**redirect** - редирект

**alias** - псевдоним

**signature** - сигнатура

### Главная проблема

**type-hint**

"Type hinting" - это контроль типов. "type-hint" в контексте Laravel это как правило означает подачу в аргументы какого-либо класса. Т.е. , например "First, let's look at accessing the session via a Request instance, which can be type-hinted on a controller method" - это что-то вроде "Один из методов доступа к сессиям - при помощи экземпляра класса Request, который можно указать в качестве аргумента метода контроллера." . Если подобное обыгрывание невозможно, то можно type-hint оставить непереведённым.
