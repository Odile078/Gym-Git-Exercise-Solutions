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

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add --all
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Creating team page"
 1 file changed, 11 insertions(+)
 create mode 100644 team.html
Enumerating objects: 4, done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/team-page
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git log
commit 63365934017df1cdd59fde86d515adfaf7fcfa58 (HEAD -> ft/team-page, origin/ft/team-page)
Date:   Fri Nov 4 14:24:55 2022 +0200

commit 52d55e0fdd746b72ff94f5d7e780b786a20383e0 (origin/main, origin/HEAD, main, ft/contact-page)
Author: Odile078 <ouwimpuhwe620@daviscollege.com>
Date:   Fri Nov 4 12:53:20 2022 +0200

commit f2c6b96727279f532e3f4fdc6ad157b51250d97a (ft/service-redesigns)
Author: Odile Uwimpuhwe <62097558+Odile078@users.noreply.github.com>

    Update services.html

    Changing services.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git cherry-pick 63365934017df1cdd59fde86d515adfaf7fcfa58
[ft/contact-page 0253b16] Creating team page
 Date: Fri Nov 4 14:24:55 2022 +0200
 1 file changed, 11 insertions(+)
 create mode 100644 team.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add contact.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Creating contact page"
 1 file changed, 11 insertions(+)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Writing objects: 100% (6/6), 753 bytes | 753.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/contact-page
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add faq.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Creating faq page"
Revert "Creating team page"
 create mode 100644 faq.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 458 bytes | 458.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/faq-page
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git revert 63365934017df1cdd59fde86d515adfaf7fcfa58
[ft/faq-page 53315ed] Revert "Creating team page"
 1 file changed, 11 deletions(-)
 delete mode 100644 team.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 283 bytes | 141.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Odile078/git-exercises.git
   c2176df..53315ed  ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.
```

### Exercise 3

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add --all
[main d5d3e1e] Updating home page content
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout ft/home-page-redesign
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git log
Date:   Fri Nov 4 14:49:33 2022 +0200

    Revert "Creating team page"
    This reverts commit 63365934017df1cdd59fde86d515adfaf7fcfa58.
Author: Odile078 <ouwimpuhwe620@daviscollege.com>
Date:   Fri Nov 4 14:47:33 2022 +0200
    Creating faq page

commit 2d25c11a70c18bbf840e7687b29ce1f2b87d40b9
Author: Odile078 <ouwimpuhwe620@daviscollege.com>
Date:   Fri Nov 4 14:44:50 2022 +0200
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add home.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "Updating home page content"
[ft/home-page-redesign f32ee24] Updating home page content
 1 file changed, 1 insertion(+)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u ft/home-page-redesign
fatal: 'ft/home-page-redesign' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin ft/home-page-redesign
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 4 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 1.83 KiB | 375.00 KiB/s, done.
Total 17 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/home-page-redesign
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
```

## Bundle 4

### Exercise 1

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git remote add git-copy https://github.com/Odile078/git-exercise-clone.git
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git remote -v
git-copy        https://github.com/Odile078/git-exercise-clone.git (fetch)
origin  https://github.com/Odile078/git-exercises.git (fetch)
origin  https://github.com/Odile078/git-exercises.git (push)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git remote
git-copy
origin
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add --all
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit "feat:updating home page"
error: pathspec 'feat:updating home page' did not match any file(s) known to git
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 318 bytes | 318.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Odile078/git-exercises.git
   16c7d00..60dd812  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u git-copy  main
Enumerating objects: 57, done.
Counting objects: 100% (57/57), done.
Delta compression using up to 4 threads
Compressing objects: 100% (49/49), done.
Writing objects: 100% (57/57), 10.21 KiB | 804.00 KiB/s, done.
Total 57 (delta 25), reused 11 (delta 3), pack-reused 0
remote: Resolving deltas: 100% (25/25), done.
To https://github.com/Odile078/git-exercise-clone.git
 * [new branch]      main -> main
branch 'main' set up to track 'git-copy/main'.
```

### Eexrcise 2

```bash
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add footer.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "feat: Adding footer file"
[ft/footer b88719b] feat: Adding footer file
 2 files changed, 10 insertions(+)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git add footer.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "feat: Adding footer content"
 1 file changed, 7 insertions(+), 1 deletion(-)
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 916 bytes | 305.00 KiB/s, done.
Total 7 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/footer
remote:
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'git-copy/main'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git merge --squash ft/footer
Updating 60dd812..dc2be02
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 15 +++++++++++++++
 home.html   |  1 +
 2 files changed, 16 insertions(+)
 create mode 100644 footer.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git commit -m "footer changes squashing"
[ft/squashing 47391ee] footer changes squashing
 2 files changed, 16 insertions(+)
 create mode 100644 footer.html
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git log
Date:   Fri Nov 4 15:54:03 2022 +0200
    footer changes squashing

commit 60dd812f79eb88d4ffac0872f8d45e8bfefcbb40 (origin/main, origin/HEAD, git-copy/main, main)
Merge: d5d3e1e 16c7d00
Author: Odile078 <ouwimpuhwe620@daviscollege.com>
Date:   Fri Nov 4 15:38:59 2022 +0200

    Merge branch 'main' of https://github.com/Odile078/git-exercises

commit d5d3e1e592fd00acb31cb3ec9bb8f436e9bed9af
Author: Odile078 <ouwimpuhwe620@daviscollege.com>
Date:   Fri Nov 4 14:58:15 2022 +0200

    Updating home page content

commit 16c7d000e15351c6bf88a93935b83aa9742a91cd
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git merge --squash ft/squashing
Already up to date. (nothing to squash)
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises> git push -u origin  ft/squashing
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 666 bytes | 666.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Odile078/git-exercises/pull/new/ft/squashing
remote:
To https://github.com/Odile078/git-exercises.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.
PS C:\Users\TheGym\Documents\TheGym\gitExercises\git-exercises>
```
