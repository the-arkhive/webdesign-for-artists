# Lesson 2
## Basic Git and More Complex Markdown
In this lesson we will get a basic understanding of how we interact with the GitHub repo we made in the last section, as well as the repo we cloned to get a local copy of the lessons. After that we will learn a bit more about Markdown and begin generating something that can act as a portfolio while we learn the beginnings of web design.

<br>

### Git Commands
Git was originally made to be used with a command line or terminal, but it has also been adapted to more simplified use through Graphical User Interfaces (GUIs). The GitHub tab on the right side of Atom is one of these. Or rather the Git tab is, and the GitHub tab just provides us some info about our repo online. So let's click on the little `Git` button in the bottom right corner. You should get an interface that is split into 3 areas. The top one shows you which files in your repo have changed. If you open the README.md file, add some text and save, it should appear in the list with a yellow icon. This means Git has found changes to files and is ready to save them in a special way we call `Commits`. To move on to the next zone we need to `Stage` our changes. Do this by clicking the `Stage All` button in the upper right of the first zone. This should move any changes files down to the second zone. From there we are ready to make our first `Commit`. In the final box where it say `Commit message` add a message. Fir this lets just use something like "Learning git" or "testing commit". One that field is filled press `Commit to master`.

There is one final step to this before we will see any changes on the web interface for our repo. Open the command pallet with `Ctrl-Shift-P` and type `Push`. The first option should be `GitHub: Push`, select it and there should be a little indicator in the lower right that says `Pushing`, once it is done refresh the webpage for you repository and you should see the changes you made to the README.md file.

Now let's say I make changes to the lessons, or add a new one. How are you going to get these updates? Well we just used the `Push` command to make sure GitHub had all our changes, so we are going to use the `Pull` command to make sure we have any changes from another repo on GitHub. Make sure you have the folder for the course repo selected and then run the `Pull` command in the same way you ran the `Push` command. This also goes for your own repo. I like to make sure to run the `Pull` command every time I sit down to work on with a repo for a bit. Since we are mostly working with a repo run by a single person it's not as big a deal, but making sure everything stays synced for larger teams can involve a lot more complexity I will not get into here. All of these steps are outlined below.

- `Pull` - run the pull commands before you start working to make sure everything is up to date
- `Stage All` - press this button when you have made changes to files

<br>

### Using a Repo
