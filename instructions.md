# Steps to work with Github

* Step 1: Clone the repository in your local machine using
```bash 
git clone https://github.com/ranbala000/ctp-loanme.git
```
* Step 2: Switch to branch ‘pre-final’ using 
```bash
git checkout pre-final
```
* Step 3: Create a new branch to work on your tasks independently using 
```bash
git –b checkout <branch-name>
```
* Step 4: After completing your work on your local machine, push it your independent branch using 
```bash
git push origin <branch-name>
```
* Step 5: Then push it to pre-final branch so that all our changes are merged using 
```bash
git push origin <branch-name>:pre-final
```
* Step 6: Incase you were working on the github website in your branch or to access the updated files use
```bash
# branch could be your independent branch or pre-final
git pull origin <branch>
```


## References  
* If you need more assistance you can checkout http://rogerdudler.github.io/git-guide/ or https://try.github.io or https://github.com/medgardo/ctp2016/blob/master/guides/git.md

## Notes
* For first version, we do not have any over lapping files to work on so the above steps will be enough.
* I have added the branch pre-final based on our TA, Tom's suggestion. After we all agree upon changes commited to pre-final, I will commit to the master.
