# Merge conflict resolution using GitHub Desktop and Atom

Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. Let's look at quick example to understand how a merge conflict can arise and how we can resolve it using GitHub Desktop and Atom-

In this scenario, you are working with a teammate on a project and are using Git for version control. You create a repository called _'merge-conflict-resolution'_ with a _'Hello World'_ file called _'index.html'_ and two branches (_'master'_ and _'branch1'_). You are making changes on the _'master'_ branch and your teammate is making changes on the _'branch1'_ branch. A merge conflict occurs when you change _'Hello World'_ to _'Hello Earth'_ and your teammate changes it to _'Hello Mars'_. When you try to merge _'branch1'_ into _'master'_, you get a merge conflict.

* original _'index.html'_ file with _'Hello World!'_ on line 10 -
![image.png](/screenshots/screen9.png)

* master _'index.html'_ file with _'Hello Earth!'_ on line 10 -
![image.png](/screenshots/screen6.png)

* _'branch1'_ _'index.html'_ file with _'Hello Mars!'_ on line 10 -
![image.png](/screenshots/screen7.png)

* To merge this conflict using GitHub Desktop -

  - Click on _'Current branch'_ then click on _'Choose a branch to merge into **master**'_ in the bottom of the dropdown menu
![image.png](/screenshots/screen1.png)

  - Choose the branch ( _'branch1'_ ) and click on _'Merge'_. Note that you can already see that there will be a conflict
![image.png](/screenshots/screen2.png)

  - Click on _'Open in Atom'_

  ![image.png](/screenshots/screen3.png)

  - In Atom, you will see the conflict. Click on the _'Use me'_ button near the changes which you want to keep.
![image.png](/screenshots/screen4.png)

  - If you want to keep both changes, remove the headers (_'<<<'_, _'>>>'_ and _'==='_) and click on _'Dismiss'_
  ![image.png](/screenshots/screen11.png)
  #### Hurrah! Your merge conflict has been resolved! Go ahead and complete the merge!
