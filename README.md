# CSCI 5828 - Spring 2018

### Homework 2 (Due date: Feb 19) / Hansol Yoon

---

### Commit 0
git init <br>
vi README.md (to edit README.md) <br>
git add README.md <br>
git commit –m “Commit 0” <br>

### Commit 1
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 1” <br>

### Commit 2
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 2” <br>

### Commit 3
git log (to see the version number of Commit 0) <br>
git checkout <the version number of Commit 0> <br>
git checkout –b bug-fix <br>
***Now we are on the bug-fix branch*** <br>
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 3” <br>

### Commit 4
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 4” <br>

### Commit 5
git merge master <br>
vi README.md (to fix the conflict) <br>
git add . <br>
git commit –m “Commit 5” <br>

### Commit 6
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 6” <br>

### Commit 7
git log (to see the version number of Commit 4) <br>
git checkout <the version number of Commit 4> <br>
git checkout –b bug-fix-experimental <br>
***Now we are on the bug-fix-experimental branch*** <br>
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 7” <br>

### Commit 8
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 8” <br>

### Commit 9
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 9” <br>

### Commit 10
git checkout master <br>
***Now we are on the master branch*** <br>
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 10” <br>

### Commit 11
git checkout bug-fix <br>
***Now we are on the bug-fix branch*** <br>
git merge bug-fix-experimental <br>
vi README.md (to fix the conflict) <br>
git add . <br>
git commit –m “Commit 11” <br>

### Commit 12
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 12” <br>

### Commit 13
git checkout master <br>
***Now we are on the master branch*** <br>
git merge bug-fix <br>
vi README.md (to fix the conflict) <br>
git add . <br>
git commit –m “Commit 13” <br>

### Commit 14
***the image file that displays the commit graph is added*** <br>
vi README.md (to edit README.md) <br>
git add . <br>
git commit –m “Commit 14” <br>