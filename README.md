# Merge conflict resolution through GitHub Desktop and Atom

Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. Let's look a quick example -

In this example, we have a repository called _'merge-conflict-resolution'_ with a file called _'index.html'_ and two branches (_'master'_ and _'branch1'_ ). We have a merge conflict when trying to merge _'branch1'_ into _'master'_ because _'Hello World!'_ was committed to _'Hello Earth!'_ in _'master'_ and to _'Hello Mars!'_ in _'branch1'_

* original _'index.html'_ file with _'Hello World!'_ on line 10 -
![image.png](/screenshots/screen9.png)

* master _'index.html'_ file with _'Hello Earth!'_ on line 10 -
![image.png](/screenshots/screen6.png)

* _'branch1'_ _'index.html'_ file with _'Hello Mars!'_ on line 10 -
![image.png](/screenshots/screen7.png)

* To merge using GitHub Desktop -

  - Click on _'Current branch'_ then click on _'Choose a branch to merge into **master**'_ in the bottom of the dropdown menu
![image.png](/screenshots/screen1.png)

  - Choose the branch ( _'branch1'_ ) and click on _'Merge'_. Note that you can already see that there will be a conflict
![image.png](/screenshots/screen2.png)

  - Click on _'Open in Atom'_

  ![image.png](/screenshots/screen3.png)

  - In Atom, you will see the conflict. Click on _'Use me'_ button near the changes which you want to keep.
![image.png](/screenshots/screen4.png)

  - If you want to keep both changes, remove the headers (_'<<<'_, _'>>>'_ and _'==='_) and click on _'Dismiss'_
  ![image.png](/screenshots/screen4.png)
