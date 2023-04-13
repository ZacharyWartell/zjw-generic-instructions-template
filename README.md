# Author Zachary Wartell

# Git: https://gitlab.com/zwartell/zjw-generic-instructions-template

Example:
    - https://webpages.charlotte.edu/zwartell/Teaching/WebGL%20Tutorial%201/index.html

- Git fork this repo as the upstream remote
- $ git submodule init
- $ git submodule update
- Add  git remote origin to reference your assignment description remote repo
- Initalize your origin and local repo as follows:
    - Windows CMD:
        - $ cd site/git_modules/zjwgi/scripts/
        - $ init-template.bat
            - this creates symlinks such as site/xyz/zjwgi that links to the corresponding zjwgi directory site/git_modules/zjwgi/site/xyz/zjwgi and creates some template    files such as site/index.html
        - $ git push origin main
