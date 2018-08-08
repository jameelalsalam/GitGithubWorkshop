# Exercises

Some beginning exercises and instructions...
(Minimum useful skills, e.g., get off the beach!)

- [ ] Make and clone a new repo on Github
- [ ] The pull, edit, commit, push cycle
- [ ] Make a local repo, get it on Github



## Make and clone a new repo on Github

[Approach here](http://happygitwithr.com/new-github-first.html)


## The pull, edit, commit, push cycle

TODO: find/make a picture and an outside reference.

Some rules of thumb:

- Commit early, commit often. Maybe once an hour? Certainly every day.
- Fetch before every commit. This avoids merge conflicts with your colleagues.
- Push after every commit. This makes your changes available to your colleagues, and again helps avoid merge conflicts.

TODO: More here. This one is sort of the key section.


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
    


    