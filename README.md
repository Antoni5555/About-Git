 # Знакомство с Git


<<<<<<< HEAD
#### **Git** - это одна из самых популярынх сисетем контроля версий. То есть система Git позволяет пользователю отслеживать все изменения в проекте и взаимодействовать с ними.
=======
#### <font color="Green">**Git**</font> - это одна из самых популярынх сисетем контроля версий. Cистема Git позволяет пользователю отслеживать все изменения в проекте и взаимодействовать с ними.
>>>>>>> 9792471e0e657f799b0faf3a441cef2cfaa55aa4

### Зачем мне Git?
#### 1. Git может сохранять твой проект в различные моменты времени, так же как ты сохраняешь свой прогресс в играх. Ты всегда можешь вернуться в нужную тебе точку.                       <br><br>2. С помощью Git над одним проектом может трудиться сразу несколько человек, благодаря его возможностям сохранять и склеивать работы всех членов команды.


## **Полезные команды Git:**

### Команды навигации

* _pwd_ - показать текущую [дерикторию](https://u.to/d9lhIA). То есть дерикторию в которой вы  находитесь в настоящее время. 
* _cd_ - сменить текующую дерикторию.
* _~_ - обозначение [домашней](https://u.to/LtlhIA) директории, как правило используется вместе с командой **cd**.
* _.._ - [родительская](https://u.to/O9lhIA) директория, как правило используется вместе с командой **cd**.
* _/_ -  [корневая](https://u.to/R9lhIA) директория, как правило используется вместе с командой **cd**.

_Пример:_ 
<br>[ _cd ~_ ] - сочетание **cd** и **~** вызовет в консоли смену текущей дерриктории на домашнюю.
<br>[ _cd .._ ] - сочетание **cd** и **..**  сменет текущую деррикторию на родительскую.
<br>[ _cd /_ ] - сочетание **cd** и **/**  сменет текущую деррикторию на родительскую.
   
* _ls_ - вывести содержимое текущей директории.


### Команды взаимодействия

* _touch_ - создание файла. 
<br> _Например:_ [ __touch file.txt__ ]- создаст текстовый файл **file** с расширением **.txt** в текущей директории.
* _mkdir_ - создание директории. 
<br> _Например:_ [ __mkdir new-directiry__ ]- создаст директорию **new-directiry** внутри текущей директории.

### На заметку 
_C помощью флага [ -p ] можно создать целую структуру директорий._
<br>[ mkdir -p der1/dir2/dir3/...] - данная команды создаст три директории, в заданном иерархическом порядке.

_Вам не обязательно переходить в нужную директорию чтобы создать там файл или другой каталог. Можно указать адрес перед создаваймым объектом._
<br>[mkdir ~/new-directory] - создаст новую директорию внутри домашней.
<br>[touch ../file.txt] - создаст файл с именем **file.txt** в родительской директории.

* _cp_ - копирование файла.
<br> _Например:_ [ __cp text.txt sky.png code.py ../__ ]- данная команда [cp] скопирует файлы **text.txt**, **sky.png**, **code.py** в родительскую директорию [../].

* _mv_ - перенести или вырезать файл в другую директорию.
<br> _Например:_ [ __mv ../file.txt sky.png/import__ ]- данная команда переместит файл **file.txt** из родительской директории и **sky.png** из текущей директории в папку **import** в рабочей директории.

* _cat_ - чтение файла. _Например:_ [ cat text.txt ] - команда откроет файл **text.txt**. 
* _rm_ - удаление файла. _Например:_ [ rm sky.png ] -  команда удалит файл **ske.png**.
* _rmdir_ - удаление пустой директории. _Например:_ [ rmdir new-dir ] -  команда удалит пустую директорию **new-dir**.
* _rmdir -r_ - рекурсивное удаление всех файлов и папок, т.е. команда удалит все файлы внутри директории, а затем и саму директорию._Например:_ [ rmdir -r new-dir ] -  команда удалит директорию и все что вней находится **new-dir**.



