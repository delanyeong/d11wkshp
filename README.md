# Workshop 11 Instruction

### Maven Commands
1. mvnw
2. mvnw compile
3. mvnw package
4. mvnw clean package
5. mvnw clean
6. mvnw clean package
7. mvnw clean package spring-boot:run
8. mvnw spring-boot:run

### Git Commands
1. git init
2. git remote add origin https://github.com/<username>/<projectname>.git
3. git add . or git add *
4. git status
5. git commit -m "commit message details"
6. git push -u origin main
7. git pull
8. git branch -a
9. git branch -delete <branch name>
10. git checkout -b develop main
11. git add * (add to develop branch)
12. git commit -m "add readme file" (add to develop branch)
13. git push -u origin develop (push to remote git develop branch)
14. git checkout main
15. git merge develop (merge changes done in develop branch into main branch)
16. git push -u origin main
//make changes in main, and need to synchronise this change to develop branch
//assume changes has alread been checkd in main branch
17. git checkout develop
18. git merge main (merge changed done in main branch into develop branch)
19. git push -u origin develop

### Deploy to Heroku from Main branch always
1. git branch 
2. git checkout main
3. heroku login
4. heroku apps:create
5. git remote -v //to check if heroku can see your repo
6. git push -u heroku main