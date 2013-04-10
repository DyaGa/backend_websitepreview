backend_websitepreview
=======================

![backend_websitepreview example](http://gyazo.com/918fd1cb78bb9e796fe1f8910a0b6bfc.png)

en - english
------------

Adds a backend website preview link to the header. The link is just opens a website in a new window without using standart Contao preview module.

ru - русский
------------

Добавляет в заголовок панели управления ссылку для просмотра сайта в новом окне. В отличии от стандартного модуля предпросмотра, сайт открывается просто в новом окне.


Changelog
================================

2.1.0
 - add: ukrainian language file
 - upd: update htaccess file in assets folder
 - fix: minor fixes

2.0.0
 - add: make compatibility with Contao 3.x
 - add: minimized js version and load it
 - fix: improve logic in js file

1.1.0

 - add: if favicon.ico file exists in TL_ROOT folder then it used as website preview link icon
 - fix: bug in Opera 11.61: relative script path should start with '\' sign
 - some fixes