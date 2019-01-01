# inlab

## Create new App

ng new inlab

## Version control 

linked this to [remote git repository](https://github.com/harshkasyap/inlab) squashed all commits and pushed initial commit.

* Some useful git commands

    * git init
    * git add .
    * git commit -m "Initial commit"
    * git commit --amend --no-edit
    * git remote add origin remote repository URL
    * git push -u origin master
    * git push -u origin master --force
    * git pull
    * git pull origin branchname --allow-unrelated-histories
    * git rebase --interactive HEAD~2
    * git rebase -i --root

        * above commands will be useful if we messed up while init, clone, merge, squash, push
        * For md file help check [markdown-cheatsheets](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md)

## Deployment

Refer [Angular Deployment Documentation](https://angular.io/guide/deployment),
I faced issued to resolve base href, came to know it should be repo name, [help](https://github.com/angular/angular-cli/issues/1080)