R&D: BasicOS (x86/ZX)
===
Проект является исследовательским, и нацелен на создание эко-системы ZX на современных компьютерах.

Preamblua
====
Проект состоит из двух зависимых друг от друга частей. Это платформозависимый [BIOS](bios.md) и непосредственно сама [BasicOS](os.md).

BIOS
====
Платформозависимая часть проекта, служащая прослой между железом и ОС. Выполняющая операции ввода вывода, настройки оборудования, а также непосредственный запуск ОС с оборудования помеченного как Загрузочный. А также предоставляет утилиту по настройке оборудования перед запуском ОС.

OS
====
Платформонезависимая часть проекта, обеспечиваящая пользователя интерфесом необходимым для работы с оборудованием. При запуске ОС пользователя встречает приветствие вида `[/]$` , где **/** является текущей директорией активного в текущий момент оборудования
