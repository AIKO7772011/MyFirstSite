or create a new repository on the command line
echo "# MyFirstSite" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/AIKO7772011/MyFirstSite.git
git push -u origin master


Это вводим мы с Айкошей
1 шаг
D:\HowTO\Create_site_on_GITHUB\MyFirstSite>git init

2
D:\HowTO\Create_site_on_GITHUB\MyFirstSite>git add .

3
D:\HowTO\Create_site_on_GITHUB\MyFirstSite>git commit -m "My site"
[master (root-commit) 8c37d23] My site
 3 files changed, 128 insertions(+)
 create mode 100644 ReadMe.TXT
 create mode 100644 index.html
 create mode 100644 main.css

 4
 D:\HowTO\Create_site_on_GITHUB\MyFirstSite>git remote add origin https://github.com/AIKO7772011/MyFirstSite.git


 5
 D:\HowTO\Create_site_on_GITHUB\MyFirstSite>git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.39 KiB | 284.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/AIKO7772011/MyFirstSite.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.


Using Git with VS Code and Github
https://www.youtube.com/watch?v=9cMWR-EGFuY


пример сайта отсюда
https://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_theme_band_complete&stacked=h


After every changes you can run these two commands in cmd line:
git commit -m "first commit"
git push --force



тоже самое можно сделать 
шаг 1 
нажать CTRL+Shift+P
шаг 2
набрать 
git commit 
после надо ввести коментарии для комита
шаг 3
нажать CTRL+Shift+P
набрать 
git push


тут есть шаблоны для сайтов
https://www.w3schools.com/bootstrap/bootstrap_templates.asp




https://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_theme_me_complete&stacked=h
