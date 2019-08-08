# Lesson 1
## Spooky Scary Editors
This lesson will center around moving the process we established in the last lesson to a desktop based editor. Doing this will provide us with a whole bunch of benefits I will get into in more detail, but the short version is we will have much more control over what we are adding to our site with this new setup.

<br>

### Part 1 - Coding Environment
This might sound really intimidating, but you've already written some code, so the hard part is over. We are going to start with a fairly simple program called Atom, that plays nicely with GitHub because it is made by the same folks. There are some alternatives available, and I'll mention them briefly as well, but as a starting point Atom is good, and you can grow into the others if you'd like. If you already have a bit of experience and have a program you like, keep using that, familiarity is much more important than following this guide to a T. The two main editors that come to mind, and that I use myself, are Atom and Visual Studio Code. Eventually we will be installing VSCode, but Atom is a better environment to learn the basics in.

#### Editors
- [Atom](https://atom.io/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/3) is essentially a plain text editor with a few additional bells and whistles, people that are very new to this will find it harder to use just a plain text editor, but if you're already comfortable with Git and HTML this could be a could fit and you probably do not need this tutorial
- [XCode](https://developer.apple.com/xcode/) is also an option on Mac, but I don't have much experience with it at the moment because I am on a PC
- If you want to go really hard and do this all from a terminal, you probably don't need my help at all, but [Vim](https://www.openvim.com/) is a standard editor, but will need to be coupled with other software to view files as they would be presented online as well as a bunch of other CLI tools and knowledge

Unless you really want to use a different editor, go ahead and follow the link to download Atom, then move on to the next section.


### Part 2 - Atom Setup
Once the Atom installer has finished downloading run it and follow the prompts on screen to complete the installation. After that launch Atom and it should present you with the welcome file. This honestly isn't the most helpful at the moment, but is a handy resource that can be reopened at any time from the `Help`. Thankfully for our purposes Atom works very well out of the box, so very little configuration is needed, but lets keep the welcome guide open for now. I will explain most of the features we will use, but the Atom documentation is a great resource if you like to dig into Atom a bit on your own (which you should totally do, because I won't cover everything in this lesson).
- [Atom Flight Manual](https://flight-manual.atom.io/)
- [Atom Docs](https://atom.io/docs)

Even though Atom is pretty good as is, there are just a few settings I personally change right away. The first is the theme, which can be accessed from the welcome guide. Fin something that you like, and that's easy on your eyes. There's a lot of built in themes, so just click through and find your favorite. The other setting I personally use a lot is word wrap, which you can get to from the `view` menu. Word wrap will help with larger blocks of text, but when we get into files that have specific indentation structure it can also get in the way a bit. Basically fiddle with things as you find them. This is why the documentation and welcome guide are nice. As you use Atom you'll find your own preferred settings.

The final piece of setup we will do is signing into GitHub from within Atom. Since Atom is developed by the same people as GitHub this is very easy. Simply click the `GitHub` button in the bottom right corner. A tab will open on the right and it should have a `Login` button. Click that and follow the steps to sign in with your GitHub account.
<br>

### Part 3 - Accessing Your Repository
So now we have a nice looking space to work on our website, but how do we get access to what we already started on GitHub? Thankfully connecting Atom to our repository is quite easy. This is also a great opportunity to introduce an incredibly useful tool in Atom. The command palette can be opened by pressing `Ctrl+Shift+P` on Windows and `Cmd+Shift+P` on Mac. In the box that shows up you can execute tons of commands built into Atom, but for now we are going to use the `Clone` command. 
- type `clone` into the box and select the option that says `GitHub: Clone`
- Switch to your browser, navigate to you repository, and click the green `Clone or download` button then press `Use HTTPS`
- Press the copy button next to the text that say `https://github.com/USERNAME/...`
- Back in Atom paste that into the box the says `Clone From`
- In the `To directory` box enter a location you would like to store this project
  - This would be a great time to make a folder somewhere on your computer name `web-projects` or something like that, and make sure it's empty
  - This box wants the path to that folder, which can be a little tricky to get
    - On Windows navigate your file explorer to the folder and then click in the bar at the top to see the full path, should look something like `C:\Users\USERNAME\...`
      - Copy and paste it into the box in Atom
  - On Mac select the folder you would like you project to be in and press `Cmd+I` to open the info panel
    - Copy the contents of the `Where` line and paste them into the box in Atom
- Git is a bit finicky and really wants a fresh directory, anf for good reasons, so at the end of the folder path you just pasted in add `\personal-site`
- When you have everything entered click `Clone`
- After a moment you should see your files in the tree on the left side of the window
- Finally open your README file and make any small change
- Open the command palette, type in `markdown` and select `Markdown Preview: Toggle` which you show you what your changes will look like
- When you're happy with your changes, save the file
- Open the Git sidebar by pressing the button in the bottom right
- At the top of the panel you should see your README listed under `Unstaged Changes`
- Press the `Stage All` button just to the right of that
- Add a quick message in the `Commit message` box, and press commit
- To finish it all off, reopen the command palette and type in `push` the select `GitHub: Push`
  - Now if you check on your site after a minute you should see the changes you made

And there you have it. That's the basics of the editing process. Might seem a bit complex at first, but the more you run through those steps the easier it becomes. We will get into what is going on behind the scenes a bit later, but for now you can begin to build up your page and see if you can figure out how to apply what we did to add an image in the last lesson to this new setup.
<br>

## Review
- Installing Atom
- Atom setup
- Linking our GitHub repo to a folder on our computer

## Up Next
### Lesson #: NEXT LESSON
