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
6. git push -u origin master
7. git pull
8. git branch -a
9. git branch -delete <branch name>
10. git checkout -b develop master
11. git add * (add to develop branch)
12. git commit -m "add readme file" (add to develop branch)
13. git push -u origin develop (push to remote git develop branch)
14. git checkout master
15. git merge develop (merge changes done in develop branch into master branch)
16. git push -u origin master
//make changes in master, and need to synchronise this change to develop branch
//assume changes has alread been checkd in master branch
17. git checkout develop
18. git merge master (merge changed done in master branch into develop branch)
19. git push -u origin develop