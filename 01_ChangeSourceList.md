Debian-101
==========

[APT HOWTO](https://www.debian.org/doc/manuals/apt-howto/index.zh-tw.html#contents)
[APT 工具](https://debian-handbook.info/browse/zh-TW/stable/apt.html)

change apt source list
----------------------

  [root@debian ~]$ vim /etc/apt/sources.list
  deb http://ftp.tw.debian.org/debian buster main
  deb http://ftp.tw.debian.org/debian buster-updates main
  deb http://security.debian.org/debian-security/ buster/updates main
  
 update & upgrade
------------------

  [root@debian ~]$ apt-get update
  [root@debian ~]$ apt-get upgrade
