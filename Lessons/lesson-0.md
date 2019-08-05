# Lesson 0
## Background
This file is actually going to mark a fairly large remake of this project. I am going to be remaking a lot of it for a few reasons. Namely I have learned about what I am actually trying to achieve, but also about better ways to explain it. This ties directly into the first big change. The first lesson is going to trim a lot of the fat from the previous first lesson. I realized a lot of the set up could be avoided, and the entirety of the first main portion of this project can be done right in a browser, no need to even bother with all the stuff I originally said to install. Now if anyone following this plans on really getting into it, the original lessons will come back eventually, but in a heavily edited form. For now I'm going to really simplify things, essentially providing a completely free web hosting platform with web based editor. To use some lingo, I have figured out an OpenSource equivalent to services like SquareSpace or WordPress. That claim does however come with a bit of a disclaimer. Getting the same complexity out of sites made with my method takes some learning, but will be forever free, so long as you put in a little effort and put up with a slightly less glossy editor, you can get the same results for free. This does not mean it will be hard to use, in fact I personally find the opposite to be true. Stripping away a lot of the features those sites try to push on you might streamline the process from design to live website, and make you think harder about smart design choices. I am beginning to ramble so lets move on to the actual lesson.

<br>

### Part 1 - From Nothing to Website in 10 Minutes (not counting reading time)
I know that's a big claim, but it's the truth. The website we make in 5 minutes obviously will not be fully populated with all the custom content you can dream of, but it will be a functional page you can add to over time. SO let's dive in.

#### Step 1 - GitHub Account
To start you'll need to go make a GitHub account if you do not already have one. You can use the link below to go right to the sign up page
- [GitHub sign up](https://github.com/join)

#### Step 2 - Make a Repo
I will get into all the terminology of GitHub in the future, but for now know that "Repo" stands for repository, which is essentially a fancy collection of files.
- Once you have made an account and signed in, go to the GitHub home page and click the the `+` icon in the top right
- Then select `New repository`
- One the next page enter a name for your repository, something relatively simple, like `personal-site`
- Enter a description if you'd like, again keeping things quick
- Check the box that says `Initialize this repository with a README`, which I will get into in detail later
- Finally click `Create repository`

#### Step 3 - Repo Navigation and Markdown Intro
After clicking `Create repository` you should automatically be taken to your new repository's main page. You will see a few things. Toward the top there will be a bar with tabs, `Code`, `Issues`, `a bunch of others`, and `Settings`. The ones I types out are the ones that we will use the most, and even then issues will only really be used later in the tutorial. Below that bar you will see the description of your repo, and then a few lines below that an area that lists any files in your repo, which should currently only contain a file called README.md. For now this file will become our website. As we develop more complex websites that will change, but we are keeping things simple. Just below the file list you should see a display area that has the name and description of your repo in it. This area is actually displaying the contents of `README.md` in a specially formatted way. If you have not already click the button that says `raw` at the top of this file in the GitHub viewer. You should see something that looks like this:

```
# Lesson 0
## Background
This file is actually ...
```
This is something called Markdown and it is wonderful. Without going too into detail, Markdown is a styling language, used to easily format text in dead simple ways. From the file you are looking at you should begin to be able to pick up what symbols indicate what formatting. For more detail and future reference check out the links below.

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


#### Step 4 - Editing README
So with that new knowledge, and mostly with the cheatsheet, let's head back to your repo and click the little pencil icon just above and to the right of where your README is displayed. In the editor that comes up you will again see some of that Markdown stuff. This is where the beauty of GitHub, and the system we will be using, really begins to show. Right from this webpage you can add just about any content to what will become your website. Don't go too crazy just yet, and instead just add something along the lines of the following:

```
# REPO NAME
DESCRIPTION

## HELLO WORLD 👋
```

After that scroll to the bottom and click `Commit changes`. You don't need to worry about the boxes above the button just yet. You should be returned to your main repo page and you can now see that `HELLO WORLD 👋` has been added to your README displayed here. That isn't exactly a live website like I promised though.

#### Step 5 - GitHub Pages
This is the final step, and it is almost scary how easy it is to take what we just made and turn it into a live website.
- From your main repo page click on settings
- Scroll until you see a section called `GitHub pages`
- Click on the drop down menu that says `None` and select `master branch`
- You should see a blue area that says `Your site is ready to be...` followed by a URL
- Wait a moment and then refresh the page until that blue area is green, and then click the URL
- Welcome to your own personal website, hosted completely for free


### PART 2 - Adding Some Complexity
Now I realize what we just made isn't the most eye catching website, but it is a page you can add whatever you want to, and is free, whish are the two primary goals of this whole project. As you learn more GitHub pages will become an extremely powerful platform, but as I said in the intro, you have to be willing to learn a little to make us of its potential. One of the first things that you should learn is how to add pictures to your site. To do this we are going to make a new folder that we can upload images to, and then link to in our README.

- From the main page of your repo click the `Create new file` button
- On the new page in the box that says `Name you file...` type `images/`, which will add the word images in next to the name of your repo to the left of the input box
  - GitHub is a little funny and wont let us just make a folder, so we have to make a file in this folder
- Name the file `image-list.md` for now
- Click `Commit changes` like before
- Now from within that folder click the `Upload files` button and follow the prompts to add an image file
- Again, click `Commit changes`
- Back to our main page click the pencil to edit the README and add `![IMAGE NAME](/images/IMAGE-FILE-NAME)` where the image file name is the compete name of the file you just uploaded. Something like `cat-image-1.jpg`
- `Commit changes`
- You should now see your images in your README on the main repo page, and if you wait a moment it should also appear on the page at the URL from the last section

<br>

### PART 3 - Looking Forward
In the next section we will begin to really flesh out this workflow,a dn learn a bit more about GitHub and the underlying system Git. We will begin to learn about some of the tools we will use to interact with our files in a more powerful way, which will allow us to make sure we like the changes we have made before we actually push them to the live site. This will involves learning a bit more "code" although things will stay relatively simple for the time being.

<br>

## Review
- GitHub setup
- Basic Markdown
- Making your website
- Editing your site and adding images

## Up Next
### Lesson 1: Moving to a "Real" Editor
