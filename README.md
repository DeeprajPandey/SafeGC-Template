Welcome to SafeGC repository!

The aim of SafeGC to build a stop of world conservative GC for C/C++ applications.

Run make in the assignment folder to build the SafeGC library and a sample application.

Please send an email to me (piyus at iiitd dot ac dot in) if you want to report an implementation bug.

---

## PLDI Specific Instructions

This is a template repository based on [SafeGC](https://github.com/Systems-IIITD/SafeGC) designed by [Dr. Piyus Kedia](https://www.iiitd.ac.in/piyus). This section is added for [CS-1319: Programming Language Design and Implementation](https://sites.google.com/ashoka.edu.in/cs1319) at Ashoka University where the assignment is set up on GitHub Classroom. Reach out to course staff on [the staff mailing list](mailto:cs1319-staff@googlegroups.com) for clarifications.

### Setup

Clone this repository

```sh
$ git clone https://github.com/CS1319-Monsoon2020/safegc-<USERNAME>.git
```

Create a new branch and checkout into it

```sh
$ git checkout -b submission1
```

### Snapshots

Work on your solution on this branch. You can check which files were modified with status.

```sh
$ git status
```

Every once in a while, commit your work. <details><summary>Committing is a two-step process.</summary>

<ul>
<li>Add specific files to the staging area. You can specify multiple files too.

```sh
$ git add memory.c
```
  
You can also add all the files which were modified (be careful)

```sh
$ git add .
```
</li>

<li>Commit your changes

The `-m` flag adds a message for your commit that is included in double quotes following the flag.

```sh
$ git commit -m “Add function definition”
```
</li>
</ul>
</details>

<details><summary>Push all your commits to the remote repo.</summary>

_Use this command the very first time you push. `--set-upstream` and its options will add a new branch in the remote copy_

```sh
$ git push --set-upstream origin submission1
```

For every subsequent push, use this

```sh
$ git push
```
</details>

### Gearing for Submission

<details><summary>When you are done with the solution and you have pushed all your commits to the `submission1` branch, merge the submission branch to master.</summary>

<ul>
<li>First ensure that you are on the master branch and that there are no differences between the remote copy and your local copy

```sh
$ git checkout master

$ git pull
```
</li>

<li>Now, merge your submission branch to master

```sh
$ git merge submission1
```
</li>
</ul>
</details>

Push the new changes in master to the remote repo

```sh
$ git push
```
