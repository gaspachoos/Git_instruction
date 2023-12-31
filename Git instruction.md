# Инструкция GIT 

## 1. Задаем свое имя  Git-у
```sh
git config --global user.name "Имя,Фамилия"
```
## 2. Задаем свой email Git-у
```sh
git config --global user.email "наш email"
```
## 3. Для проверки имени и фамилии 
```sh
git config user.name или git config user.email
```
## 4. Для привязки папки,задаем адрес
```sh
cd "Путь к файлу"
```
## 5. Для обзора версии Git-а 
```sh
git --version
```
## 6. Для создания репозитория
```sh
git init
```
## 7. Обзор состояния файла с которым работаем
```sh
git status
```
## 8. Что бы добавить файл для отслеживания 
```sh
git add пишем первые несколько символов из названия нашего файла и нажимаем Tab,после чего программа сама допишет название файла
```
## 9. Commit для изменений 
```sh
git commit -m "Пример текста:"Добавили новый текст"
```
## 10. Журнал изменений 
```sh
git log
```
## 11. Что бы увидеть выбранный этап сохраненя 
```sh 
git checkout "Первые 4 символа нашей ссылки"
```
## 12. Для продолжения работы в актуальном состоянии 
```sh
git checkout master
```
## 13. Разницу между не сохраненным и сохраненным файлом 
```sh
git diff
```
## 14. Листинг текущей директории
```sh
dir
```
## 15. Удаление файла
```sh
rm "название файла"
```
## 16. Для игнорирования файла Git-ом создаем файл в корневой директории
```sh
.gitignore
```
## 17. Вывод короткой версии log
```sh
git log --oneline
```
## 18. Удаление текущего изменения 
```sh
git restore
```
## 19. Отменяем действие 
```sh
git restore --staged
```

# Инструкция для работы с MarkDown

## Выделение текста 

Чтобы выделить текст курсивом необходимо обрамить егозвездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным,необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркиваниия (__) .Например **вот так** или __вот так__.

Альтернативные способы выделение текста жирным или курсивом нужны для того,чтобы мы могли совмещать оба этих способа. Например, _Текст может быть выделен курсивом и при этом быть **полужирным**_. 


## Списки 


Чтобы добавить ненумерованные списки,необходимо пункты выделить звездочкой (*).

Например,вот так:
* Элемент 1
* Элемент 2 
* Элемент 3

Что бы добавить нумерованные списки,необходимо пункты просто пронумеровать.

Например вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями 
Чтобы вставить изображение в текст,достаточно сделать следующее:
![Альберт :P](Альберт.jpg) 


# Работа с удаленными репозиториями в GIT

## GitHub
* Представляет Microsoft 
* Самый популярный сервис Git
* Много полезных функций 
* Огромный архив различного кода

## Мы можем копировать с GitHub ссылку кода и внедрить в наш Git и работать с ней 
```sh
git clone "ссылка кода"
```
## *Особенности команды clone*

*Мы можем указать при клонировании любую папку,даже новую,не существующую,команда создаст и склонирует все в него.*

### После клонирования нужно будет указать папку с директорием 
```sh
git cd "путь к папке"
```

## Чтобы с локальной репозитории направить все в интернет используем команду 
```sh
git push
```

## *Особенности команды push*

*git должен знать адрес удаленного репозитория,git должен быть "авторизован" на внесение изменений в удаленном репозитории*

## Если наш код в GitHub-e будет открытый,то если кто-то внесет изменения,наша версия ропзитория на локальном устройстве устраеет,используем команду
```sh
git pull
```
## Как сделать pull request

1. Делаем **fork** репозитория
2. Делаем **clone** своей версии репозитория
3. Создаем новую ветку и в нее вносим свои изменения
4. Фиксируем изменения (делаем **commit**)
5. Отправляем свою версию в свой **GitHub**
6. На сайте **GitHub** нажимаем кнопку **pull request**

## Чтобы связать наш удаленный репозиторий с локальным нужно в локальном написать
```sh
git remote add origin "ссылка репозитория"
```



## Ссылки

## Работа с таблицами 

## Цитаты 

„Жизнь — как вождение велосипеда. Чтобы сохранить равновесие, ты должен двигаться.“


## Заключение 




