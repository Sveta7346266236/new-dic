Шпаргалка GIT
<br>
*README.md — текстовый файл, который можно создать командой touch, а затем редактировать так же, как и любой другой текстовый документ.*
```
$ cd C:\Users\студент\new-dir #чтобы войти
<br>
$ pwd - проверка где мы находимся
<br>
$ touch faile.txt - создание файла с названием
  <br>
  $ git add -добавить файл на отслеживание
  <br>
$ git commit -m - добавление к комментария
<br>
$ git push синхронизируем с локальной версией 
<br>
```
**$ ls**`-Вывести содержимое директории`
<br>
**$ mkdirs**` -создания директорий` 
<br>
**$ cps**` -Копирование файлов` 
<br>
**$ mvs**` - Перемещение файлов и папок`  
<br>
**$ cats**` - Чтение файлов` 
<br>
**$ rms**` - Для удаления файла`
<br>
**$ rmdirs**` - для удаления пустой директории`
<br>.
**$ rm -rs**` -для директории с файлами` 
<br>
**$ the-best-file-ever.txts**` - Прочитать файл `
<br>
**$ the-best-file-ever.txts**` -Удалить файл` 
<br>
**$ screenshotss**` - Удалить папку` 
<br>
**$ gitconfig**` - Работа с файлом настройки`
<br>
**$ git init**` - Сделать папку репозиторием` 
<br>
**$ cd ~/dev/first-project**` # перешли в нужную папку`
<br>
**$ git init**` # создали репозиторий` 
<br>
**$ git status**` - Проверить состояние репозитория` 
<br>
**$ root-commit**` — это самый первый, или «корневой»` 
<br>
**$ 2 files changed, 1 insertion(+)**` значит: изменились два файла (readme.txt и todo.txt);`
<br>
**$ create mode 100644 readme.txt**` — это более подробная информация о новых (добавленных в Git) файлах`
<br>
**$ git log**` - Просмотреть историю коммитов`
<br>
```

Команда git status всегда подскажет, что происходит с файлом: например, он добавлен в список «на коммит» или ещё вообще не отслеживается, или изменён.

git status показывает явно следующие состояния файлов: untracked, staged и modified.

<тут пустая строка!>
git status подсказывает, какие команды можно выполнить, чтобы поменять состояние файла.
```

**Как откатиться назад, если «всё сломалось**
<br>
На разных этапах работы с Git могут происходить похожие ситуации:
<br>
•	В список на коммит попал лишний файл (например, временный). Нужно «вынуть» его из списка.
<br>
•	Последние несколько коммитов ошибочные: например, сделали не то, что было нужно, или нарушили логику. Хочется «откатить» сразу несколько коммитов, вернуть «как было вчера».
<br>
•	Случайно изменился файл, который вообще не должен был меняться. Например, вы открыли не тот файл в редакторе и начали его исправлять.
<br>
**git restore --staged <file>** - Убрать файл из staging поможет команда 
<br>
**git restore --staged** -она сбросит всю текущую папку 
<br>
**git reset --hard <commit hash>** -Откатить» коммит 
<br>

