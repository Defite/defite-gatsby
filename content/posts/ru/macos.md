---
templateKey: blog-post
category: notes
path: "/notes/macos-multiple-zip-archives"
title: MacOS и сжатие в отдельные архивы
excerpt: ''
date: 2020-09-21T21:00:00Z
published: true
coverImg: "/uploads/compress-files-archive-utility.png"

---
Сегодня столкнулся с необходимостью сжать несколько файлов в раздельные архивы. Обычно я выделяю нужные мне файлы и в контекстном меню Finder или ForkLift выбираю "Сжать объекты (n)". В таком случае дефолтная "Утилита архивирования" создаст один архив со всеми выделенными мною файлами. Это удобно, но не всегда.  
Для того, чтобы сжать каждый файл (папку на верхнем уровне) в свой отдельный архив, нужно проделать несколько шагов:

1. Открыть "Утилита архивирования"
2. Зайти в "Настройки"
3. В поле "Использовать формат архива" выбрать "Zip-архив"  
   ![](/uploads/archive_utility_-preferences.png)
4. После перетаскивания файлов или папок на иконку утилиты в доке в файловой системе будут созданы отдельные архивы. Кстати, из контекстного меню пропадет пункт "Сжать объекты". Для одиночного файла этот пункт останется.