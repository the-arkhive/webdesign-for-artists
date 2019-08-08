# Lesson 2
## Basic Git and Markdown
In this lesson we will get a basic understanding of how we interact with the GitHub repo we made in the last section, as well as the repo we cloned to get a local copy of the lessons. After that we will learn a bit more about Markdown and begin generating something that can act as a portfolio while we learn the beginnings of web design.

<br>

### Git Commands

NOTE UPDATE WITH FIXED CLONE PROCESS
  - Terminal install XCode command line tools
  - install Git
  - pull issues on Mac


BIG DISCLAIMER THIS IS POORLY WRITTEN AND ONLY APPLIES TO ATOM. AS I HAVE SAID BEFORE I WOULD RECOMMEND VS CODE SO BEAR WITH ME WHILE I GET THE VSCODE VERSION DONE

Git was originally made to be used with a command line or terminal, but it has also been adapted to more simplified use through Graphical User Interfaces (GUIs). The GitHub tab on the right side of Atom/VS Code is one of these. Or rather the Git tab is, and the GitHub tab just provides us some info about our repo online. So let's click on the little `Git` button in the bottom right corner. You should get an interface that is split into 3 areas. The top one shows you which files in your repo have changed. If you open the README.md file, add some text and save, it should appear in the list with a yellow icon. This means Git has found changes to files and is ready to save them in a special way we call `Commits`. To move on to the next zone we need to `Stage` our changes. Do this by clicking the `Stage All` button in the upper right of the first zone. This should move any changes files down to the second zone. From there we are ready to make our first `Commit`. In the final box where it say `Commit message` add a message. Fir this lets just use something like "Learning git" or "testing commit". One that field is filled press `Commit to master`.

There is one final step to this before we will see any changes on the web interface for our repo. Open the command pallet with `Ctrl-Shift-P` and type `Push`. The first option should be `GitHub: Push`, select it and there should be a little indicator in the lower right that says `Pushing`, once it is done refresh the webpage for you repository and you should see the changes you made to the README.md file.

Now let's say I make changes to the lessons, or add a new one. How are you going to get these updates? Well we just used the `Push` command to make sure GitHub had all our changes, so we are going to use the `Pull` command to make sure we have any changes from another repo on GitHub. Make sure you have the folder for the course repo selected and then run the `Pull` command in the same way you ran the `Push` command. This also goes for your own repo. I like to make sure to run the `Pull` command every time I sit down to work on with a repo for a bit. Since we are mostly working with a repo run by a single person it's not as big a deal, but making sure everything stays synced for larger teams can involve a lot more complexity I will not get into here.


### Using a Repo
All of the commands and steps you just learned are outlined below.

- `Pull` - run the pull commands before you start working to make sure everything is up to date
- `Stage All` - press this button when you have made changes to files and want to get ready to send them to your repo
- `Commit message` - Add a message to remind you what changes you made
- `Commit to master` - Adds the changes to the repo version history
- `Push` - sends changes to your GitHub repo
- Repeat whenever you make edits

It is worth noting you do not need to do this each time you save a file, but if you want to you could. As you make changes to multiple files you will see them added to the `Unstaged Changes` area. Sometimes I will only commit changes to a single file, sometimes it will be tens, and I'm sure in certain projects it's hundreds at a time. We will hit a point where we will have to commit fairly frequently to test our website, but that will be minimized with some of the setup we did last lesson. That's basically my general workflow, no matter what project I am working on. Pull, edit, commit, push. Don't worry about making tiny commits either. I have committed changes that were literally a single letter. These will happen and they are okay.

<br>

### Markdown
First things first I am going to give a link I had in the first lesson that will be your friend for the near future,
- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

This file will basically teach you everything you need to make our first website, but for now we aren't getting into that. Instead we just want to learn Markdown. We went over in lesson 1 how to open the Markdown preview with `Ctrl+Shift+M`.

Make a new file in the repo we made in lesson 1 by right-clicking on the main folder and selecting `New File` then naming it whatever you want, just make sure it ends in `.md`. You can explore the cheat sheet and these lesson files to begin to understand what you can do with Markdown. The most general commands are below and in general require a space after them.
- `# `   - This makes the text after it be formatted as `Heading 1`
- `## `  - This makes the text after it be formatted as `Heading 2`
- `### ` - This makes the text after it be formatted as `Heading 3`
- `- `   - This make a standard text bullet
- `[TEXT](LINK)` - This allows you to embed links in your text, simply replace `TEXT` with what you want the link to say and `LINK` with the url you would like it to take you to
- `![TEXT](LINK)` - This is what you do for images. The `TEXT` will not actually display anywhere, and the `!` renders the image inline rather than just providing the link

Using these commands do a bit of writing in the file we just made, or in the README.md of your repo and use the preview to see what your changes will produce. GitHub is pretty cool because that README.md file will display as the rendered Markdown right on your repo's page. I used this to make my first portfolio with a link I could share and put on job applications.

Between now and the next lesson fiddle around with Markdown a bit. Try to make the beginnings of a portfolio or home page. Feel free to check out the first version of my portfolio, which eventually became my home page, at the link below. The README.md file is what was eventually displayed as a webpage.
- [Portfolio v1.0](https://github.com/thomas-williams/portfolio)

A reminder that you can add any file to a repository. Try making a new folder in your repo and adding some pictures to it, then come back to Atom and look at the Git sidebar. If you go look at my first portfolio you can see I did this, and then could link to those images. I link to them in a way we will learn a little later, but the general process is the same.

<br>

## Review
- Git workflow
- Using Git in Atom
- More complex Markdown

## Up Next
### Lesson 3: GitHub Pages and Your First Website
