## Git Commands


- Clone the repository: ``` git clone <URL>```
- Checkout to your branch: ```git checkout <my-branch>```
- Add your changes to the staging are: ```git add .```
- Commit your changes: ```git commit -m "commit message```
- Push your changes to remote: ```git push origin <my-branch>```
- Pull changes from remote to local: ```git pull origin <branch-name>```
- Create new branch: ```git branch <my-branch>```
- Create a new repository: ```git init <my-repo>```
- Create a new README: ```touch README.md```
- Add origin for the repository: ```git remote add origin <github link to repo>```
- Merge my branch into main branch:
    - ```git checkout main```
    - ```git merge --no-ff <my-branch> -m "updating main branch with my code"```
    - ```git push origin main```
- Merge main branch into my branch:
    - ```git checkout <my-branch>```
    - ```git merge --no-ff main -m "updating my-branch with main"```
    - ```git push origin <my-branch>```
    