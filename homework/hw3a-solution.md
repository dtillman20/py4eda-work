# HW3A Solution - Git and Version Control

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.

### Key Commands Used

- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections

## Part 2: Portfolio Repository Creation

I created my personal course repository with:

- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes

### Understanding Git Workflow

The three-stage workflow:

1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`

## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub

### The Remote Connection

My local repository is now connected to GitHub:

- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)

### Details

Complete this section with details from your setup:

- Repository URL: ... 
- Output of `git remote -v`: 
- The output of `git log --oneline`:

## Questions  

### Reflection Questions 
1)
   a) Before this assignment I managed different versions of my work via Word, Jupyter lab, and GoogleColab for writing code and using markdown language. I think that it is easier to share documents with Git, since it is a website where a terminal, in my case Git Bash, does not have to be open to run the website unlike Jupyter Lab. When modifying a file in Git Bash via the _editor_, I noticed that the features, _undo_ and _redo_ were not available in the _editor_. This was a big issue for me. But, these two features are available on the Git website, which is where I am directly editing this file.  
   - Advantages of using Git:  
     - advantage: allows you to share python code through a Github account which is linked to a website URL
     - advantage: git provides a way to verify your commit before you push it to Github
   b) Hmmm. The situation I can think of is for example, as an engineer in the civilian AF, the program I work for requires field work. If someone from the office asks me if I uploaded a file to say our Sharepoint googledrive but I did not have internet access in the field, if we used Github to share documents, I use git offline to view my Git commit history since this command does require internet access

2) 
 
