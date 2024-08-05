## Git Commands


- Clone the repository:<br>
``` git clone <URL>```<br>

- Checkout to your branch: <br>
```git checkout <my-branch>```<br>

- Add your changes to the staging are: <br>
```git add .```<br>

- Commit your changes: <br>
```git commit -m "commit message```<br>

- Push your changes to remote: <br>
```git push origin <my-branch>```<br>

- Pull changes from remote to local: <br>
```git pull origin <branch-name>```<br>

- Create new branch: <br>
```git branch <my-branch>```<br>

- Create a new repository: <br>
```git init <my-repo>```<br>

- Create a new README: <br>
```touch README.md```<br>

- Add origin for the repository: <br>
```git remote add origin <github link to repo>```<br>

- Merge my branch into main branch:<br>
    - ```git checkout main```
    - ```git merge --no-ff <my-branch> -m "updating main branch with my code"```
    - ```git push origin main```

- Merge main branch into my branch:<br>
    - ```git checkout <my-branch>```
    - ```git merge --no-ff main -m "updating my-branch with main"```
    - ```git push origin <my-branch>```
