# first-time-learners
A school project repository for teaching new Git users how to use git 

### Goals
In this tutorial, the aim is to create a simple repository in your own account, and practice some simple commands. In order to do this, you must first have Git Bash downloaded, accessible [here](https://git-scm.com/downloads), as well as have an acccount created, signup available [here](https://github.com/join?source=login).

### So, Why GitHub?
GitHub has a bunch of useful features that might help you choose it over other source and version control softwares. First up, Git gives you a place to not only store your files and work, but also a way to keep track of *who*, *when*, and *what* happens to your work. Looking at your Repo online or through a console allows you quick and easy access to both the most current version, as well as all the changes that led to that version.

Additioanlly, GitHub is also great for sharing and collaborating on work. It allows you to share your work easily, and for people to make their own changes, while still allowing you the control you need. Whether you're trying out GitHub for the first time, or writing code and collaboarting online, GitHub should be able to take care of your needs!

### First Steps
First things first, we're going to practice creating a Repository on GitHub. There are two ways to do so. The first is to simply launch up the aforementioned Git Bash (you can download it above), navigate to the folder you want to create your repository in, and use the command `git init <put your prefered name here>`. This creates a new repository locally, and you can then push that repository to Git using `git push`, but more on that later.

Alternitavely, you can create a new repository using the web. Navigating to your [home page](github.com), you can click on the new button in the top left corner of your screen, next to the word repository. Fill in the information and you're good to go.

### Cloning Your Repository
If you used the first method in the above section, you can skip this section, although if it is your first time, you should probably still go over it, as this is how you can work with other people's repositories as well. So, assuming you've created a repository on the website, you still won't have access on your computer. However, this is easily fixed by cloning. Start by navigating to the folder you want to clone your repository into. Next, open up the repository you want access to in your browser. Click the code button that appears in green in the top right of the overall code. Next, if you're using Git Bash, copy the https link (if you are using Linux, use the ssh link instead). Now, flipping back to your console, type in `git clone <your link here>`, and presto! Your repository will download, and you'll be able to modify things locally.

### Making Changes
At this point, you've created a repository, and have access to it locally on your machine. You can go ahead and create any file you want. Seriously, any file. I named mine "hello-world.txt". I'm original, I know. Anyway, for the purposes of the demo, the file name and changes don't matter, as long as you don't create an empty folder. Now, add your new file using `git add <your folder name here>`. You can also add everything you've changed using either `git add *` or `git add -A`. To make sure you've created something, type `git diff`, which shows you any unstaged changes. Assuming you've done everything correctly, you'll have one uncommited change. For those of us that are new, we commit changes with a short message describing the changes we made before we send those changes back to the main repository. Currently, because we added our file, we have one uncommitted, but staged (a.k.a. changes ready to be comitted) change.

### Git Commit and Push
Alright, we have a file we made, and some changes to push into our repository, so what do we do next? First, type in `git commit -m "<your message with changes here>"`. This commits your staged changes. You can, of course, just type `git commit`, however, you will be brought into your default editor to type a message, as we can't commit without recording what changes we made. At this point, we're ready to send our work over to the main repository. Using `git push`, send your work in. Assuming everything is set up correctly, this should push your changes and new files to your repository. Congratulations! You've succesfully made a repository! To get this work in the future (or the most up to date version of git), you can use `git pull` to grab any changes you're missing locally.

### Parting Notes
This guide is by no means comprehensive, but is rather intended to simply give you a taste of using GitHub. I have some useful commands, as well as a link to a more extensive beginner list of commands in the [here](/research_notes/'Git Commands.docx') in the research folder. Hopefully, you learned something useful and this served as a useful guide to jumpstarting your GitHub experience.
