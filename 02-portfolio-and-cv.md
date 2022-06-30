1. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ mkdir Rizki_Ihsan_Qilabi
2. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > README.md
Halo perkenalkan aku halaman utama
3. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git init
Initialized empty Git repository in /mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi/.git/
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "First Commit"
[master (root-commit) a5112f2] First Commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
4. Hello World rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > README.md
Hello World
5. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat README.md
Hello World
6. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git checkout 9a7c28207af395683802580a3bd4164fd58fa4e4
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  e44dd9c Change to Hello World

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> e44dd9c

HEAD is now at 9a7c282 First Commit
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat README.md
Halo perkenalkan aku halaman utama
7. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git branch cv
8. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git checkout cv
Switched to branch 'cv'
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > cv.txt
Ini adalah cv
9. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add cv.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "Initial cv"
[cv b5f552f] Initial cv
 1 file changed, 1 insertion(+)
 create mode 100644 cv.txt
10. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "Menambahkan Perusahaan Minyak Bumi"
[cv 045f9bd] Menambahkan Perusahaan Minyak Bumi
 1 file changed, 1 insertion(+)
 rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
Perusahaan Batu Bara
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
Perusahaan Batu Bara
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "Menambahkan Perusahaan Batu Bara"
[cv 1a26c91] Menambahkan Perusahaan Batu Bara
 1 file changed, 1 insertion(+)
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
Perusahaan Batu Bara
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
Perusahaan Batu Bara
Perusahaan Logam Mulia
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat cv.txt
Ini adalah cv
Perusahaan Minyak Bumi
Perusahaan Batu Bara
Perusahaan Logam Mulia
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "Menambahkan Perusahaan Logam Mulia"
[cv 0a225aa] Menambahkan Perusahaan Logam Mulia
 1 file changed, 2 insertions(+), 1 deletion(-)
11. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git checkout master
Switched to branch 'master'
12. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ cat > README.md
Halo perkenalkan aku adalah halaman utama

Ini adalah update pertama pada branch
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git commit -m "update master pertama"
[master 2e59240] update master pertama
 1 file changed, 3 insertions(+), 1 deletion(-)
13. rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Rizki_Ihsan_Qilabi$ git merge cv
Merge made by the 'recursive' strategy.
 cv.txt | 4 ++++
 1 file changed, 4 insertions(+)
 create mode 100644 cv.txtr
