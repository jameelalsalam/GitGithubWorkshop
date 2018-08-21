# Practice

This section includes exercises to practice basic Git operations you might do every day. We plan to provide time for students to go through this material during the workshop session.

- [ ] Make and clone a new repo on Github
- [ ] Edit files directly on Github
- [ ] The pull, edit, commit, push cycle
  - [ ] Using the command line
  - [ ] Using Git-GUI
  - [ ] Using RStudio / other IDE




## Make and clone a new repo on Github

The easiest way to get a new project started is with "Github first, then clone locally" sequence. There are other options, but this approach has the fewest possible hiccups.

The instructions here are copied/adapted from Jenny Bryan's [approach here](http://happygitwithr.com/new-github-first.html) with extra screenshots. If you are having trouble here, you could try the source material.

### Make a repo on Github

**Do this once per new project.**

Go to <https://github.com> and make sure you are logged in.

Click green "New repository" button. Or, if you are on your own profile page, click on "Repositories", then click the green "New" button.

TODO: Screenshot

Repository name: `myrepo` (or whatever you wish)  
Public  
YES Initialize this repository with a README

Click the big green button "Create repository."

Copy the HTTPS clone URL to your clipboard via the green "Clone or Download" button. Or copy the SSH URL if you chose to set up SSH keys.

### Clone repo locally

TODO: Git Bash instructions and screenshots


### Alternative: Clone Using RStudio??



## The pull, edit, commit, push cycle

TODO: find/make a picture and an outside reference.

Some rules of thumb:

- Commit early, commit often. Maybe once an hour? Certainly every day.
- Fetch before every commit. This avoids merge conflicts with your colleagues.
- Push after every commit. This makes your changes available to your colleagues, and again helps avoid merge conflicts.

TODO: More here. This one is sort of the key section.


## Exercises:

1. Read the manual page for `git commit`. What does the `-m` mean in `git commit -m "initial commit"`? (Hint: try `git help commit` from Git Bash)
2. Is it possible to stage files to be committed using the command line, and then actually make the commit using a different tool (Git-GUI or RStudio)?


## Bonus Content

Here we started with a repo on Github, then cloned it locally. But there are lots of different ways to do the sequencing.

## Make a local repo, put it on Github

[Jenny Bryan approach here](http://happygitwithr.com/existing-github-last.html)

You can initialize a repo either from the Git-Bash command line:

    mkdir newproject
    cd newproject
    git init
    
Or using a client, e.g., "New Version Control Project" from RStudio

Then make some new files and put them in the folder. Add and commit them with Git.

    
    nano README.md
    (Ctrl-X, and 'Y' once you are done)
    
    git add README.md
    git fetch origin
    git commit -m "initial commit"
    git push origin
    


    