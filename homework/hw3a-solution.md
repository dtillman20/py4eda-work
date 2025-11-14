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
   a) It's important to keep the `class_repo` and `my_repo` separate because:
     - `class_repo` is read-only, meaning you can only `pull`, read files, from this repository (repo)
        - If anyone besides Dr. Oleary tried to push commits to this repository it would get denied
      - `my_repo` is available for reading and writing I believe because it is public
         - Therefore me or someone could push commits to this repo
      - If I tried to put everything in one repo, I would not be able to push commits because one of the repos, `class_repo` is read-only
   b) I would orgaize multiple repos based on which ones I would want to be read-only: 
      - A group project I would allow anyone in my group to be able to `pull` or `push` commits to the repo.
      - Probably for an individual assignment I would make the repo read-only, so others could only `pull` from it
         - For reference materials, I would definitely make this repo read-only.
3)
   a) "update" is more useful when updating a file and the 2nd message is more useful when adding a file to a repo.
     - These two commit messages help separate and distinguish when a new file is being added or an existing file is being updated.
     - I might need to find the 2nd commit for book keeping reasons or to document when a certain file was initally committed
   b) First, I clarified with Claude to understand why the cammands, commit and push are separate. It explained that using commit is like saving your changes in a word document and then pushing those changes is like uploading them to google drive. Using the commit command does not require internet access. 
      - With this information, I would choose to commit my changes probably daily so that my work is saved and safe.
          - "Added ...", "Finished ...", and "Updated ..." could be useful for a single commit
      
### Graduate Questions
1) 

 
