diskpublish
=============
Tool to publish files on Yandex.Disk (http://disk.yandex.ru).
-------------

Setting up:
1. Put diskpublish to /usr/bin
2. Create file .diskpublish.conf in your home directory.
3. Fill it in this way:
        LOGIN=your_login
        PASS=your_pass

Usage: 
        diskpublish path_to_some_file

This will put a file "path_to_some_file" to Yandex.Disk "public" directory and give a public url to stdout.
