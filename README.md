# GIT Exercises

This projects is used to do Git exercises.

## Bundle 1

### Exercise 1

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git init
Initialized empty Git repository in C:/Users/TheGym/Documents/TheGym/gitExercises/git-exercise-1/.git/
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch -m main
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add README.md
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Setting up the project"
[main (root-commit) a6dbf90] Setting up the project
 1 file changed, 7 insertions(+)
 create mode 100644 README.md
On branch main
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git remote add origin https://github.com/Odile078/git-exerPS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Compressing objects: 100% (2/2), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout -b dev
Switched to a new branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout -b test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch
  main
* test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push origin  dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote:      https://github.com/Odile078/git-exercises/pull/new/dev
To https://github.com/Odile078/git-exercises.git
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout test
Switched to branch 'test'
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/test
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      test -> test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git branch -D test
Deleted branch test (was a6dbf90).
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push origin  --delete  test
To https://github.com/Odile078/git-exercises.git
 - [deleted]         test
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Already on 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Adding Exercise 1 commands to the README file"
[main 4657c17] Adding Exercise 1 commands to the README file
 1 file changed, 53 insertions(+)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 976 bytes | 488.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   a6dbf90..4657c17  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Updating the README fil"
[main 1e51b00] Updating the README fil
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 159.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   4657c17..1e51b00  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git checkout dev
Switched to branch 'dev'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git commit -m "Adding commands used the the README file in dev branch"
[dev 3fc0b5c] Adding commands used the the README file in dev branch
 1 file changed, 69 insertions(+)
 PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercise-1> git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.08 KiB | 552.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   a6dbf90..3fc0b5c  dev -> dev
branch 'dev' set up to track 'origin/dev'.

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add .
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Updating Exercise 1 commands"
[dev 1e9868d] Updating Exercise 1 commands
 1 file changed, 30 insertions(+)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 542 bytes | 271.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Odile078/git-exercises.git
   3fc0b5c..1e9868d  dev -> dev
branch 'dev' set up to track 'origin/dev'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>

```

### Exercise 2

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add home.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)

Saved working directory and index state WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git status
Your branch is up to date with 'origin/dev'.

Changes to be committed:
        new file:   about.html

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash
Saved working directory and index state WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
stash@{0}: WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add team.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash
Saved working directory and index state WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
stash@{0}: WIP on dev: 1e9868d Updating Exercise 1 commands
stash@{1}: WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q|--quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash pop stash@{1}
usage: git stash pop [--index] [-q|--quiet] [<stash>]

    --index               attempt to recreate the index

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash pop 'stash@{1}'
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
Dropped stash@{1} (cb949f7c5177339d0b11f98eb2fe9feffb74d01d)
stash@{1}: WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash pop 'stash@{1}'
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (dad95d271dd79abbacef40adc74ab1e3726f81c3)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
stash@{0}: WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Adding Home and about page"
 2 files changed, 22 insertions(+)
 create mode 100644 home.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 534 bytes | 267.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
   1e9868d..ba32cfc  dev -> dev
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
stash@{0}: WIP on dev: 1e9868d Updating Exercise 1 commands
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (493d53a624dc46cbf59588faced2392601c84498)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git stash list
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git reset --hard
HEAD is now at ba32cfc Adding Home and about page
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
```

## Bundle 2

### Exercise 1

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add README.md
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Adding Exercise 2 commads to the README file"
 1 file changed, 117 insertions(+)
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
branch 'dev' set up to track 'origin/dev'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add services.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Adding services page"
[ft/bundle-2 ad02c87] Adding services page
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
error: src refspec ft/bundle does not match any
error: failed to push some refs to 'https://github.com/Odile078/git-exercises.git'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>  git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 469 bytes | 156.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/bundle-2
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
```

### Exercise 2

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), 1.29 KiB | 82.00 KiB/s, done.
From https://github.com/Odile078/git-exercises
   196996b..f2c6b96  main       -> origin/main
Updating 196996b..f2c6b96
Fast-forward
 services.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout  ft/service-redesigns
error: pathspec 'ft/service-redesigns' did not match any file(s) known to git
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout  -b ft/service-redesigns
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add services.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Making changes to services.html"
[ft/service-redesign 72ab878] Making changes to services.html
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin  ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Writing objects: 100% (3/3), 309 bytes | 309.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
   6219506..72ab878  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add services.html
Everything up-to-date
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add services.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Making changes to services.html"
[main 52d55e0] Making changes to services.html
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   f2c6b96..52d55e0  main -> main
branch 'main' set up to track 'origin/main'.
#
Your branch is up to date with 'origin/ft/service-redesign'.
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add services.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit
[ft/service-redesign 0167179] Merge branch 'main' into ft/service-redesign
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin  ft/service-redesign
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 245 bytes | 245.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odile078/git-exercises.git
   72ab878..0167179  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
```

## Bundle 3

### Exercise 1
