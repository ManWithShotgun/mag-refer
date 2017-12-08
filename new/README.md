В главном файле надо  указать путь к стилям так:
\documentclass[12pt,a4paper%,openbib
]{`styles/report`}

А и самого `report` надо указывать относительно главного файла `\usepackage{styles/axodraw}`

* Diff от оригинала*
1. `\usepackage[utf8x]{inputenc}` было: `\usepackage[cp1251]{inputenc}`


LATEX UI:
Я использую TeXstudio. MiKTeX 2.9
*** Что бы TeXstudio нашло MiKTeX надо запустить студию после установки MiKTeX. Проверить нашелся ли MiKTeX можно так: TeXstudio -> Options -> Configure TeXstudio -> Commands и если команды проставлены автоматически - нашло. 
Если не нашло можно поробывать запустить MiKTeX 2.9/miktex/bin/x64/miktex-texworks.exe после этого запустить студию и проверить.
*** Для скачивания недостающих пакетов. При билде студия натктется на ненайденные пакеты и выдаст диалоговое окно с настройко репозитория откуда скачивать (если настройка не была произведена ранее); нужен интернет