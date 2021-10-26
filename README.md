Лабораторная работа №4
Команды:
-git --version
-git config --global user.name "Kate"
-git config --global user.email ekaterinakalmykova213@gmail.com
-mkdir my_lab
-cd my_lab
-git init
-git status 
-echo "Kate" > name.txt 
-echo "Kalmykova" > surname.txt 
-echo "Lbd-21" > group.txt
-git status
-git add . 
-git status 
-git commit -m 'my first commit'
-git status
-git remote add origin https://github.com/Kate3010/my_lab.git
-git push -u origin master
