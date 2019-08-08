# LESSON 1

## Coding and GitHub Basics
This lesson runs you through the basics of a code editor and GitHub. You will be getting set up with an account, making your first project, and learning the very basics of a language called Markdown to jump start your coding chops, as well as get a page of sorts going very quickly. Each section will have some text describing the process and then links I have found that are particularly helpful or relevant.

<br>

### Coding Environment
First things first we need a space we can start to work, namely because these lesson documents wont be able to be viewed in all their glory without a nice environment, so here we go, my top recommendation and then a few alternatives. In prepping for the future I would suggest VisualStudio Code if you want to eventually get into more complex work, and there is a version of this tutorial that if focused on VS Code, but for now we are going to use Atom.

#### Atom
Atom is great and I am honestly still learning it, but it is so easy to learn that's really not an issue. Atom is made by the developers of GitHub, so it plays very nicely with it and by extension Git, which we will be using a lot. For total beginners I would maybe lean toward Atom but in the long term would highly recommend VS Code. However VS Code will require a bit more setup that I will not be going into just yet, so if you'd like to try to tackle that on your own feel free to do so, just know that this tutorial currently contains instructions for Atom.

#### VS Code
VS Code is honestly a bit more powerful than we need for a while, but it will scale really nicely with the complexity of what we want to be doing and beyond. You could theoretically do this all in the most basic text editor, TextEdit on Mac and Notepad on Windows, but that becomes a pain very quickly. There are some more options that I have fiddled with and they are below.
<br>

#### Editors
- [Atom](https://atom.io/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/3) is essentially a plain text editor with a few additional bells and whistles, people that are very new to this will find it harder to use just a plain text editor, but if you're already comfortable with Git and HTML this could be a could fit and you probably do not need this tutorial
- [XCode](https://developer.apple.com/xcode/) is also an option on Mac, but I don't have much experience with it at the moment because I am on a PC
- If you want to go really hard and do this all from a terminal, you probably don't need my help at all, but [Vim](https://www.openvim.com/) is a standard editor, but will need to be coupled with other software to view files as they would be presented online as well as a bunch of other CLI tools and knowledge

Download the editor you would like and install it. For this I am going to be using Atom for the reasons mentioned above, but I also whole heartedly endorse VS Code, and used it for a long time.

###### NOTE: If you are using VS Code skip to the 'VS Code Basics' section for that, if you are using Atom just keep going to the next section after finishing this one. There is currently only an Atom tutorial because I just haven't gotten to VS Code, but I personally use VS Code and while it is a bit more complex I would recommend learning it as it will carry you much further. Pretty much all of the Atom basics apply to VS Code
<br>
Setting up the environment will be somewhat different for each application, so I will run through what you need for Atom and VS Code (at least to start), and we will periodically add on extensions as we need them.

If you are using Atom we only need one for now and we wont even use it for a bit, but it will be nice to already have it.
- [HTML Live Preview](https://atom.io/packages/atom-html-preview)

If you are using VS Code you will need a few right away.
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver) - we wont be needing this for a bit, but we may as well get it now

<br>


### Atom Basics
Honestly there isn't much to do here, Atom runs pretty darn well out of the box, and takes little configuring. I would explore the main settings a bit, maybe look at the themes to find one that is easy on your eyes, and fiddle with word wrap, which you can search for. I usually like word wrap because it reduces the amount of side scrolling I do, but other people like how they can see the indent structure of their file better. Two great resources to learn all the ins and outs of Atom are provided below.
- [Atom Flight Manual](https://flight-manual.atom.io/)
- [Atom Docs](https://atom.io/docs)

There are two key features I am going to focus on that are pretty much core to the whole process and will be found in all good editors, as well as a third that is a little unique to Atom that I thoroughly enjoy.

The first I also go over in the VS Code section, and I wrote that first, so if you're really interested in why I like it go check that out in the section just after this for a little more info. The tool here is called 'Tree View' and it can be toggled from the `View` menu or with `Ctrl+\` on Windows and `Cmd+\` on Mac. This should bring up a panel on the right, but to get the most out of it we have one more step. Under the `File` menu select `Open Folder...` and browse to where this file is currently stored.

The next important tool is something that comes built right into Atom. This is the Markdown preview. As you might have noticed this file has some random `#s` and some other odd symbols scattered throughout it. This is a Markdown file. In fact in the browser you just opened on the left, you should see something like `lesson_1.md` and if you click on the file Atom will bring up an editor and should provide some nice color highlighting of all those symbols. This is because Atom excels at handling Markdown and already has a suite of tools to work with it built in. The first of these tools we have seen is the highlighting. The second that we will use is preview I mentioned. To open this type `Ctrl+Shift+M` on Windows and `Cmd+Shift+M` on Mac. This should also trigger another nice feature of Atom, the split view editor. On the right you should now see a file that has all the same words as the one on the right, but non of the odd symbols and has some nice formatting, like font size and links and some code snippets. This is what Markdown looks like when it is interpreted and rendered by something that knows how to. The basic text editor you were using before to read this file didn't know how to display it, at least not right off the bat.

You have perhaps noticed the `.md` at the end of the file name for this file. That means it is a Markdown file. Markdown is a formatting language that allows you to quickly and easily generate nicely formatted text for various uses. You have also probably noticed some odd characters throughout this file like `<br>` and `#`. These are the clues that Atom will use to show us what this file really looks like. It you press `Ctrl+Shift+M` on Windows and `Cmd+Shift+M`. This should open a new editor that has the same words as this document but looks very different. This is rendered Markdown, you can begin to see how all those symbols tell Atom what to do with the text. For more info check out the resource below.
- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

The final feature really leads us into a different section, but I will mention it now and we will sort of come back to it in a bit. Under the same `View` menu you will see a `Toggle GitHub Tab` option, which can also be triggered with `Ctrl+Shift+8` or by the small button in the lower right. Open this and hopefully you will be greeted by a login button, head on to the next steps and we will come back to this, but basically the system we will use to host and track all our files integrates directly into the side of Atom and that is wonderful.

<br>

### Make a GitHub Account
Git is one of many version control softwares out there, and most likely the widest used. It is incredibly versatile and powerful, but also keeps things simple enough for the average user to be able to get a lot out of it. Git will allow us to keep track of the changes we make over time, and if things go south will let us easily recover older versions of our work.

GitHub is in essence a web interface for Git, which a bunch of other features many of which we will use and get to know well, but our time with Git starts with finding a way we can easily interact with it on our computers.

For the most part just follow the steps at the link below to create a GitHub account, which will probably involve confirming an email address and a few other steps. It's pretty easy, and if you really need instructions they are basically built right into the page, and once you are logged in GitHub has some good tutorials.
- [GitHub Sign Up](https://github.com/join?source=experiment-header-dropdowns-home)

Once made explore GitHub a little, as you open new pages little tutorial bubbles will pop up, they are great, but a quick google can find you tons more tutorials that are as complex or simple as you want. I wont really provide an extensive one here, but I will run you through just what we need as we need it.

<br>

### Make Your First Repo
Once you are logged in click the '+' icon in the upper right corner, and then select 'New Repository'. Fill out the text fields, which should be something like:
- Repository Name
- Description
- Initialize with README (I'd recommend doing this)
- Git ignore and license can be ignored for now

When you are satisfied with the various fields click the 'Create Repository' button. Repositories are cheap and can be easily deleted, so we aren't necessarily going to use this specific one for much beyond this initial tutorial. For now we have a bit to do with it, but to do that we need to be able to access it on our desktop, where VS Code can interact with its file structure. This is where we will bring everything we just learned together.

<br>

### Finishing Environment Setup
Now we can bring it all together. You won't get a full explanation of what all the bells and whistles you are about to see will do, but that will be the beginning of the next lesson. We are going to make it so we can see and edit the contents of the repository you just made. To do that make sure you have selected the folder you opened on the left previously (now would be the time to start fresh and name the folder something like `learn_to_code` or whatever). Once in the folder we are going to open the command palette by pressing `Ctrl+Shift+P` on Windows and `Cmd+Shift+P` on Mac. This will open a box to type in, type `Clone` and the first result should be an option that say `GitHub: Clone`, select it. A new box should pop up with two fields. The first you'll need to head back to the GitHub webpage for your repo and clock the `Clone or Download` button on the right. This will bring up a small windows with a filled text box. Select the contents of the box and copy-paste them into the first line of the window we have open in Atom. For the second we need the path to the folder we are working in. For some reason Atom doesn't fill that automatically, which can be a bit of a pain. On Windows the best way to get this is to open a file browser and click in the path bar at the top of the window then copy and paste the text there. On Mac open the `Info` panel for the folder, and copy the contents of the `Where` line into the box. Worth noting this folder should be empty, and stored locally not in any cloud services and the like. Then click `Clone`. A new folder should appear in the tree on the left, but the window wont go away. As far as I know this is a bug, so just click cancel. You should now be able to expand the new folder and see another one named `.git` and potentially a file named `README.md`. These are the basic components of most repos, we will get to know them well.

NOTE: If you ever want to move the folder you are working in to a new location, do not just drag it, make a new one and clone the two repos into the new one, Git does not like being dragged around.

<br>

### Download the Course
I am going to distribute this course through a GitHub repo of my own, which you can clone into whatever folder you want to be working in. Which means you should have a top level folder that will then contain your person GitHub repo and mine that will contain the course materials. Follow the same steps you just did to clone a repo, using the link below as the source. You'll still need to get the exact link from the `Clone and Download` button.
- [Course Materials](https://github.com/thomas-williams/webdesign_for_artists)

<br>

## Up Next
### Lesson 2: Basic Git and Markdown
