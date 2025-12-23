# Git Sync Mirror

Simple bash script to automatically mirror a bunch of git repositories to another remote

## Usage

To use, create a `repos.txt` file. For every mirror you want to make, create a line as follows:

```
git@github.com:roembol2000/git-sync-mirror.git|git@codeberg.org:roembol2000/git-sync-mirror.git
```

Only use SSH urls and do not include `ssh://` in front of the url.
