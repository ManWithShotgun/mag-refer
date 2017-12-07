В главном файле надо  указать путь к стилям так:
\documentclass[12pt,a4paper%,openbib
]{`styles/report`}

А и самого `report` надо указывать относительно главного файла `\usepackage{styles/axodraw}`

* Diff от оригинала*
1. `\usepackage[utf8x]{inputenc}` было: `\usepackage[cp1251]{inputenc}`