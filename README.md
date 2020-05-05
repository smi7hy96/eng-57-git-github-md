# Git, Github and Bash  - Title for README

This repo covers the following tools:
- Git
- Github
- Bash
- README files
- MarkDown files (.md)

## Bash
Bash is a scripting language used by command line terminals.
We can use it to create files, navigate our computer or run programs.

### Basic Bash Commands

- pwd --> print working directory
- ls --> list short
  - ls - a --> list all, including hidden folders
- cd <directory> --> go somewhere
  - cd .. --> go back one folder
  - cd ~ --> go to home directory
- touch <filename> --> Create a file
- mkdir <name> --> create a new directory/ folder
- rm <file> --> remove file
  - rm -rf <directory> --> recursive forced removal of all files in directory and directory itself

#### More Commands

- x=x --> create new variable (for current session only)
- echo $x --> print variable x (for current session only)
- printenv --> print environment variables (terminal settings)

## Git
Git is version control.
It can go backwards and forwards in time.
It can also create separate branches to allow us to experiment.

### Basic Git Commands

- 0) init --> create new repo
- 0) status --> info on current git repo
- 0) log --> view info on previous commits

- 1) add --> prepare a change to commit
- 1) commit -m 'message' --> commit change to repo including message of commit

- pull --> retrieve latest version of repo
- push --> commit edits to repo
- merge --> integrate branches back into one master branch
- clone --> clone an existing repo
