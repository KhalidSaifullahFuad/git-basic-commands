<h1 align="center">Git</h1>

**Git** is software for `tracking changes` in any set of files, usually used for `coordinating work` among programmers collaboratively developing source code during software development. Its goals include `speed`, `data integrity`, and support for `distributed, non-linear workflows`.

<h2 align="center">Git Commands</h2>

### git config

Configures user information used across all local repositories. Set a name that is identifiable for credit when review version history.

```
git config --global user.name "username"
```

Set an email address that will be associated with each history marker.

```
git config --global user.email "email"
```

### git init

Initializes an existing directory as Git repository (.git directory)

```
git init
```

### git remote

Set up the remote repository

```
git remote add origin https://github.com/UserName/RepositoryName.git
```

Check the current remote

```
git remote -v
```

### git pull

Pull from origin
```
git pull origin brach_name
```

### git push

Force push to origin

```
git push origin +branch_name --force
```

### git branch

Rename branch name

```
git branch -m <oldname> <newname>
```





