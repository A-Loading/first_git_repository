# Подсказки по терминалу

Команда смены директории
```sh
CD <<Path>>
```

Команда отображения текущей дирикториии
```sh
PWD
```

листинг текущей директории
```sh
LS
```

удаление файла 
```sh
RM <<File>>
```

Команда touch используется для изменения метки времени любого заданного файла.

Также утилита создаёт файл, только если он ещё не существует
```sh
touch <<arg>> <<File>>
```

echo "text">>FILE   >> (to file)

# echo -e

color|ansii|color|ansii
-|-|-|-
Black       | 0;30   |  Dark Gray     |1;30
Red         | 0;31    | Light Red     |1;31
Green       | 0;32    | Light Green   |1;32
Brown/Orange| 0;33    | Yellow        |1;33
Blue        | 0;34    | Light Blue    |1;34
Purple      | 0;35    | Light Purple  |1;35
Cyan        | 0;36    | Light Cyan    |1;36
Light Gray  | 0;37    | White         |1;37
And then use them like this in your script:

RED='\033[0;31m'
\033[0m' # No Color
echo -e "I ${RED}love${NC} Stack Overflow"