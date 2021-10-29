---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author: Разин Никита Андреевич НБИбд-402-18
institute: Российский Университет Дружбы Народов
date: 28 октября, 2021, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
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

## Теоретическое введение 

В UNIX-системах, кроме стандартных прав доступа, существуют также дополнительные или специальные атрибуты файлов, которые поддерживает файловая система. С помощью утилиты chattr можно управлять атрибутами

Установить атрибут i на файл

chattr +i file.txt

Посмотреть текущие атрибуты можно командой lsattr

lsattr file.txt 

----i---------- file.txt

## Цель лабораторной работы

Цель - получение практических навыков работы в консоли с расширенными атрибутами файлов.

## Задачи лабораторной работы

1. С пользователя root установить расширенный атрибут, a на файл /home/guest/dir1/file1, выполнить команды (mv, cat, echo), затем снять расширенный атрибут,a и повторить свои действия.
2. С пользователя root установить расширенный атрибут i на файл /home/guest/dir1/file1, выполнить команды (mv, cat, echo), затем снять расширенный атрибут i и повторить свои действия.
3. Сделать выводы.

## Результаты выполнения лабораторной работы

Я приобрел практические навыки работы в консоли с расширенными атрибутами файлов «а» и «i».