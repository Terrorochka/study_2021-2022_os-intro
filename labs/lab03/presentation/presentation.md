---
## Front matter
lang: ru-RU
title: Laboratory
author: Pavlova Polina

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
- \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
- '\makeatletter'
- '\beamer@ignorenonframefalse'
- '\makeatother'
aspectratio: 43
section-titles: true
---

# Лабораторная работа № 4

# Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки

## Pavlova Polina

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Выполнение лабораторной работы

### Определите полное имя вашего домашнего каталога.(рис.1.1)

![image](image/1.png)

Рис.1.1 Определение полного имени домашнего каталога

### Перейдите в каталог /tmp.(рис.2.1)

![image](image/2.png)

Рис.2.1 Переход в каталог /tmp

### Выведите на экран содержимое каталога /tmp. Для этого используйте команду ls с различными опциями. Поясните разницу в выводимой на экран информации.(рис.2.2-2.3)

![image](image/3.png)

Рис.2.2 Вывод на экран содержимое каталога /tmp используя команду ls

![image](image/4.png)

Рис.2.3 Вывод на экран содержимое каталога /tmp используя команду ls с опцией -а

### Определите, есть ли в каталоге /var/spool подкаталог с именем cron?(рис.2.4)

![image](image/5.png)

Рис.2.4 Определение наличия подкаталога с именем cron

Такого каталога нет.

### Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Определите, кто является владельцем файлов и подкаталогов?(рис.2.5-2.6)

![image](image/6.png)

Рис.2.5 Переход в домашний каталог и вывод на экран его содержимого

![image](image/7.png)

Рис.2.6 Определение, кто является владельцем файлов и подкаталогов

### В домашнем каталоге создайте новый каталог с именем newdir.(рис.3.1)

![image](image/8.png)

Рис.3.1 Создание нового каталога с именем newdir в домашнем каталоге

### В каталоге ~/newdir создайте новый каталог с именем morefun.(рис.3.2)

![image](image/9.png)

Рис.3.2 Создание нового каталога с именем morefun

### В домашнем каталоге создайте одной командой три новых каталога с именами letters, memos, misk. Затем удалите эти каталоги одной командой.(рис.3.3-3.4)

![image](image/10.png)

Рис.3.3 Создание одной командой трёх каталогов с именами letters, memos, misk

![image](image/11.png)

Рис.3.4 Удаление трёх каталогов одной командой

### Попробуйте удалить ранее созданный каталог ~/newdir командой rm. Проверьте, был ли каталог удалён.(рис.3.5)

![image](image/12.png)

Рис.3.5 Удаление каталога newdir командой rm

Каталог не был удалён.

### Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли каталог удалён.(рис.3.6)

![image](image/13.png)

Рис.3.6 Удаление каталога ~/newdir/morefun из домашнего каталога с проверкой содержимого

Каталог был удалён.

### С помощью команды man определите, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него.(рис.4.1)

![image](image/14.png)

Рис.4.1 Опция -R используется для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него

### С помощью команды man определите набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.(рис.5.1-5.2)

![image](image/15.png)

Рис.5.1 Опция -l

![image](image/16.png)

Рис.5.2 Опция -t

### Используйте команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. Поясните основные опции этих команд.(рис.6.1-6.9)

![image](image/17.png)

Рис.6.1 Ввод команды man cd

![image](image/18.png)

Рис.6.2 Результат работы команды man cd

![image](image/19.png)

Рис.6.2 Ввод команды man pwd

![image](image/20.png)

Рис.6.3 Результат работы команды man pwd

![image](image/21.png)

Рис.6.4 Ввод команды man mkdir

![image](image/22.png)

Рис.6.5 Результат работы команды man mkdir

![image](image/23.png)

Рис.6.6 Ввод команды man rmdir

![image](image/24.png)

Рис.6.7 Результат работы команды man rmdir

![image](image/25.png)

Рис.6.8 Ввод команды man rm

![image](image/26.png)

Рис.6.9 Результат работы команды man rmdir

### Используя информацию, полученную при помощи команды history, выполните модификацию и исполнение нескольких команд из буфера команд.(рис.7.1-7.2)

![image](image/27.png)

Рис.7.1 Вывод команды history

![image](image/28.png)

Рис.7.2 Модификация и сполнение команды mkdir

# Выводы

Были получены практические навыки взаимодействия с системой посредством командной строки.































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































