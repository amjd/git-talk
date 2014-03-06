% Git, GitHub and GitHub Pages
% Syed Amjad Ali
% March 6, 2014

# Version Control

> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

# git - definition

The Oxford Advance Learner's Dictionary defines git as,

git n. /ɡɪt/ A stupid or unpleasant man.

:D

# git goals
- Speed
- Simple design
- Strong support for non-linear development (thousands of parallel branches)
- Fully distributed
- Able to handle large projects like the Linux kernel efficiently (speed and data size)

# git workflow

The basic Git workflow goes something like this:
- You modify files in your working directory.
- You stage the files, adding snapshots of them to your staging area.
- You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.

If a particular version of a file is in the git directory, it’s considered committed. If it’s modified but has been added to the staging area, it is staged. And if it was changed since it was checked out but has not been staged, it is modified.

# git commands
- `git init`
- `git add`
- `git commit`
- `git branch`
- `git checkout`
- `git merge`
- `git clone`
- `git fetch`
- `git pull`
- `git push`

# GitHub Pages
Steps to host your website with GitHub Pages:
- Make a repository *username*.github.io on GitHub, with your GitHub username. (Eg, amjd.github.io)
- Clone the repository to your computer by running `git clone https://github.com/username/username.github.io.git`
- Make an index.html file. `echo "Hello world!" > index.html`
- Add untracked files to the stage. `git add .`
- Commit changes, specifying a short commit message. `git commit -m 'Initial commit'`
- Push the changes and your site will be live in a few minutes! :D `git push origin master`

# Sources
- http://git-scm.com/docs
- http://stackoverflow.com

# Further reading
- http://git-scm.com/docs
- http://marklodato.github.io/visual-git-guide/index-en.html
- http://rogerdudler.github.io/git-guide/
- http://www.progit.org/book/
