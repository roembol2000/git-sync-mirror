# Git Sync Mirror

Simple bash script to automatically mirror a bunch of git repositories to
another remote

Requires bash 4.0 or later!

## Usage

To use, create a `repos.txt` file. For every mirror you want to make, create a
line as follows:

```text
git@github.com:roembol2000/git-sync-mirror.git|git@codeberg.org:roembol2000/git-sync-mirror.git
```

Only use SSH urls and do not include `ssh://` in front of the url.

Then, make sure that the script can be executed and run it:

```bash
chmod +x sync_repos
./sync_repos
```
