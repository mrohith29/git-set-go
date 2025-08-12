## Initializing a Git Repository

To start using Git, you need to initialize a repository in your project directory.

```sh
git init
```

---

## Staging Changes

After making changes to your files, you need to stage them before committing.

```sh
git add <file>
```

To stage all changes, use:

```sh
git add .
```

---

## Cloning a Repository

To clone an existing repository from GitHub:

```sh
git clone <repository_url>
```

---

## Committing Changes

Once your changes are staged, you can commit them with a message describing the changes.

```sh
git commit -m "Your commit message"
```

---

## Pushing Changes

To upload your committed changes to a remote repository on GitHub:

```sh
git push origin <branch_name>
```

---

## Pulling Updates

To fetch and merge updates from a remote repository:

```sh
git pull origin <branch_name>
```

---

## Switching Branches

To switch to a different branch in your repository:

```sh
git checkout <branch_name>
```

---

## Checking Status

To check the status of your files and see which changes are staged, unstaged, or untracked:

```sh
git status
```

---

## Viewing Commit History

To view the commit history of your repository:

```sh
git log
```

---

By following these commands, you can effectively manage your Git repositories, whether you are creating a new one or updating an existing one.
