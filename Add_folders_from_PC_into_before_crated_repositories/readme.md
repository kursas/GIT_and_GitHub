Microsoft Windows [Version 10.0.22621.1105]
(c) „Microsoft Corporation“. Visos teisės ginamos.

C:\Users\user name>git clone git@github.com:kursas/Pirmas_projektas_Python.git(Склонировать репозиторий)
Cloning into 'Pirmas_projektas_Python'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (5/5), done.

C:\Users\user name>d:

D:\>dir
 Volume in drive D is DATA
 Volume Serial Number is 7450-6EED

 Directory of D:\

2022-04-13  11:19    <DIR>          DUMENYS
2022-05-09  14:20    <DIR>          INSTALL
               0 File(s)              0 bytes
               2 Dir(s)  264 935 563 264 bytes free

D:\>cd DUMENYS

D:\DUMENYS>dir
 Volume in drive D is DATA
 Volume Serial Number is 7450-6EED

 Directory of D:\DUMENYS

2022-04-13  11:19    <DIR>          .
2022-04-13  11:21    <DIR>          DARIUS
               0 File(s)              0 bytes
               2 Dir(s)  264 935 563 264 bytes free

D:\DUMENYS>cd DARIUS

D:\DUMENYS\DARIUS>dir
 Volume in drive D is DATA
 Volume Serial Number is 7450-6EED

 Directory of D:\DUMENYS\DARIUS


2023-01-15  19:46    <DIR>          Desktop
2022-12-19  15:27    <DIR>          Documents
2023-01-15  19:43    <DIR>          Downloads
2022-12-19  15:27    <DIR>          Favorites
2022-12-19  15:27    <DIR>          Links
2022-12-19  15:27    <DIR>          Music
2022-12-19  15:27    <DIR>          Pictures
               0 File(s)              0 bytes
              7 Dir(s)  264 935 563 264 bytes free

D:\DUMENYS\DARIUS>cd Desktop

D:\DUMENYS\user name\Desktop>git clone git@github.com:kursas/Pirmas_projektas_Python.git(Склонировать репозиторий)
Cloning into 'Pirmas_projektas_Python'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
Receiving objects: 100% (5/5), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0

D:\DUMENYS\user name\Desktop>cd Pirmas_projektas_Python(Перейти в эту папку)

D:\DUMENYS\user name\Desktop\Pirmas_projektas_Python>git status(Проверить текущий статус)
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    .gitignore
        deleted:    LICENSE
        deleted:    README.md

Untracked files:(Добавляем в папку нужные файлы, удаляем ненужные)
  (use "git add <file>..." to include in what will be committed)
        pythoncode-tutorials/

no changes added to commit (use "git add" and/or "git commit -a")

D:\DUMENYS\DARIUS\Desktop\Pirmas_projektas_Python>git add .(Отследить изменения (точка в конце обязательна))
warning: in the working copy of 'pythoncode-tutorials/database/connect-to-remote-mysql-server/config.sql', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pythoncode-tutorials/database/connect-to-remote-mysql-server/remote_mysql_connector.py', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pythoncode-tutorials/database/mongodb-client/mongodb.py', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pythoncode-tutorials/web-scraping/youtube-video-downloader/youtube_downloader_ui.py', LF will be replaced by CRLF the next time Git touches it

D:\DUMENYS\user name\Desktop\Pirmas_projektas_Python>git commit -m .(Закоммитить изменения)
[main 45c07fb] .
 2625 files changed, 342250 insertions(+), 151 deletions(-)
 delete mode 100644 .gitignore
 delete mode 100644 LICENSE
 delete mode 100644 README.md
 create mode 100644 pythoncode-tutorials/database/connect-to-remote-mysql-server/config.sql
 create mode 100644 pythoncode-tutorials/web-scraping/youtube-video-downloader/youtube_downloader_cli.py
 create mode 100644 pythoncode-tutorials/web-scraping/youtube-video-downloader/youtube_downloader_ui.py
 create mode 100644 pythoncode-tutorials/web-scraping/youtube-video-downloader/youtubelogo.png

D:\DUMENYS\user name\Desktop\Pirmas_projektas_Python>git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:kursas/Pirmas_projektas_Python.git'

D:\DUMENYS\user name\Desktop\Pirmas_projektas_Python>git push -u origin main(#Залить изменения на гитхаб)
Enumerating objects: 2862, done.
Counting objects: 100% (2862/2862), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2719/2719), done.
Writing objects: 100% (2861/2861), 193.00 MiB | 3.68 MiB/s, done.
Total 2861 (delta 163), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (163/163), done.
remote: warning: See http://git.io/iEPt8g for more information.
remote: warning: File pythoncode-tutorials/machine-learning/nlp/text-classification/data/reviews.txt is 62.50 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB
remote: warning: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
To github.com:kursas/Pirmas_projektas_Python.git
   ea19e83..45c07fb  main -> main
branch 'main' set up to track 'origin/main'.

D:\DUMENYS\user name\Desktop\Pirmas_projektas_Python>
#http://studyjavascript.blogspot.com/2017/10/github.html

