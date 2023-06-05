# final_assignment


ubuntu@ubuntu:~$ mkdir Videos/Watched
ubuntu@ubuntu:~$ ls -R Videos
Videos:
Watched

Videos/Watched:
ubuntu@ubuntu:~$ ^C
ubuntu@ubuntu:~$ cd Documents
ubuntu@ubuntu:~/Documents$ mkdir ProjectX PProjectY
ubuntu@ubuntu:~/Documents$ ls
PProjectY  ProjectX
ubuntu@ubuntu:~/Documents$ mkdir -p Thesis/Chapter1 Thesis/Chapter2 Thesis/Chapter3
ubuntu@ubuntu:~/Documents$ cd
ubuntu@ubuntu:~$ ls -R Videos Documents
Documents:
PProjectY  ProjectX  Thesis

Documents/PProjectY:

Documents/ProjectX:

Documents/Thesis:
Chapter1  Chapter2  Chapter3

Documents/Thesis/Chapter1:

Documents/Thesis/Chapter2:

Documents/Thesis/Chapter3:

Videos:
Watched
ubuntu@ubuntu:~$ mkdir Videos/Watched
ubuntu@ubuntu:~$ ls -R Videos
Videos:
Watched

Videos/Watched:
ubuntu@ubuntu:~$ ^C
ubuntu@ubuntu:~$ cd Documents
ubuntu@ubuntu:~/Documents$ mkdir ProjectX PProjectY
ubuntu@ubuntu:~/Documents$ ls
PProjectY  ProjectX
ubuntu@ubuntu:~/Documents$ mkdir -p Thesis/Chapter1 Thesis/Chapter2 Thesis/Chapter3
ubuntu@ubuntu:~/Documents$ cd
ubuntu@ubuntu:~$ ls -R Videos Documents
Documents:
PProjectY  ProjectX  Thesis

Documents/PProjectY:

Documents/ProjectX:

Documents/Thesis:
Chapter1  Chapter2  Chapter3

Documents/Thesis/Chapter1:

Documents/Thesis/Chapter2:

Documents/Thesis/Chapter3:

Videos:
Watched

Videos/Watched:

Videos/Watched:
![Screenshot from 2023-06-05 02-13-41](https://github.com/4924ai/final_assignment/assets/115356787/494ca4a4-06ea-41ed-9eba-f9545458b11a)
ubuntu@23:~$ cd Videos
ubuntu@23:~/Videos$ cp blockbuster1.ogg blockbuster3.ogg
cp: cannot stat 'blockbuster1.ogg': No such file or directory
ubuntu@23:~/Videos$ ls -l
total 4
drwxrwxr-x 2 ubuntu ubuntu 4096  6월  5 12:07 Watched
ubuntu@23:~/Videos$ 
ubuntu@23:~/Videos$ cd ../Documents
ubuntu@23:~/Documents$ cp thesis_chapter1.odf thesis_chapter2.odf Thesis ProjectX
cp: cannot stat 'thesis_chapter1.odf': No such file or directory
cp: cannot stat 'thesis_chapter2.odf': No such file or directory
cp: -r not specified; omitting directory 'Thesis'
ubuntu@23:~/Documents$ cd Videos
bash: cd: Videos: No such file or directory
ubuntu@23:~/Documents$ cp /etc/hostname
cp: missing destination file operand after '/etc/hostname'
Try 'cp --help' for more information.
ubuntu@23:~/Documents$ cat hostname
cat: hostname: No such file or directory
ubuntu@23:~/Documents$ cd ../Documents
ubuntu@23:~/Documents$ cp thesis_Chapter1.odf thesis_chapter2.odf Thesis ProjectX
cp: cannot stat 'thesis_Chapter1.odf': No such file or directory
cp: cannot stat 'thesis_chapter2.odf': No such file or directory
cp: -r not specified; omitting directory 'Thesis'
ubuntu@23:~/Documents$ ls Thesis ProjectX
ProjectX:

Thesis:
Chapter1  Chapter2  Chapter3

![Screenshot from 2023-06-05 12-21-07](https://github.com/4924ai/final_assignment/assets/115356787/a69b9e2d-1470-4e6b-85a5-33247f68bb10)

ubuntu@23:~$ cd Documents
ubuntu@23:~/Documents$ cp -r Thesis ProjectX
ubuntu@23:~/Documents$ ls -R ProjectX
ProjectX:
Thesis

ProjectX/Thesis:
Chapter1  Chapter2  Chapter3

ProjectX/Thesis/Chapter1:

ProjectX/Thesis/Chapter2:

ProjectX/Thesis/Chapter3:
ubuntu@23:~/Documents$ 

buntu@23:~/Documents$ cd ..
ubuntu@23:~$ cp /etc/hostname
cp: missing destination file operand after '/etc/hostname'
Try 'cp --help' for more information.
ubuntu@23:~$ cp/etc/hostname
bash: cp/etc/hostname: No such file or directory
ubuntu@23:~$ cat hostname
cat: hostname: No such file or directory
ubuntu@23:~$ cd Documents
ubuntu@23:~/Documents$ cp -r Thesis ProjectX
ubuntu@23:~/Documents$ ls -R ProjectX
ProjectX:
Thesis

ProjectX/Thesis:
Chapter1  Chapter2  Chapter3

ProjectX/Thesis/Chapter1:

ProjectX/Thesis/Chapter2:

ProjectX/Thesis/Chapter3:
ubuntu@23:~/Documents$ ls -l thesis*
ls: cannot access 'thesis*': No such file or directory
ubuntu@23:~/Documents$ mkdir thesis
ubuntu@23:~/Documents$ ls -l thesis*
total 0
ubuntu@23:~/Documents$ mv thesis_chapter2.odf thesis_chapter2_reniewed.odf
mv: cannot stat 'thesis_chapter2.odf': No such file or directory
ubuntu@23:~/Documents$ ls -l thesis*
total 0
ubuntu@23:~/Documents$ ls Thesis/chapter1
ls: cannot access 'Thesis/chapter1': No such file or directory
ubuntu@23:~/Documents$ 
ubuntu@23:~/Documents$ mv thesis_chapter1.odf Thesis/Chapter1
mv: cannot stat 'thesis_chapter1.odf': No such file or directory
ubuntu@23:~/Documents$ ls Thesis/Chapter1
ubuntu@23:~/Documents$ ls -l thesis*
total 0
ubuntu@23:~/Documents$ ls -l thesis*
total 0
ubuntu@23:~/Documents$ rm thesis_chapter2_reniewed.odf
rm: cannot remove 'thesis_chapter2_reniewed.odf': No such file or directory
ubuntu@23:~/Documents$ ls -l thesis*
total 0
ubuntu@23:~/Documents$ rm Thesis/Chapter1
rm: cannot remove 'Thesis/Chapter1': Is a directory
ubuntu@23:~/Documents$ ls -R Thesis
Thesis:
Chapter1  Chapter2  Chapter3

Thesis/Chapter1:

Thesis/Chapter2:

Thesis/Chapter3:
ubuntu@23:~/Documents$ 

![Screenshot from 2023-06-05 12-32-03](https://github.com/4924ai/final_assignment/assets/115356787/5206eecf-da83-49f8-b9a6-ae4708a42091)

ubuntu@23:~$ ls -l /tmp
total 60
-rw------- 1 ubuntu ubuntu    0  6월  5 20:11 config-err-VWJv5w
-rw-rw-r-- 1 ubuntu ubuntu   67  6월  5 20:13 saved-output
drwx------ 2 root   root   4096  6월  5 20:10 snap-private-tmp
drwx------ 2 ubuntu ubuntu 4096  6월  5 20:11 ssh-0e1DiSyNwNMU
drwx------ 3 root   root   4096  6월  5 20:11 systemd-private-45f0e4a7778a4119b1b93766e5f98430-colord.service-UF3CJi
drwx------ 3 root   root   4096  6월  5 22:15 systemd-private-45f0e4a7778a4119b1b93766e5f98430-fwupd.service-mOPPhf
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-ModemManager.service-8dEsvj
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-switcheroo-control.service-BmjAXf
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-logind.service-3VAmGh
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-resolved.service-jjdEgh
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-timesyncd.service-20Rr9f
drwx------ 3 root   root   4096  6월  5 20:11 systemd-private-45f0e4a7778a4119b1b93766e5f98430-upower.service-EBjvQi
-rw-rw-r-- 1 ubuntu ubuntu   67  6월  5 20:13 ten-last-changed-files
drwx------ 2 ubuntu ubuntu 4096  6월  5 20:11 tracker-extract-files.1000
drwxrwxrwt 2 root   root   4096  6월  5 20:10 VMwareDnD
drwx------ 2 root   root   4096  6월  5 20:10 vmware-root_731-4248811549
ubuntu@23:~$ 

ubuntu@23:~$ ls -l /tmp
total 64
-rw------- 1 ubuntu ubuntu    0  6월  5 20:11 config-err-VWJv5w
-rw-rw-r-- 1 ubuntu ubuntu   67  6월  5 20:13 saved-output
drwx------ 2 root   root   4096  6월  5 20:10 snap-private-tmp
drwx------ 2 ubuntu ubuntu 4096  6월  5 20:11 ssh-0e1DiSyNwNMU
drwx------ 3 root   root   4096  6월  5 20:11 systemd-private-45f0e4a7778a4119b1b93766e5f98430-colord.service-UF3CJi
drwx------ 3 root   root   4096  6월  5 22:15 systemd-private-45f0e4a7778a4119b1b93766e5f98430-fwupd.service-mOPPhf
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-ModemManager.service-8dEsvj
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-switcheroo-control.service-BmjAXf
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-logind.service-3VAmGh
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-resolved.service-jjdEgh
drwx------ 3 root   root   4096  6월  5 20:10 systemd-private-45f0e4a7778a4119b1b93766e5f98430-systemd-timesyncd.service-20Rr9f
drwx------ 3 root   root   4096  6월  5 20:11 systemd-private-45f0e4a7778a4119b1b93766e5f98430-upower.service-EBjvQi
drwx------ 2 ubuntu ubuntu 4096  6월  5 22:16 Temp-a10731f2-2916-4fbc-a9f8-f6bb9f4db4d1
-rw-rw-r-- 1 ubuntu ubuntu   67  6월  5 20:13 ten-last-changed-files
drwx------ 2 ubuntu ubuntu 4096  6월  5 20:11 tracker-extract-files.1000
drwxrwxrwt 2 root   root   4096  6월  5 20:10 VMwareDnD
drwx------ 2 root   root   4096  6월  5 20:10 vmware-root_731-4248811549
ubuntu@23:~$ 

ubuntu@23:~$ id
uid=1000(ubuntu) gid=1000(ubuntu) groups=1000(ubuntu),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),120(lpadmin),133(lxd),134(sambashare)
ubuntu@23:~$ 
ubuntu@23:~$ ps au
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
ubuntu      1004  0.0  0.1 173952  6848 tty2     Ssl+ 22:10   0:00 /usr/lib/gdm
ubuntu      1011  0.9  1.9 305668 76456 tty2     Sl+  22:10   0:07 /usr/lib/xor
ubuntu      1110  0.0  0.3 200728 15468 tty2     Sl+  22:10   0:00 /usr/libexec
ubuntu      1690  0.0  0.1  20552  5156 pts/0    Ss   22:10   0:00 bash
ubuntu      1735  0.0  0.0  18376  2360 pts/0    T    22:10   0:00 less
ubuntu      1813  0.0  0.0  18376  2428 pts/0    T    22:13   0:00 less
ubuntu      2912  0.0  0.0  21428  3612 pts/0    R+   22:22   0:00 ps au
ubuntu@23:~$ 

Week_13
