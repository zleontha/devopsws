# devopsws
## Hello world
* The very first commands for the master (me) of this repo
1. git init -- create local repository
1. git add README.md -- add file named 'README.md' to local repository's index
1. git commit -m "first commit" -- commit file named 'README.md' to local repository

## Config global user (me)
* git config --global user.email "zleon.mail@gmail.com"
* git config --global user.name "ZLeon"

## working with remote repository
1. git remote add origin https://github.com/zleontha/devopsws.git
1. git push -u origin master

## status command 
* git status
* git help -m -- man help

## git ignore
1. create file '.gitignore'
2. add line of '*.tmp' and 'build/test.txt'
3. git ls-files --other --ignored --exclude-standard <for checking if the ignored files are correct or not>

## docker run
docker run --name some-nginx \
-v C:\Users\Tranning\Downloads\devops\html:/usr/share/nginx/html:ro \ <ro = read only>
-p 80:80 \
-d nginx