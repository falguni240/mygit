pract 2 - 

IMRD@IMRDCOMP84 MINGW64 ~/Desktop
$ git config --global user.name "Falguni Bhavsar"

IMRD@IMRDCOMP84 MINGW64 ~/Desktop
$ git config --global user.email "falgunibhavsar310@gmail.com"

IMRD@IMRDCOMP84 MINGW64 ~/Desktop
$ git clone https://github.com/falguni240/mygit.git
Cloning into 'mygit'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

IMRD@IMRDCOMP84 MINGW64 ~/Desktop
$ cd mygit

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (master)
$ git init
Reinitialized existing Git repository in C:/Users/IMRD/Desktop/mygit/.git/

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (master)
$ git checkout -b login
Switched to a new branch 'login'

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (login)
$ echo "welcome" > wel.txt

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (login)
$ git add wel.txt
warning: in the working copy of 'wel.txt', LF will be replaced by CRLF the next
time Git touches it

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (login)
$ git commit -m "welcome to this file"
[login f90b874] welcome to this file
 1 file changed, 1 insertion(+)
 create mode 100644 wel.txt

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (login)
$ git push origin login
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'login' on GitHub by visiting:
remote:      https://github.com/falguni240/mygit/pull/new/login
remote:
To https://github.com/falguni240/mygit.git
 * [new branch]      login -> login

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (login)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (master)
$ git pull origin master
From https://github.com/falguni240/mygit
 * branch            master     -> FETCH_HEAD
Already up to date.

IMRD@IMRDCOMP84 MINGW64 ~/Desktop/mygit (master)
$
