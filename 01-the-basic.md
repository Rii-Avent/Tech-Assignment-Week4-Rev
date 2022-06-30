1. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ mkdir git-basic
2. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ cd git-basic
3. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ touch first.txt
4. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git init
Initialized empty Git repository in /mnt/c/Users/PCMANPASI/git-basic/.git/
5. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git add first.txt
6. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git commit -m "adding first.txt"
[master (root-commit) 404577f] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt
 7. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git log
commit 404577f427e967ff857c5f0597504750ab5e6bc4 (HEAD -> master)
Author: Rizkiihsanqilabi <Rizkiihsanqilabi@gmail.com>
Date:   Tue Jun 28 19:28:13 2022 +0700

    adding first.txt
8. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ touch second.txt
9. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git add second.txt
10. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git commit -m "adding second.txt"
[master 445a925] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt
11. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ rm first.txt
12. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git add .
13. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git commit -m "remove first.txt"
[master 090df7a] remove first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt
 14. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/git-basic$ git log
commit 090df7abffbc459ab2c94487621107c98be65727 (HEAD -> master)
Author: Rizkiihsanqilabi <Rizkiihsanqilabi@gmail.com>
Date:   Tue Jun 28 19:37:14 2022 +0700

    remove first.txt

commit 445a92513c7ba577f064d482a13f534427920c46
Author: Rizkiihsanqilabi <Rizkiihsanqilabi@gmail.com>
Date:   Tue Jun 28 19:30:43 2022 +0700

    adding second.txt

commit 404577f427e967ff857c5f0597504750ab5e6bc4
Author: Rizkiihsanqilabi <Rizkiihsanqilabi@gmail.com>
Date:   Tue Jun 28 19:28:13 2022 +0700

    adding first.txt