# Git Configuration

![Git Logo](assets/git-logo.png)


## Telling git who you are

```bash
$> git config --global --list

$> git config --global user.name "Surendra Bajracharya"
$> git config --global user.email "bajracharya.surendra@gmail.com"
```


## Setting up the environment

```bash
$> git config --global core.editor /path/to/editor
$> git config --global merge.tool /path/to/diff/tool
$> git config --global color.ui auto
```


## Git user config file

* $HOME/.gitconfig
* Can edit this file directly

```bash
[user]
    name = Surendra Bajracharya
    email = bajracharya.surendra@gmail.com
```

<aside class="notes">
Example config file.
<br />
[section_name]
    property = value
</aside>


## Aliases

* Command aliases go in the <code>alias</code> section


## Exercise: Add some aliases

```bash
[alias]
    stat = status
    co = checkout
    hist = log --graph --oneline
```

<aside class="notes">
Remind people they can add aliases as the workshop progresses.
</aside>
