# OhMyGit_Answers

This repo has my answers of Oh My Git Game - An open source game about learning Git!

If you also want to play the game then follow the [LINK](https://ohmygit.org/), download it and play it. <br> Also I find one website where you can refer to the answers [LINK](https://pierrejean.wp.imt.fr/2023/09/08/oh-my-git/).

>[!NOTE]
> The explanations of the problems in the game can sometimes be confusing, and at times, they don't provide enough clarity. Please stay calm and make an effort to solve them ;)

# 1. Intro
### 1.1) Living Dangerously
```
# Add a new line in the form.txt
```
## 1.2) Making Backups
```
# Add a new line in form2_really_final.txt
```
### 1.3) Enter the Time Machine
```
git init
```
### 1.4) The Command Line
```
git init
```
### 1.5) Your First Commit
```
git add glass
git commit -m "first commit"
# Change the contents of the file
git add glass
git commit -m "second commit"
```
### 1.6) Working Together
```
git pull
# Add your name to students.txt
git add students
git commit -m "Added my name"
git push
```

# 2. Files
## 2.1) Unexpected Roommates
```
rm big_web thick_web tiny_web
          OR
rm *web
```
## 2.2) Interior Design
```
touch chair bed
# Write yellow in both files and save
```

# 3. branches
## 3.1) Moving through Time
```
git checkout 0ae4e768ddf2b27f7b65471b3f1b2c504d50eea3
# Add 10 coins in  piggy_bank.txt
git add .
git commit -m "Added 10 Coins"
```
## 3.2) Make Parallel Commits
```
git checkout HEAD~2
# Add text Child is happy in cage/child and Add text Lion eat Lollipop or something else in  cage/lion
git add .
git commit -m "Done changes"
```
## 3.3) Creating Branches
```
git branch -f birthday 0ee310f9a1612079377ca5156888fa35b848a9a6
git branch -f concert 6412f2b19a4c97b29780ac6889ee2ff4910a9484
```
## 3.4) Branches grow with you!
```
git checkout e5cbb3ef4ecc5642431a2e39e818ce67c6891793
# Make changes to you.txt
git add you
git commit -m "Changes done in you"
git checkout concert
# Make changes in you.txt
git add you
git commit -m "Changes done in you
```
## 3.5) Deleting the Branches
```
git checkout 8b698d2fd41693dfef7f6942588c1458ef65ce40
git checkout 06ae81bc3acdaff7f2d8797e599d9b2c73620874
git checkout 670bce20cf0f059ae042b92c1a0a0881192b40d8 # Correct Branch
git checkout 7876691fe99b6645b37ae41c4d3ac1f1cdb5e0e7
git branch -D music ice-cream friend
```
## 3.6) Moving branches arounnd
```
git checkout 581d19075bf4e16695e9987b291e7579e6610b11
git branch -f coffee ecf5c44fdc25087ca9243855ef559ad543d972a9
git branch -f baguette 6ab8db489344e7130e1f027f567c5d0171ce3f9f
git checkout e99ce9ac2a9a120f7588a96965e9434373e1f62f
git add .
git commit -m "you ate a donut"
git branch -f donut 6e9ec3cfa103df50ebb5e0586e0ef87161e41d78
```
# 4. Merge
## 4.1) Merging Timelines
```
git merge bda7e769b85dc92dc45205e0ed94845c2e12a3db
git merge d63959cd3286972202c0b8e98514de15fcb0919d
```
## 4.2) Contradictions
```
git reset --hard muesli
git merge pancakes
git add .
git commit -m "compromise"
```
# 5. Index
## 5.1) Step by Step
```
git checkout step-by-step
# Add text alarm goes off in smoke_detector.txt
git add .
git commit -m "alarm goes off"
```
## 5.2) Add New Files to the Index
```
git add candle
git commit -m "added new file"
```
## 5.3) Update Files in Index
```
# Do some changes in the candle.txt file
git add candle
git git commit -m "did changes in candle"
```
## 5.4) Resetting files in the Index
```
git reset blue_candle green_candle
git commit -m "done"
```
### 5.5) Adding Changes step by step
```
# Do some changes in all the files
git add bottle
git commit -m "added bottle"
git add hammer
git commit -m "added hammer"
git add sugar_cane
git commit -m "added sugar_cane" 
```
