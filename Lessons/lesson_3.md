# Lesson 3
## GitHub Pages and Your First Website
We will fire up a feature called `GitHub Pages` which will begin to show how we will be hosting this website. This is the underlying structure for this whole project, and allows for this to be done completely for free as long as you don't require a custom domain. We will get into custom domains later, but for now, we will just use `GitHub Pages` as is.

<br>

### Rename Your Repo
I know, I know, we just spent so much time getting it set up and now we have to rename it. This isn't very hard at all, and it's something I have used multiple times as I have made new version of my website. Go to you repository on GitHub and click on the settings tab toward the top of the page, and then change the text in the box to `USERNAME.github.io` where `USERNAME` is replaced with your GitHub username. I know this looks weird, but this is the first step to getting our website going. Once you have done this click `Rename`. You might get a warning about renaming changing the url, and we are about to fix that too, though in my experience sometimes everything still works just fine.

Now head back to Atom and you may as well give the `Pull` command a shot and see what happens. If you don't get any red error boxes, great, keep reading anyway, this is useful information. If you do get a red error box saying something about not finding a url then you've come to the right place. In the file tree sidebar on the left, open the `.git` folder that is inside the folder for your repository. This is where Git keep all its information about your repo. In that folder is a file name `config`. When you open this file you will see something that looks like this:

```
[core]
  repositoryformatversion = 0
  filemode = false
  bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[submodule]
	active = .
[remote "origin"]
	url = https://github.com/thomas-williams/webdesign_for_artists.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master
```

You might have already spotted the url field. We are going to change this to make sure it matches our new one. Which you can either type out, or copy from your GitHub page for the repo. Save the file and do a `Pull` command to confirm things are working.

<br>

### Enable GitHub Pages
Now the fun stuff begins. Back in the settings panel on GitHub, where you changed the name of your repo, scroll down until you see something that says `GitHub Pages`. There will be a drop down that says `None` and when you click it you will get 3 options: `master branch`, `master branch /docs folder` and `none`. For now select `master branch`, we will get into the other option later. Click `Save` to confirm your changes. A blue bar will appear at the top of the section that says `Your site is ready to be published at...`. After a minute and a page refresh or two that bar should turn green and say `Your site is published at...`. The link after should be clickable, and when you click on it you should see the README.md file you have been working with displayed. It won't be very pretty, and everything will be left justified, but it's a website that shows what you want for free. So that's the hard part done really.

<br>

### Multiple Pages
Many websites have multiple pages, and GitHub Pages handles this really well. This also ties into the choices we had in the GitHub Pages settings. If you want to experiment with multiple pages for your website I would recommend changing that setting to `master branch /docs folder` and then making a new folder in your repo named `docs` then putting your README.md file in there. For any future pages just make a new `.md` file with the name you want for the page and GitHub will automatically add `USERNAME.github.io/PAGENAME` as a subpage of your site. I don't particularly like any of them, but you can also explore the `Themes` section of the GitHub pages settings, which will make your Markdown a little nicer looking and usually centers the text.

You now have basically all the tools to get a rudimentary website off the ground. Try to build up a portfolio page and a home page (README.md) and make a link between them. Store these in the docs folder.
HINT: your Markdown links can be what is called relative, meaning it uses the page linked from as the starting point so all you need to write is the ending of the url (i.e. `[Portfolio](/portfolio)`).

This is what I used as a website for a few months while I learned more about this whole process and did other work, but I had a link I could give out at the very least. Maybe not the most professional looking link, but then again it's not the most professional looking website yet to be perfectly honest, but it works and hopefully you wont need to use it for months because of this tutorial.

<br>

## Review
- Setup GitHub Pages
- Learned how to do a basic Markdown based website

## Up Next
### Lesson 4: Adding Some Complexity and Early HTML
