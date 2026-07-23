Example for D197 for creating a remote off a local repo.

It was determined that you cannot create a remote repository from a local windows terminal using just git commands. The repository must exist online first to be able to connect to it.

After making line 3 edit via GitHub, in doing git status locally, it says all is well. So this states that git status review local changes; not changes online. After a git pull, it updated this local file with the changes online.