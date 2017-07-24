# **TechRacers Git Quiz**

[![N|Solid](http://www.techracers.com/wp-content/uploads/2017/04/logo-black.png)](http://techracers.com)

## **Problems**

### **1. Change author and committer name of multiple commits.**

Commits|Messages|Author/Commiter
-------|--------|---------------	
ad7a9e1|(HEAD -> master) Added some new paragraph|`Shivam Jaiswal <sjaiswal@techracers.com>`
4cd4658|Changed some Data|`Shivam Jaiswal <sjaiswal@techracers.com>`
fec1146|Replaced whole data|`Shivam Jaiswal <sjaiswal@techracers.com>`
b52c62d|Added another paragraph|`Shivam Jaiswal <sjaiswal@techracers.com>`
e9f2d8e|Added Dummy Data to file|`Shivam Jaiswal <sjaiswal@techracers.com>`
0b7fc5d|Added Html Data to index.html|`Shivam Jaiswal <sjaiswal@techracers.com>`
3f85dad|Added index.html|`Shivam Jaiswal <sjaiswal@techracers.com>`

**Make it like**

Commits|Messages|Author/Commiter
-------|--------|---------------	
ad7a9e1|(HEAD -> master) Added some new paragraph|`Your Name <youremail@email.com>`
4cd4658|Changed some Data|`Your Name <youremail@email.com>`
fec1146|Replaced whole data|`Your Name <youremail@email.com>`
b52c62d|Added another paragraph|`Your Name <youremail@email.com>`
e9f2d8e|Added Dummy Data to file|`Your Name <youremail@email.com>`
0b7fc5d|Added Html Data to index.html|`Your Name <youremail@email.com>`
3f85dad|Added index.html|`Your Name <youremail@email.com>`

###  **2. Bring back all changes back from listed commits without using `git reset`**

Commits|Messages|Author/Commiter
-------|--------|---------------	
ad7a9e1| Added some new paragraph|`Shivam Jaiswal <sjaiswal@techracers.com>`
4cd4658| Changed some Data|`Shivam Jaiswal <sjaiswal@techracers.com>`

### **3. Create new branch**
Make a new branch from `branch 1` with `Added Second File` commit as a `HEAD` and get `Added Third File` and `Added Fourth File` commit of `branch 2` and `branch 3` on newly created branch.

**staging**

```
	Added Eigth File    HEAD -> staging
		|
		|
		|
	Added Second File
		|
		|
		|
	Added First File
```

**develop**

```
	Added Sixth File    HEAD -> develop
		|
		|
		|
	Added Fourth File
		|
		|
		|
        Added Seventh File
```

**hot_fixes**

```
	Added Third File    HEAD -> hot_fixes
		|
		|
		|
	Added Ninth File
		|
		|
		|
	Added Fifth File
```

New Branch should look like this and have following commits.

**new_branch**

```

	Added Fourth File    HEAD -> new_branch
		|
		|
		|
	Added Third File
		|
		|
		|
	Added Second File
		|
		|
		|
	Added First File
```