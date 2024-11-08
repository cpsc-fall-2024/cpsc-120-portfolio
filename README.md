# Reflection & Making a Personal Portfolio

The 16 week long semester is almost over and you have accomplished so much! You learned about problem solving and programming and created a portfolio of programs that demonstrate your competency and along the way you learned and improved your note taking and team work skills.

Our goal is to create an online resume or personal homepage which shows off some of your achievements. Ideally, you will add to this portfolio as you work on school related projects as well as your own personal projects.

If you do not have any experience or knowledge on how to make a web page, this will be your opportunity to learn how to create one. Over time, you can revisit, improve, and customize your web page to make your own personal corner of the Web stand out.

We shall use GitHub's service called [GitHub Pages](https://pages.github.com/) to host your web page in a GitHub repository. We shall use [Markdown](https://en.wikipedia.org/wiki/Markdown) instead of HTML to simplify creating our web pages.

There is nothing to submit via Canvas. If you completed the portfolio, then when you reach the end of _Step 3: Your Home Page_ you will be able to view your webpage by visiting `yourusername.github.io` in your web browser and see your portfolio. We will view this web page after the deadline and assign a grade.

**This is an individual assignment. Each student must create their own portfolio. This is a graded assignment. There is a rubric at the end of the document which will guide how your assignment is scored.**

## Background & Motivation

Sharing the fruits of our labor is an important part of the learning process and the mentoring process. To this end, it is beneficial to create our own little corner on the Internet where we can show off some of the cool things you have done.

GitHub is a lot more than just uploading and downloading code.

Consider where you will be in a few years. You may be looking to collaborate with some friends on writing software to address a family business need. Perhaps you will be applying for jobs and they ask you for your GitHub link. Invariably, your name comes up in a conversation and someone Googles your name - up comes your GitHub page. The next thing you know you've got a job iterview, an internship, or that independent study project you wanted to do gets approved.

Consider this as a first draft of what shall be many drafts of your personal home page. On this page, you can share a little bit of information about yourself and some of the topics you are interested in. As your programming skills evolve, you can add and remove projects to show your latest interests and achievements.


## Markdown

We shall start by creating a personal web page using [Markdown](https://en.wikipedia.org/wiki/Markdown) instead of HTML. Markdown is a human readable, lightweight markup language with a syntax that is easy to learn and use. Markdown is the markup language that your instructor uses for all the `README.md` files. The Markdown project's home page is https://daringfireball.net/projects/markdown/.

Everything you need to know can be learned from this Markdown cheat sheet, https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet and by looking at README.md files from past lab assignments. (Even this one!)

Students who are interested in having a page that looks fancier can use [HTML](https://www.w3schools.com/html/), [CSS](https://www.w3schools.com/css/default.asp), [JavaScript](https://www.w3schools.com/js/default.asp), [images](https://wordpress.org/openverse/), etc. however this is not required.

## Step 1: URL and Lab URLs

A _universal resource locator_ or _URL_ is the term we use to identify unique addresses on the World Wide Web. Casually in conversation, we may refer to a URL as a _link_. GitHub's URL or link is http://github.com and CSU Fullerton's is http://fullerton.edu.

Think about your three favorite lab exercises that you completed this semester. You may have a hard time remembering each one so review the labs that you have on your computer.

In case, you no longer have copies of your labs on your computer the links to each Canvas lab assignment is given below. **Bookmark or write down your favorite lab repositories or lab parts to make it easier to find your favorite labs.**

<!-- comment: short cut to build the list using mshafae's canvas-utils is
COURSEID="3453286"
count=1
for i in `./bin/asgts.py -c $COURSEID ls | egrep "^[0-9]{8} \"Lab [0-9][0-9]?\".*$" | cut -f 1 -d\ `; do
    echo "* [Lab $count](https://csufullerton.instructure.com/courses/${COURSEID}/assignments/$i)"
    count=$(($count + 1))
done
` -->

* [Lab 1](https://csufullerton.instructure.com/courses/3453286/assignments/37261539)
* [Lab 2](https://csufullerton.instructure.com/courses/3453286/assignments/37261543)
* [Lab 3](https://csufullerton.instructure.com/courses/3453286/assignments/37261545)
* [Lab 4](https://csufullerton.instructure.com/courses/3453286/assignments/37261546)
* [Lab 5](https://csufullerton.instructure.com/courses/3453286/assignments/37261547)
* [Lab 6](https://csufullerton.instructure.com/courses/3453286/assignments/37261548)
* [Lab 7](https://csufullerton.instructure.com/courses/3453286/assignments/37261549)
* [Lab 8](https://csufullerton.instructure.com/courses/3453286/assignments/37261550)
* [Lab 9](https://csufullerton.instructure.com/courses/3453286/assignments/37261551)
* [Lab 10](https://csufullerton.instructure.com/courses/3453286/assignments/37261540)
* [Lab 11](https://csufullerton.instructure.com/courses/3453286/assignments/37261541)
* [Lab 12](https://csufullerton.instructure.com/courses/3453286/assignments/37261542)

## Step 2: Reflection

**Before continuing: please have your three favorite projects selected.**

For each of your favorite labs, write down in your notebook **at least 3 sentences** why that lab is your favorite and what you learned. Your narrative must be **no less than 30 words in length**. Be specific about why you like the lab and what you learned. **It is part of your grade for this assignment!**

For example, in [Lab 07](https://csufullerton.instructure.com/courses/3411194/assignments/34637727) there were two parts. The first part was writing a program that calculates the number of days between two dates and the second part calculated the value of a Blackjack hand. One could write:

> Lab 7, part 2 was a favorite because I was always curious about how the game Blackjack works. I was able to write functions for the first time that calculate the correct value of a Blackjack hand no matter how many Aces were dealt.

Carefully and considerately write your reflection about your three favorite labs. Your spelling and grammar matter. Remember that each narrative reflection must be **at least 3 sentences** long. Your reflection must clearly express why that lab/part is your favorite and what you learned. Your narrative reflection must be **no less than 30 words in length**. Be specific about why you like the lab/part and what you learned.


## Step 3: Your Home Page

**Before continuing: please have your reflections from Step 2 written down and ready to be published on the web. Check your spelling and grammar, use tools like Google Docs, Microsoft Word, and Grammarly to improve your writing.**

We will use [GitHub Pages](https://pages.github.com/) to host and serve your home page. GitHub Pages is a service where you create a git repository that contains HTML, CSS, JavaScript, images, etc. for your own personal home page and GitHub will serve those pages for you at no cost.

To create your own home page, follow the instructions given on https://pages.github.com. Make sure the _User or organization site_ button is selected and not _Project site_.

**Use the GitHub username that you have used in CPSC 120A. Using a different GitHub username will result in a missing assignment and a 0 (zero) grade.**

1. Log into GitHub, https://github.com
1. Create a new repository for your web pages. The name of the repository is very important. You must use your GitHub username as part of your repository name. For example, my GitHub login is `mshafae`. I created a new repository, https://github.com/new, and named the repository `mshafae.github.io`. **Replace `mshafae` with your GitHub username.**
1. We are using the _terminal git client_. Clone the repository to your computer using the `git clone` command. **Replace `mshafae` with your GitHub username.**
    ```sh
    git clone https://github.com/username/mshafae.github.io
    ```
1. Change directory to be inside your repository, `cd mshafae.github.io` for example. In this directory, using your text editor, VS Code, create a file named `index.md`. In the terminal, you can use the command `code index.md` and it will create the file `index.md` and open it for editing.
Start by adding the following into `index.md` and replace **your_username** with your GitHub username, **Your Name** with your name, and **your_major** with your major.
    
    Use the reflections that you wrote in the previous step to create a bulleted list of at least three projects from CPSC 120. Make sure that the links you use are correct by clicking the links and verifying that they load correctly. The previously used example is shown below.

    ```
    # Hello World

    This is my home page! My name is Your Name and I am a student at [Cal State Fullerton](http://www.fullerton.edu/) and my major is your_major.

    ## Computer Science Projects

    My GitHub page is http://github.com/your_username.

    ### CPSC 120

    * Lab 7

        Lab 7, part 2 was a favorite because I was always curious about how the
        game Blackjack works. I was able to write functions for the first time
        that calculate the correct value of a Blackjack hand no matter how many
        Aces were dealt.
    ```

    The above text will transform into HTML when it is saved to GitHub and will look like the following block of text.

    # Hello World

    This is my home page! My name is Your Name and I am a student at [Cal State Fullerton](http://www.fullerton.edu/) and my major is your_major.

    ## Computer Science Projects

    My GitHub page is http://github.com/your_username.

    ### CPSC 120

    * Lab 7

        Lab 7, part 2 was a favorite because I was always curious about how the
        game Blackjack works. I was able to write functions for the first time
        that calculate the correct value of a Blackjack hand no matter how many
        Aces were dealt.


1. Save this file and add it to your repository with the `git add` command.
    ```sh
    $ git add index.md
    ```
1. Commit the changes to your git repository and push the changes back to GitHub using the `git commit` and `git push` commands. **Very important - the instructions on GitHub are slightly off. Make sure you use the `git branch` and `git push` commands below.**
    ```sh
    $ git commit -a -m "Initial commit of my home page."
    $ git branch -m main
    $ git push -u origin main
    ```
1. If you have successfully created your `index.md` file and pushed it to GitHub, you can visit your own GitHub Pages URL to view your newly created page. For example, if your username is `mshafae`, then you would type `https://mshafae.github.io` in the address box of your web browser. Replace `mshafae` with your GitHub username.

### Common Problems

#### Master Branch
A common problem is that Ubuntu 20 and other systems uses an older version of `git` than what GitHub expects. Since version 2.28, `git` no longer uses a hard coded default branch name called `master`. Instead, GitHub expects the default branch name to be `main`. The solution is to rename your branch.

For example, if you try to push your repository and you see an error message simiar to the following:

```sh
$ git push
Username for 'https://github.com': mshafae
Password for 'https://mshafae@github.com': 
No refs in common and none specified; doing nothing.
Perhaps you should specify a branch such as 'master'.
Everything up-to-date
```

Another example of the same problem is the following:

```sh
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/mshafae/mshafae.github.io.git'
```

Both of these errors mean that you have your default branch named `master`. To solve this problem, run the following commands:

```sh
$ git branch -m main
$ git push -u origin main
Username for 'https://github.com': mshafae
Password for 'https://mshafae@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 908 bytes | 908.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/mshafae/mshafae.github.io.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```

This will resolve the problem and you will have updated your repository.

#### Wrong Filename or Not Using Markdown

Do not use the filename `index.html` or `Index.html`. For this exercise, you are _required_ to use Markdown.

If you created a file named `index.html`, please rename it. You can do this using the `git` command. First, make sure you do not have the file open in your text editor, VS Code. Next, make sure you have committed all your changes to your repository before renaming the file. For example, the following series of commands will work in most cases to rename a file from `index.html` to `index.md` when it is already part of a Git repository.

```sh
$ git commit -a -m "Checking in all files."
$ git mv index.html index.md
$ git commit -a -m "Renamed index.html to index.md"
$ git push
```

#### Misspelling `index.md`

Double check to make sure the name of your indes file is `index.md`. It is a common mistake to accidentally name the file `Index.md`, notice the capitalized letter _i_. The file name must be all lower case letters. The correct file name is `index.md`.

#### Try One More Commit

Occasionally, your `yourusername.github.io` will continue to show a 404 error message after you have pushed your first change to `index.md`. Pushing a second change to `index.md` seems to spur GitHub Pages to serve your page properly. So if you have double-checked that your repository is named correctly, public, and  your `index.md` file is named correctly, and you are still getting a 404 error message, try making another change to `index.md`, push your change, wait three minutes, and reload the `yourusername.github.io` page. 

#### Still Have Problems

If your changes did not appear online, then
1. Make sure you have the correct URL, remember it is github.io not github.com
1. Make sure you have committed and pushed your changes, look at the repository on GitHub.com to make sure the changes are there. Use `git status` to check the status of your files and repository.
1. Retrace all your steps

If you continue to have problems, please ask your instructor for help.

# Extras

Extras are welcome and encouraged however they are not required. Your grade will not improve or suffer should you choose to or choose not to include any extras. Your grade shall be calculated using the rubric given at the end of this document.

## Images
Use some images to show off who you are and what you have accomplished. For example, the images you created in Labs 10 and 12 are beautiful and you can embed them into your page very easily.

For example, let us image that you have an image named `gradient.png` and we want to place the image in this page.

1. Create a directory in your repository named images using the `mkdir` command.
    ```sh
    $ mkdir images
    ```
1. Next identify where you have the file `gradient.png`. Let us assume that the file is located in `/home/mshafae/cpsc120/cpsc-120-lab-10-mshafae/part-3/gradient.png`. Copy the file into your new `images` directory.
    ```sh
    $ cp /home/mshafae/cpsc120/cpsc-120-lab-10-mshafae/part-3/gradient.png images
    ```
1. Add the `images` directory to your repository, including the image you just copied using the `git add` command.
    ```sh
    $ git add images
    ```
1. In the file `index.md`, using VS Code, add Markdown text to embed the image into your page. This will place the image in the file when you view it through your web browser.
    ```
    ![The gradient image from Lab 10](images/gradient.png)
    ```
1. Save the changes you made to `index.md`, commit and push your changes.
    ```sh
    $ git commit -a -m "Added an image to my index.md"
    $ git push
    ```
1. If you have successfully embedded an image into your `index.md` file and pushed it to GitHub, you can visit your own GitHub Pages URL. For example, if your username is `mshafae`, then you would type `https://mshafae.github.io` in the address box of your web browser. Replace `mshafae` with your GitHub username.

Below is an example of how to embed an image into this page using the Markdown code `![Example gradient image.](images/gradient.png)`.

![Example gradient image.](images/gradient.png)

## GIF Screencasts

You can make your links to your projects more interesting by using animated GIFs of your terminal. You can create animated gifs using [ttyrec](https://en.wikipedia.org/wiki/Ttyrec) with [ttygif](https://github.com/icholy/ttygif) or [terminalizer](https://www.terminalizer.com). On Ubuntu Linux, you can easily install packages `ttyrec`, `ttygif`, and `xdotool` with the command `sudo apt install ttyrec ttygif xdotool`. Below is an animated GIF of the installation process.

![Animated GIF of the terminal output from the commands `sudo apt update` and `sudo apt install ttyrec ttygif xdotool`.](images/ttyrec-install-small.gif)

Once you have the tools installed, you can create GIFs demonstrating your programs like the one below demonstrating a _Hello World!_ program that we wrote back in Week 1.

![Animated GIF of the terminal output compiling a C++ program and then executing the binary which prints the messaage "Hello World!".](images/clang-hello-world.gif)

If you run into a problem where the `ttygif` program throws an error and says `Error: WINDOWID environment variable was empty.`, then there is a simple fix for Ubuntu Linux using `xdotool` given on the [`ttygif` README](https://github.com/icholy/ttygif/blob/master/README.md).

If you're on Ubuntu, you can use `xdotool` to find the WINDOWID
``` sh
$ sudo apt-get install xdotool
$ export WINDOWID=$(xdotool getwindowfocus)
```

Paul Czarkowski has some [brief instructions](https://medium.com/@pczarkowski/how-to-make-an-animated-gif-of-your-terminal-commands-62b08dfb6089) on how to create an animated GIF and then optimize it using [`gifsicle`](http://www.lcdf.org/gifsicle/) to make the file size smaller.

## Custom Domain

If you really would like to get fancy, you can [register a custom Internet domain and have it map onto your GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages). 

# Rubric

This exercise is worth 30 points. There is no programming in this assignment.

A submission that does not use the GitHub username the instructors have on record or is not accessible using GitHub Pages shall be considered missing and receive a 0 score.

* Repository: (6 points) Your repository is correctly named and can be accessed using GitHub pages. For example, if your username is `tuffy`, then the repository name is `tuffy.github.io` and the index page can be reached by visiting the URL `https://tuffy.github.io/`.

* Index File & Student Information: (6 points) An index file exists and can be viewed using a web browser from GitHub Pages. The index file is written in Markdown. The index file contains at a minimum, the student's name, the university the student attends, the student's major, and a link to their GitHub profile. Students are urged to use the template provided in this document.
    Index files that are not written in Markdown shall receive 0 points in this category.
    Index files that are missing in part or in whole the required student information shall receive 0 points in this category.

* Favorite Labs and Reflection: (6 points each; 18 points total) The index file must clearly identify a minimum of three lab assignments from the current CPSC 120 term that were authored by the student or a student team that the student was a part of. Each lab must have a grammatically correct and meaningful reflection. Students are urged to use the template provided in this document.
    3 points are earned for identifying what the student liked about the lab for each reflection. Omitting what was liked about the lab forfeits 3 points.
    3 points are earned for identifying realized learning objectives for each reflection. Omitting what learning objective was realized forfeits 3 points.
    Missing reflections will loose 6 points each.
    Reflections which contain gratuitous grammatical or spelling errors will loose 6 points each.

### Unpublishing

Should you wish to unpublish your portfolio from the World Wide Web, you can [remove your repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/deleting-a-repository) after you have received a grade for the assignment. Please retain a copy for your records.