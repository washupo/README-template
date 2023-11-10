# Titre
![Banner](/images/Banner.jpg)
[Live demo]()
# Description courte de projet (140words max)
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In quis mattis massa. Quisque convallis viverra elementum. Donec suscipit pulvinar ullamcorper. Cras fermentum mauris turpis, eget viverra velit ornare id. Phasellus semper velit vitae tristique tincidunt. Pellentesque tristique mauris fermentum arcu egestas ultrices. Morbi vel justo vitae leo pulvinar lacinia id ut nunc.
Proin eu suscipit lorem. Nulla congue urna id dolor gravida facilisis. Aenean suscipit eget nisl vitae viverra. Vivamus ante velit, consectetur in accumsan id, suscipit eu lorem. Curabitur mollis orci et tellus pellentesque, ut vestibulum metus convallis. In et sem imperdiet, viverra odio et, vestibulum leo. Vestibulum pulvinar fringilla iaculis. Cras mollis semper ex quis hendrerit. Mauris non diam quis tellus pharetra laoreet. Aliquam et nisl ut ante rhoncus volutpat. Praesent finibus velit urna, id maximus dui dignissim id. Quisque nec ullamcorper felis, nec ornare nisl. Pellentesque dapibus. 

# Screenschots
## Desktop
![Desktop screenshot](/images/Desktop%20screenshot.jpg)
## Mobile
![Mobile screenshot](/images/Mobile%20screenshot.jpg)

# Techs utilisés 
(main libraries `i,e:  vite, bootstrap, tailwind,typescript`)

# Development (quoi je dois faire pour le lancer en local dans ma machine)
## Cloning the Repository

1. Navigate to the directory that you would like to clone the repository into using commands like:
    `cd`: to change your working directory.
    `cd ../` to "go back" a level in your directory tree.
2. Clone the remote repository and create a local copy on your machine using this command:

    `git clone git@github.com:yvessoham/Javascript.git`

3. Now you can see the contents of the remote repository on your machine by moving into the newly cloned directory:

    `cd Javascript/`
    `ls -la`

## Updating Your Local Repository

When changes are made to the remote repository, they will not automatically sync with your local copy. You can update your local directory by running the following command when your working directory is `Javascript`. You can check your working directory by running pwd, the last item in the path should be `Javascript/`.

To update your local git directory:
`git pull`

**Note:** on `git pull` errors: You may get a `git pull` error if you have made changes to files in your local git directory. This is ok, and normal. If you get an error when you `pull` (or update) the repo that says something like "Your local changes to the following files will be overwritten by merge’", you can do a `git stash` to address this. To find out how to do this, go to https://git-scm.com/book/en/v1/Git-Tools-Stashing to read all about it.

## Updating Your Local Changes To The Remote Repository

1. `git status` 
    Always a good idea, this command shows you what branch you're on, what files are in the working or staging directory, and any other important information.
2. `git checkout [branch-name]`
    Switches to the specified branch and updates the working directory.
3. `git commit -m "descriptive message"`
    Records file snapshots permanently in version history.
4. `git push` 
    Uploads all local branch commits to the remote.

<!-- # Copyright 
()[] - Source -->
