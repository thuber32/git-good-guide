<h1>DeltaV Git Good Guide</h1>

<h2>Set Up Local Project</h2>

<h3>Initialize New Project</h3>

```
git init
```
<h3>From GitHub</h3>
```
git clone https://github.com/my-user/my-repo-name.git
```
<h2>ACP:  Add, Commit, Push</h2>

```
git add . 
```
<h3>Save Change in Git</h3>
<p>To save the added changes into history, commit with a useful, descriptive message</p>

```
git config --global core.editor "code --wait"
```

<h4>Review Changes Before Committing</h4>
To view changes that have not been added 

```
git diff
```

To review changes that have been added:

```
git diff --staged
```

<h3>Push to GitHub</h3>

To push changes on the current branch to its branch on GitHub:

```
git push
```

If the current branch has not been pushed yet:

```
git push -u origin HEAD
```

<h2>Branching</h2>

<h3>To Create A Branch ** from current location (HEAD)**</h3>

```
git branch my-branch
```

<h3>To Switch to a Branch</h3>

```
git checkout my-branch
```

<h3>To Switch to a New Branch **from 'master'**</h3>

```
git checkout master -b my-branch
```

<h3>To Switch to a New Branch **from current location('HEAD')**</h3>

```
git checkout -b my-branch
```

<h3> To Delete a Local Branch</h3>

```
git branch -d my-branch
```

**Note:** 