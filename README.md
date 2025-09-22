# Every Thing About Git

## Important Orders in Git

1) using this link to make new Maven Project(mvn).

```
mvn archetype:generate "-DgroupId=at.fhj.msd" "-DartifactId=LearningGit" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.5" "-DinteractiveMode=false"
```

2) after Creating the folder go init and use``` git init ```

3) give ``` touch .gitignore ``` to make the .gitignore file .

4) add all this orders in .gitignore

    ````
    /target/
    target/
    .DS_Store
    .idea/
    .vscode/
    *.class
    logs/
    *.log
    Src/main/resources/log4j2.xml
    *.iml
    .mvn/
    *.pdf
    *.html
    target/classes/at/fhj/msd

5) Make new Repository in your own GitHub

6) add this orders in folge

```
# git remote add clone https://github.com/username/RepoNAme.git
# git add README.md
# git commit -m "add readme.md"
# git add .gitignore
# git commit -m "add .gitignore"

# git push origin main
````

7) now we have verbinde between our reposotory on github and workplace 

8. to making new branch all you need is 

````
# git branch     // to know in which branch am i
# git checkout -b name  // to make new branch
# git checkout  main  //   to go back to branch  main or any other branch
````

9) After finish working on this branch make git add and git commit and then go to main branch 
if every thing is ok make
````
git merge branchName
git push origin main

