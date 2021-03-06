# Инструкция по работе с git
Для создания локального репозитория нужно запустить команду:
>git init

Для добавления файла к следующему коммиту:
>git add

и фиксируем эти файлы:
>git commit

Для отслеживания состояния репозитория можно ввести команду:
>git status

Чтобы посмотреть все коммиты:
>git log

Для просмотра разницы между закоммиченными и текущими изменениями:
>git diff

Для перехода к прошлым коммитам (с кодом commit_code) можно использовать комманду:
>git checkout commit_code

и чтобы вернуться:
>git checkout master 

![какая-то картинка](изображение_viber_2022-03-29_16-25-48-567.jpg)

## Подзаголовок

### Второй подзаголовок

*Курсив выделяется звездочками*

**Жирный текст выделяется двумя звездочками**

Нумерованные списки обозначаются цифрами:
1. раз
2. два
3. три

Ненумерованные списки обозначаются звездочками:
* раз
* два
* три

>Для вставки цитат используют знак >
>>цитата второго уровня
>>>цитата третьего уровня
>
>еще одна цитата первого уровня

Чтобы создать ветку. нужно:
> git branch branch_name

Для просмотра всех веток:
> git branch

Для перехода к ветке branch_name, используем:
 >git checkout branch_name git
 
 Для совмещения текущей ветки с веткой branch_name:
 >git merge branch_name
 
 изменения добавятся в текущую ветку
 
 Для того, чтобы удалить ветку branch_name, нужно:
 > git branch -d branch_name

 Для визуализации веток можно использовать:
 >git log --graph

Если ветка неполностью замержена, то с помощью тега -d удалить её не получится, тогда нужно использовать тег -D:
>git branch -D branch_name

Ветка4: зачеркнутый текст пишется с помощью символов ~~

например, ~~вот так~~
Ветка3: чтобы добавить полужирное курсивное начертание, нужно использовать символы ***:

например, ***вот так***

Что-то на ветке2.

Что-то на ветке1.

