# 20-10-19 Development Environment Lecture

Today's lecture will focus on getting familiar with cloning github repositories using the terminal. Making file changes in Visual Studio Code, and pushing local changes to your remote repository using the terminal. 

### Set Up
- ensure that you can successfully navigate to your github profile
- ensure that you can successfully open the application Visual Studio Code and turn on autosave
- in the terminal, navigate to your `User` directory
    - open the Command Prompt application
    - run the command `ls` to list current files and subdirectories
    - run the command `cd` to change into a listed subdirectory
- in the terminal, create a new subdirectory called `CodeCrew` under your User directory using the command `mkdir CodeCrew`
- in the terminal, navigate to the newly created subdirectory `CodeCrew`
- in the terminal, create a new subdirectory called `html-css-basics` under your `CodeCrew` directory using the command `mkdir html-css-basics`

### Using GitHub
- accept the assignment link sent in the slack
- clone the assignment to your machine
    - copy the git url by clicking the green `Code` button (in the top right corner below the project navigation) and click the clip board icon
    - in the terminal navigate to the `html-css-basics` directory and run the command `git clone COPIED_URL`
    - a new subdirectory named the same as your repository will be created
    - in the terminal, navigate to the newly created subdirectory named after your repository 

### Using VSCode
- open the newly cloned repository in VSCode
    - open the application VSCode
    - in the menu bar choose file, open folder
    - choose the directory that you just cloned
    - OR in the terminal run the command `code .` from inside the cloned repository 

### Reflecting Local Changes in a Remote Repository 
- create a new file
    - from the explorer (two files icon in the sidebar) hover over the name of the open directory and click on the new file icon
    - OR right click in the explorer and choose `New File`
    - type the file name followed by the file extension separated by a period - lecture.txt
- paste a paragraph about computer science from [wikipedia](https://en.wikipedia.org/wiki/Computer_science) in the newly created file
- review file changes
    - click on the version control icon in the sidebar (branch with bubbles) and choose any file under `Changes` to see the differences
- push changes to your remote repository
    - in the terminal run the command `git status` to see if changes have been made locally
    - in the terminal run the command `git add -A` to stage all file changes for commit
    - in the terminal run the command `git commit -m "meaningful message"` to commit local changes with associated message
    - in the terminal run the command `git push` to push all commits to remote repository 
- check the the push was successful in github 

### Markdown Files
- create a new markdown file called notes - notes.md
- copy the snippet below into the newly created markdown file
```md
# Computer science
### Computer science is the study of computation and information.
Computer science deals with theory of computation, algorithms, computational problems, and the design of computer systems hardware, software, and applications.
Learn More [Here](https://en.wikipedia.org/wiki/Computer_science)
```
- review file changes
    - click on the version control icon in the sidebar (branch with bubbles) and choose any file under `Changes` to see the differences

### Subdirectories and External Files
- create a subdirectory from the VSCode explorer called `img` by choosing the `New Folder` icon on hover or right clicking in the explorer and choosing `New Folder`
- find an image related to computer science [maybe this one](https://wp-media.petersons.com/blog/wp-content/uploads/2018/01/26100309/blur-close-up-code-computer-546819.jpg), download the image to your machine and drag it from the download folder to the newly created `img` subdirectory
- add the image to your markdown file with the snippet `![Alternative Text](./img/IMAGE_NAME)`
- push changes to your remote repository
- check the the push was successful in github 

### Useful Extensions
- Code Spell Checker : A basic spell checker that works well with camelCase code

### Resources
[Concept Documentation Info on Git](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/overview.md#version-control) 

[Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
