# A theme for Taskpaper for those who use notes more than tasks

Taskpaper 3 just came out, and here's a theme for those who:

* Use *note* items a lot, and tasks (dashed items) just a little
* Find the handle (the circle next to the lines) handy mostly to collapse indented items
* Prefer URLs to appear discreetly, but still look clickable

## Installation

    # Download theme to Application Support directory
    cd ~/Library/Application\ Support/Taskpaper/
    git clone https://github.com/pascallaliberte/theme-notes-first.git

    # Backup the previous theme.less and copy theme.less from theme-notes-first
    mv theme.less theme-backup.less && cp -p theme-notes-first/theme.less theme.less

## Upgrading

    # Download the latest version of the theme
    cd ~/Library/Application\ Support/Taskpaper/theme-notes-first
    git pull origin master

    # Backup the previous theme.less and copy theme.less from theme-notes-first
    cd ~/Library/Application\ Support/Taskpaper/
    mv theme.less theme-backup.less && cp -p theme-notes-first/theme.less theme.less

## Collaborating

1. Use a symlink to point to the theme.less inside the theme-notes-first directory

    `cd ~/Library/Application\ Support/Taskpaper/
    mv theme.less theme-backup.less && ln -s theme-notes-first/theme.less`

2. Fork this project
3. Create a branch with your new change e.g. `use-variables-everywhere`
4. Push your branch
5. Submit a pull request for your new branch