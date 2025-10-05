# Description
A personal tutorial repository (aka repo) to practice git commands.

But I might as well us this repo to pratice front-end development...

This started out as a local repository stored on my personal computer. As to how I did that:

  - Run the command `git init` to initialize a git repository
  - Make various commits to the local repo using `git add` then `git commit -m "some meaningful commit message would go here"`...
  - Run these commands:
    - `git remote add origin https://github.com/<username>/<address>.git`: link the local project to a GitHub repo (`origin` is the default name for the main remote repo).

      In this case:
      - `<username>` = RocketStarMan7285
      - `<address>` = LocalRepoND
    - `git branch -M main`: `-M` option of `git branch` renames the current branch to `main` (the default branch name used by GitHub), regardless of what it was called before
    - `git push -u origin main`: pushes the **local** main branch to the remote repo (`origin`), the `-u` flag sets the upstream link between local and remote branches
# Contents
  - `index.html:` a html file

  - `notes.txt:` contains notes on git commands

  - `README.md:` A README.md is a text file, usually written in Markdown (.md), that provides information about a project. It’s one of the first things people see when they visit a repository
    (like on GitHub, GitLab, or Bitbucket). Think of it as the project’s "cover page" or "manual."

    More information about markdown can be found here: https://www.markdownguide.org/

    Practice writing .md files with an online editor: https://dillinger.io/
# I made changes:
Directly on GitHub: I run `git pull` to update my local repository (the one on my personal computer) 

On my local machine: I run `git push origin` to update the remote repository (this GitHub repository!)

Sidenote: Because we previously specified the `-u` flag with the first `git push` command, we can run these commands without specifying `origin main` everytime!

**YOU MUST RUN THESE COMMANDS IN THE SAME DIRECTORY THAT THE REPOSITORY IS IN!!!**

# Be on the lookout for...
I may practice GitHub branches...

I may add some CSS and JavaScript...
