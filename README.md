# git-cafe-exercise

## Bundle-5 Exercises

### Exercise-1
```bash
 https://thicien.github.io/Gym-Git-Exercise-Solution2/index.html
```

### Exercise-2

```bash
PS C:\git-exercise> git clone https://github.com/thicien/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 63.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.
PS C:\git-exercise> cd git-cafe-exercise
PS C:\git-exercise\git-cafe-exercise> git add .
PS C:\git-exercise\git-cafe-exercise> git commit -m "index.html has edited"
[main 57134b3] index.html has edited
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\git-exercise\git-cafe-exercise> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 330 bytes | 330.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/thicien/git-cafe-exercise.git
   d1d3f9c..57134b3  main -> main
PS C:\git-exercise\git-cafe-exercise> git checkout -b ft/my-feature
Switched to a new branch 'ft/my-feature'
PS C:\git-exercise\git-cafe-exercise> git branch
* ft/my-feature
  main
PS C:\git-exercise\git-cafe-exercise> cd
PS C:\git-exercise\git-cafe-exercise> git checkout ft/my-feature
Already on 'ft/my-feature'
PS C:\git-exercise\git-cafe-exercise> git add .
PS C:\git-exercise\git-cafe-exercise> git commit -m "finished"
[ft/my-feature a9be259] finished
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\git-exercise\git-cafe-exercise> git push origin ft/my-feature
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/my-feature' on GitHub by visiting:
remote:      https://github.com/thicien/git-cafe-exercise/pull/new/ft/my-feature
remote:
To https://github.com/thicien/git-cafe-exercise.git
 * [new branch]      ft/my-feature -> ft/my-feature
PS C:\git-exercise\git-cafe-exercise> 
```