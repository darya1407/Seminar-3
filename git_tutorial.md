# Туториал по GIT 

## Как добавить скв в ваш проект

Чтобы добавить систему контроля версий в ваш проект, используйте следующую команду

```
git init
```

## Как зафиксировать изменения в git

Чтобы зафиксировать изменения, добавьте следующую команду:

```
git commit -m "Ваше сообщение"
```

## Как получить информацию от git о его состоянии

Чтобы получить данные о текущем состоянии git, необходимо выполнить следующую команду:

```
git status
```

## Как добавить файл(ы)

Для того, чтобы добавить один или несколько файлов к следующему коммиту необходимо выполнить команду:

``` 
git add
```

## Как перейти от одного коммита к другому

Чтобы выполнить переход, необходимо воспользоваться командой ***git checkout***

## Как увидеть разницу между файлами

Команда ```git diff``` используется для вычисления разницы между текущим файлом и закоммиченным файлом

## Как сбросить изменения

Команда ``` git reset номеркоммита``` позволяет сбросить все изменения до определенного коммита