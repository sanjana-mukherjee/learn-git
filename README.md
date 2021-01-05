# Git Commands

## Contributing to an open source project

## METHOD 1

- First fork the repository you in which you wish to contribute

- Clone your copy of the repository
  ```bash
  git clone https://github.com/ssmkhrj/learn-git.git
  ```
- Make changes and commit those changes
  ```bash
  git add .
  git commit -m "add some commands"
  ```
  _NOTE: Here the commit message uses the verb add and not added_
- Also, the remote is already correctly set since we cloned it from github, to see run

  ```bash
  git remote -v
  ```

  _v flag stands for verbose_

- Push changes to your copy

  ```bash
  git push -u origin master
  ```

  _u flag stand for upstream. And if we use this flag from next push onwards we can simply run `git push`_

- Finally you can go to github and on your repo you would see a message prompting that "_This branch is 1 commit ahead of sanjana-mukherjee:main_" and a button for making the pull request, click the button and continue with the pull request.
