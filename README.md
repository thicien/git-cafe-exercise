# git-cafe-exercise
## Bundle-6

### Exercise-2

```bash
PS C:\git-exercise\git-cafe-exercise> git checkout -b bug/fix
Switched to a new branch 'bug/fix'
PS C:\git-exercise\git-cafe-exercise> git checkout bug/fix
Already on 'bug/fix'
PS C:\git-exercise\git-cafe-exercise> git add .
PS C:\git-exercise\git-cafe-exercise> git commit -m "index-4.html is changed"
[bug/fix 5747948] index-4.html is changed
 1 file changed, 203 insertions(+), 203 deletions(-)
 rename index-4.html => contact.html (98%)
PS C:\git-exercise\git-cafe-exercise> git add .
PS C:\git-exercise\git-cafe-exercise> git commit -m "done"
On branch bug/fix
nothing to commit, working tree clean
PS C:\git-exercise\git-cafe-exercise> git push origin bug/fix
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.50 KiB | 2.50 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'bug/fix' on GitHub by visiting:
remote:      https://github.com/thicien/git-cafe-exercise/pull/new/bug/fix
remote:
To https://github.com/thicien/git-cafe-exercise.git
 * [new branch]      bug/fix -> bug/fix
PS C:\git-exercise\git-cafe-exercise>
```
### Exercise-3

```bash
PS C:\git-exercise\git-cafe-exercise> git add .
PS C:\git-exercise\git-cafe-exercise> git commit -m "number changed"
[bug/fix 94d1ff7] number changed
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\git-exercise\git-cafe-exercise> git push origin bug/fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/thicien/git-cafe-exercise.git
   78fab7e..94d1ff7  bug/fix -> bug/fix
PS C:\git-exercise\git-cafe-exercise> 
```