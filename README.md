<img src="https://media.giphy.com/media/2QHLYZFJgjsFq/giphy.gif" width="100%">

<h1 align="center">Hi 👋, I'm Clarence Abcdee M. Glorioso</h1>
<h3 align="center">A 2nd Year Computer Science Student from Mapúa Malayan Colleges Laguna</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=abc1dee&label=Profile%20Views&color=0e75b6&style=flat" alt="abc1dee" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=abc1dee" alt="abc1dee" /></a> </p>

- 📫 How to reach me **abcdee1glorioso@gmail.com**

- ⚡ Fun fact **I hate coding**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/abcdeglrso" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="abcdeglrso" height="30" width="40" /></a>
<a href="https://instagram.com/deo1.gg" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="deo1.gg" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abc1dee&show_icons=true&locale=en&layout=compact" alt="abc1dee" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=abc1dee&show_icons=true&locale=en" alt="abc1dee" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abc1dee&" alt="abc1dee" /></p>

<br>
<h2>❗ Git Commands Cheat Sheet ❗ </h2>

``` html

1.  Command: git reflog

Description: Displays a log of all reference changes (e.g., branch creations, rebases) in the repository, helping you recover lost commits or branches.
Use Case: When you accidentally delete a branch or commit and need to recover it.
Parameters: git reflog
Example:
git reflog

2.  Command: git filter-branch

Description: Rewrites branches to remove or modify commits, useful for history cleanup or repository restructuring.
Use Case: When you need to remove sensitive information from the entire history or restructure the repository.
Parameters: git filter-branch [options]
Example:
git filter-branch --commit-filter 'git_commit_non_empty_tree "$@"'

3.  Command: git submodule

Description: Manages Git submodules within a repository, allowing you to include other Git repositories as subdirectories.
Use Case: When you want to include external projects or libraries in your repository while keeping them independent.
Parameters:
git submodule add <repository-url> [path] (to add a submodule)
git submodule update --init --recursive (to initialize and update submodules)
Example:
git submodule add https://github.com/example/repo.git external/repo

4.  Command: git worktree

Description: Manages multiple working trees, allowing you to have multiple branches checked out simultaneously in different directories.
Use Case: When you need to work on multiple features or bug fixes simultaneously without switching branches in the same working directory.
Parameters:
git worktree add <path> <branch> (to create a new working tree)
git worktree list (to list all working trees)
Example:
git worktree add ../feature-branch feature-branch

5.  Command: git fsck

Description: Performs a file system check on the Git repository, helping to identify and repair issues in the object database.
Use Case: When you suspect corruption in the repository or want to ensure the integrity of the Git objects.
Parameters: git fsck
Example:
git fsck
