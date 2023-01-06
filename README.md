# otus_lesson_1
**Обновить ядро из репозитория**

ashtrey@ashtrey-Lenovo-V580c:~$ uname -a
> Linux ashtrey-Lenovo-V580c 5.15.0-56-generic #62~20.04.1-Ubuntu SMP Tue Nov 22 21:24:20 UTC 2022 x86_64 x86_64 x86_64 GNU/Linux

ashtrey@ashtrey-Lenovo-V580c:~$ uname -r
> 5.15.0-56-generic

ashtrey@ashtrey-Lenovo-V580c:~$ ls -l /boot/ | grep vmlinuz*
```
lrwxrwxrwx 1 root root       25 –і–µ–Ї 30 14:11 vmlinuz -> vmlinuz-5.15.0-56-generic
-rw-r--r-- 1 root root 11431744 –і–µ–Ї 30 13:28 vmlinuz-5.15.0-46-generic
-rw------- 1 root root 11447712 –љ–Њ—П 22 23:32 vmlinuz-5.15.0-56-generic
lrwxrwxrwx 1 root root       25 –і–µ–Ї 30 14:11 vmlinuz.old -> vmlinuz-5.15.0-46-generic
```

ashtrey@ashtrey-Lenovo-V580c:~$ uname -r
>5.19.17-051917-generic

ashtrey@ashtrey-Lenovo-V580c:~$ ls -l /boot/ | grep vmlinuz*
```
lrwxrwxrwx 1 root root       30 —П–љ–≤  2 13:37 vmlinuz -> vmlinuz-5.15.86-051586-generic
-rw-r--r-- 1 root root 11431744 –і–µ–Ї 30 13:28 vmlinuz-5.15.0-46-generic
-rw------- 1 root root 11447712 –љ–Њ—П 22 23:32 vmlinuz-5.15.0-56-generic
-rw------- 1 root root 11533472 –і–µ–Ї 31 16:33 vmlinuz-5.15.86-051586-generic
-rw------- 1 root root 11979136 –Њ–Ї—В 24 12:39 vmlinuz-5.19.17-051917-generic
lrwxrwxrwx 1 root root       30 —П–љ–≤  2 13:37 vmlinuz.old -> vmlinuz-5.19.17-051917-generic
```
