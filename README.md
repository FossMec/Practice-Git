# GitHub
Andreessen Horowitz announced a whopping $100 million investment in GitHub this week. You can read commentary and speculation all over the web about what GitHub will do with the money, whether this was a good investment for Andreessen Horowitz and whether taking such a large investment is a good thing for GitHub.

But what the heck is GitHub and why are developers so excited about it? You may have heard that GitHub is a code sharing and publishing service, or that it’s a social networking site for programmers. Both statements are true, but neither explain exactly why GitHub is special.

At the heart of GitHub is Git, an open source project started by Linux creator Linus Torvalds. Matthew McCullough, a trainer at GitHub, explains that Git, like other version control systems, manages and stores revisions of projects. Although it’s mostly used for code, McCullough says Git could be used to manage any other type of file, such as Word documents or Final Cut projects. Think of it as a filing system for every draft of a document. 

This tutorial was actually made for highschool students to learn Git and Github. The actual tutorial is more difficult than this, you can find it [here](https://github.com/zulip/zulip-gci/blob/master/tasks/submit-a-pull-request.md). Over 200 students from all over the world completed this tutorial succesfully. This is a much easier version of that tutorial. If highschool students can do this task, you can too.

After completing this task, you would be finally ready to contribute to Open Source, so take your time and go through slowly and ask for help wherever you get stuck.

### [Read this article on Git to get a better idea on what Git is.](https://opensource.com/resources/what-is-git)

# Welcome to the tutorial of getting started with Git.

## Step 1
First and foremost, each of you will need a github account. It is fairly easy to register and similar to most of the other sites it offers login using your Gmail or other Social Network ID's.<br>
<br>
[Register Here](https://www.github.com/join) <br><br>
<img src="http://i.imgur.com/eeWND4m.png"></img>

Before continuing with the rest of the tutorial it is highly recommended that you go through the hello world tutorial offered by GitHub to get familiar with the github workflow.<br>
[Hello World Tutorial](https://guides.github.com/activities/hello-world/)


## Step 2
Before doing this step you have to install Git client in your system. 
<br>
<br>
<a href="http://git-scm.com/download/mac" target="_blank"><img src="http://image.prntscr.com/image/3db58348aece46f597293368e5a4bbd9.png"></a>
<br>
<br>
<a href="http://msysgit.github.io/" target="_blank"><img src="http://image.prntscr.com/image/eaafaf6722284064a1172c682ffb7466.png" t></a>
<br>
<br>
<a href="http://git-scm.com/book/en/Getting-Started-Installing-Git" target="_blank"><img src="http://image.prntscr.com/image/65ba4f31800e466082d05c3aaa89bd60.png"></a>
<br>
For most Linux systems Git is already pre-installed.
<br>
<br>
### Now time to get your hands dirty and get into Git. 
If you're having trouble with the names and terms used in github, go and read through the definitions [here](https://help.github.com/articles/github-glossary/).
Submitting a pull request is the process where you send the changes you've made on your repository (your copy of this file.) to the main copy (Our version of the file) so that you can improve the code in whole and contribute. 
<br>
<br>

#### * Step 1: Firstly, you should fork this repository to your account. Press the "Fork" button on top right of the page and select your account to fork this repository.
<br>
<i>Forks are copies of a main repository which are available for individual users to edit according to their preferences.</i>
<img src="http://i.imgur.com/Ayvkflu.png"/>
<br>
<br>
####  * Step 2: Next, goto your profile and find the fork or the copy of the main repository and click the clone or download green icon on your fork.
<br>
<img src="http://i.imgur.com/ywyNYpp.png"></img>
<br>

#### * Step 3: Go to your terminal(You can search up how to access terminal in your system online.), where git is installed.
<br>
Paste this onto the terminal. You are making the files available on you Computer.


`git clone https://github.com/<your_username>/Practice-Git`


<br>
<img src="http://image.prntscr.com/image/8c27469b5f254f609307d4254d2be5bc.png">
<br>
#### * Step 4:  Go into Practice-Git and go into `submit-a-pull-request` folder and make a folder with your own github username and inside make a file called `helloworld.md` and inside it add something about yourself and commit the file. More detailed instructions are given below
<br>
<img src="http://i.imgur.com/iIUdqEf.png"></img>
<br>

## Step 3

This step includes basic knowledge of the terminal. If you're already familiar with the terminal you can read through. If you're a complete beginner you'll have go through other external tutorials and find it and learn itonline.

It is recommended that you have a working Linux installation. If you need help with Linux installation please contact any of the Core Members and we'll be happy to help you out. But to do this tutorial you don't have to have a Linux. A windows will do just fine. And if you get stuck, Google it or ask in any of the group in slack or whatsapp.

[Beginner Command Line Tutorials](https://www.codecademy.com/learn/learn-the-command-line)

[Beginner Command Line Tutorials](https://www.learnenough.com/command-line-tutorial)

 
Some of the basic commands useful for doing this tutorial:
* cd (Change Directory): This command is used to change the current working directory. For eg:
```
$cd directory_name
```
<img src="http://i.imgur.com/7qvL5V8.png"></img>
* ls (List Files):This command will list you all the files in the directory.
```
$ls
```
<img src="http://i.imgur.com/e1G841o.png"></img>
<br>

* mkdir(Make directory): A command to make a directory(folder) in the current working directory.

```
$mkdir directory_name
```
<br>

* rmdir(Remove directory): Command to remove an empty directory.

```
$rmdir directory_name
```
<br>

* touch (Create): Command to create a file. will create file.txt in current directory.

```
$touch file.txt
```
<br>

* nano(Command line rext editor): Opens up nano, a text editor in the console to edit files. Creates a new file if the filename does not exist. Ctrl+O to save. Ctrl+X to exit.

```
$nano file.txt
```
<br>

## Step 4

In this step we will go further into the command line tools of git.
If you haven't already configured git, you can do it [here](https://help.github.com/articles/setting-your-username-in-git/)

Use command:

```
$git --help
```
to see a list of all commands and their descriptions.

Codecademy has a really good tutorial on using the git command line.

[Codecademy Git Tutorial](https://www.codecademy.com/learn/learn-git)

## Step 5

Once you're familiar with command line tools, it is time to get hands on approach on that as well.
Use git command line tools to do something similar as to what you've done in step 2. Since you've already cloned the file onto your local system. A new folder will be visible called `Practice-Git`.

* Go into you fork folder on your system using your command line and go into the `submit-a-pull-request` folder. Inside the folder make an another folder with you user name (hint : `mkdir <Your_username>`).

```
$cd submit-a-pull-request
$mkdir <your_username>
$cd <your_username>
```
<br>

* Inside the folder with your name, make a file named hello-world.md and inside it add something about yourself using an editor.
```
$touch hello-world.md
```

<br>
<br>

* Now that your file is ready to be online, you need to make git track your new files.

* First you have to add it to git, which is basically letting git know you have a new file.

```
$git add .
```
* Now that's done, you have to save your file, which in git is known as commit. You can do it by.

```
$git commit -m "My First Commit."
```
* The you have to upload it to Github website. Do it by
```
$git push
```
* It will ask for your credentials for logging in.

* Now after it uploads the new file, through the browser go to `https://github.com/<your_username>/Practice-Git`, where `<your_username>` is your github username.

* Now your in your copy of main file. To merge it with the main copy click the option make a pull request.
