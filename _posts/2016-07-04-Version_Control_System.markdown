---
layout: post
title:  "Amisha and Gagan - Version Control"
date:   2016-07-04 11:45:00 +0530
author: "Deepti Sharma"
categories: presentation
---


**Version Control System (By Amisha Budhiraja and Gagandeep)**

Version control system help a software team manage changes to source code over time.
There are two types of Version Control System:

- Centralized Version Control System. Eg: Perforce, CVS (Concurrent Version Control System)

- Distributed Version Control System. Eg: Git, Bazaar 

**Q1. What is CVS, SVN?**


**Basic diference between Git and Github**

Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories. So they are not the same thing: Git the tool, GitHub the service for projects that use Git.

There are various control systems like Bitbucket, Gitlab etc.

**Making new local repository**

*Some of the commands are:*

- Mkdir test

- cd test

- git init

- touch new.txt

And so on ..
 
You can also use **git clone** command

**Q2. Can we push a repository from local system without having any remote repository?**

**Basic difference between git add and git commit:**

Git add is just the index of a file but git commit is actual data which is present under that index number.

- git status tells about the status of the repository.

- git remote add red http://github.com/amisha2016/invention

Above command gives shortcut named red instead of writing url
git stash command is used when we had added a file but hadn’t commit it then we can save it in another place where we can refer afterwards and can move to other repository.

**Q3. How to git stash a particular file?**

- git log tells about the recent commits.

- git revert is used for undo changes after push command.

- git reset : If you do changes locally and didn’t push yet and you apply reset it will undo all the changes and didn’t show any changes on git hub, repo remains same.

-  git branch commands show all branches.

**There are 2 modes:**

- **Hard:** It removes the commitment entry from the index and actual commit stage.

- **Soft:** It removes only the actual commitment


**Q4. How to change the message if we had written wrong message accidently?**

unanswerd

### Command examples

```bash
git clone https://github.com/frappe/bench /home/sdc/.bench --depth 1 --branch master
git status
cat .git/config 
git fetch
git branch
git status
git pull
joe .git/config 
git add erpnext/education/web_form/student_applicant/student_applicant.json 
git status
git commit -m "Student enabled to apply for admission without login"
git push
git config --global --edit
git commit --amend --reset-author
```

## More

```sh
mosh hsrai@erp.gndec.ac.in
sudo ufw allow 60000:61000/udp
sudo ufw disable
sudo ufw enabled
sudo ufw enable
sudo ufw status numbered
sudo ufw status numbered | grep 465
sudo ufw allow 465/tcp
sudo apt install mlocate
sudo chown hsrai -R /home/hsrai
cd
git clone https://github.com/frappe/bench /home/sammy/.bench --depth 1 --branch master
git clone https://github.com/frappe/bench ~/.bench --depth 1 --branch master
sudo pip3 install -e ~/.bench
bench init ~/frappe-bench --frappe-path https://github.com/GreatDevelopers/erpnext --frappe-branch version-13 --python python3
bench init ~/frappe-bench --frappe-path https://github.com/frappe/frappe --frappe-branch version-13 --python python3
cd frappe-bench/
bench get-app ERPNext https://github.com/GreatDevelopers/erpnext --branch version-13
bench setup requirements
bench new-site erp.ukiericoncretecongress.com --admin-password 'erpUCC' --mariadb-root-username hsrai --mariadb-root-password 'hsraiDB' 
bench drop-site erp.ukiericoncretecongress.com
bench drop-site erp.ukiericoncretecongress.com --force 
bench   --mariadb-root-username hsrai drop-site  erp.ukiericoncretecongress.com --force 
sudo mysql -u root -p
sudo bench  drop-site  erp.ukiericoncretecongress.com --force 
sudo mysql_secure_installation
mysql -uroot -p
mysql -u hsrai -p
sudo mysql_secure_installation
mysql -uroot -p
sudo service mysql restart
sudo bench  drop-site  erp.ukiericoncretecongress.com --force 
bench new-site erp.ukiericoncretecongress.com --admin-password 'erpUCC' --mariadb-root-username hsrai --mariadb-root-password 'hsraiDB' 
bench start
cd sites/
joe common_site_config.json 
cd -
bench start
tmux new -s hsr
tmux ls
tmux a -t hsr
sudo snap install certbot --classic
sudo certbot --nginx

bench init rai-bench
cd rai-bench/
sudo snap install tree
tree .
tree -d .
tree -d -L 1 . | more
bench find .
bench new-app library_management
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install 14
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] &amp;&amp; \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] &amp;&amp; \. "$NVM_DIR/bash_completion" 
nvm install 14
node -v
npm install -g yarn
pip3 install frappe-bench
which bench
echo $PATH
joe .bashrc 
source ~/.bashrc
bench --version
bench init rai-bench
cd rai-bench/
bench start
bench find .
bench new-app library_management
bench start
/etc/init.d/redis-server status
/etc/init.d/redis-server stop
bench start
sudo service nginx stop
sudo service nginx start
bench start
bench start
sudo service supervisor stop
w3m http://erp.gndec.ac.in:8001/
cd rai-bench/
cd sites/
cp ../../frappe-bench/sites/REMcurrentsite.txt .
mv REMcurrentsite.txt currentsite.txt 
w3m http://erp.gndec.ac.in:8001/
w3m http://103.66.206.232:8001/
cd library_rai/
cd .git/
cat config 
cd ..
git status
git branch
git add . 
git status
git add -A
sudo apt  install gitsome
gh repo create
sudo pip install pyOpenSSL --upgrade
gh configure
joe ~/.gitsomeconfig 
cd library_rai
cd
cd tmp/
mkdir Test
cd Test/
mkdir A
touch a.text b.text A/c.csv
git init
git add . 
git status
git branch
git commit -m "initial commit"
git config --global user.email "hardeep.rai@gmail.com"
git config --global user.name "hsrai"
git commit -m "initial commit"
git status
joe .git/config 
git push --set-upstream origin master
git fetch
git status

echo "# Test1" &gt;&gt; README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hsrai/Test1.git
git push -u origin main

git remote add origin https://github.com/hsrai/Test1.git
git branch -M main
git push -u origin main
```
