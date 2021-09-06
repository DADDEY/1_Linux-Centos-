# Module#1_Linux-Centos
Домашнее задание №1
Процессы, fork()
Упражнение 1
Напишите программу (на языке C), которая вызывает fork () в цикле 3 раза и спит (
sleep(..) ) 5 секунд. Запустите программу в фоновом режиме и запустите команду
pstree несколько раз. Посмотрите на вывод и скажите, сколько процессов создано.
Объясните результат. Измените программу так, чтобы она вызывала fork () 5 раз.
Посмотрите, как меняется результат. Сохраните код в Робокод.
Упражнение 2
Напишите свою собственную упрощенную оболочку (shell). Он должен читать
пользовательский ввод и иметь возможность запускать команду без параметров, таких
как pwd, ls, top, pstree и т.д. Сохраните код в Робокод.
• Подсказка: используйте команду man
Упражнение 3*
Выясните, что происходит с файлами, открытыми в процессе, когда данный процесс
вызывает системный вызов fork()? Ответ дайте в виде текстового описания и загрузите
его в Робокод
Файлы
Упражнение 4
Создайте файл file.txt в каталоге abc и получите доступ к этому файлу из каталога xyz
через $ link <source> _some_file.txt
• Проследить все ссылки на file.txt: $ find <path> –inum inodenumber
•Удалить все ссылки to file.txt $ find <path> –inum inodenumber -exec rm {} \;
• Сохранить вывод в файл ex4.txt. Сохраните историю команд в Робокод.
Упражнение 5
Создайте файл ex5.txt и попробуйте следующее:
• Удалить права на выполнение для всех
• Предоставить все права владельцу и другим (т.е. всем, но не группе)
• Сделать групповые права равными правам пользователя.
• После каждого шага сохраняйте вывод / ответ в ex5.txt. Сохраните историю команд в
Робокод.
