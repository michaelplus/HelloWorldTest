README
=======

This project is very simple and was created to understand the ins and outs of Git and GitHub, including how to collaborate on GitHub.

This was then forked (not using Git, just with copy and paste) and then uploaded as a new project to Bitbucket.

Instructions
-------------
For someone new to GitHub or Bitbucket, creating an account is the first step. For GitHub, there is a walk-through that guides a new user in downloading the GitHub native app and getting started working on projects. Bitbucket is a bit trickier for someone who has zero experience with Git, but is fairly easy to understand once one has gone through the GitHub tutorial.

Useful Resources
-----------------

* [http://git-scm.com/](http://git-scm.com/book/en/Getting-Started) is the first chapter of a good reference for understanding what version control is, what Git is, what GitHub is, and how to use it.
* [https://help.github.com/articles/github-flavored-markdown](https://help.github.com/articles/github-flavored-markdown) is a great explanation of Markdown, the formatting language used for GitHub README files.

Notes
------
* To upload to Bitbucket, ```git remote set-url origin https://mamurphy@bitbucket.org/mamurphy/helloworldtest-bitbucket-native.git``` was needed.
* I also needed to ```git add --all``` and git ```commit --all```, then ```git push -u origin --all```. The GUI for GitHub knocks the socks off the non-existent GUI for Bitbucket. Perhaps there is a GUI for Git that can be used with Bitbucket.
* [http://www.sourcetreeapp.com/](http://www.sourcetreeapp.com/) seems like a very popular GUI option for Bitbucket, and it is gaining ground on GitHub.
* This README may not show up in the native Windows 8 GitHub app; see [this Stack Overflow fix]( http://stackoverflow.com/questions/21110011/windows-github-app-not-detecting-readme/21273024#21273024).