1. Removing .gitcompletely deletes all local Git history in that folder(backup first)
```bash
rm -rf .git
```
2. To see which remote github repo linked with the local repo
```bash
git remote -v
```
3. Fetch ALL latest branches/changes from GitHub (safe, doesn't change your files)
```bash
git fetch origin
```
4. origin: Your remote (GitHub repo). main: The branch on GitHub to pull from. Git fetches new changes from GitHub + merges them into your local main.
```bash
git pull origin main
```
5. Switch auth active account 
```bash
gh auth switch
```
6. add the remote manually:
```bash
git remote add origin git@github.com:your-username/my-awesome-project.git
```