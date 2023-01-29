    Git and GIthub explanation


Git is a command line tool that will help us with version control in several different ways:
Allowing us to keep track of changes we make to our code by saving snapshots of our code at a given point in time.

Allowing us to easily synchronize code between different people working on the same project by allowing multiple people to pull information from and push information to a repository stored on the web.

Allowing us to make changes to and test out code on a different branch without altering our main code base, and then merging the two together.
Allowing us to revert back to earlier versions of our code if we realize we’ve made a mistake.
In the above explanations, we used the word repository, which we haven’t explained yet. A Git repository is a file location where we’ll store all of the files related to a given project. These can either be remote (stored online) or local (stored on your computer).

-
-
-
-
GitHub is a website that allows us to store Git repositories remotely on the web.



- if run `git clone repository url` in the terminal, it will create a folder with the same name as the repository and copy all the files from the repository into the folder.
- if run `ls` in the terminal, it will list all the files in the current directory
-  if run `cd repository name` in the terminal, it will change the current directory to the repository folder
- if run `touch file name` in the terminal, it will create a file with the given name in the current directory
- if run `git status` in the terminal, it will show the status of the repository


More GitHub Features
There are some useful features specific to GitHub that can help when you’re working on a project:

Forking: As a GitHub user, you have the ability to fork any repository that you have access to, which creates a copy of the repository that you are the owner of. We do this by clicking the “Fork” button in the top-right.
Pull Requests: Once you’ve forked a repository and made some changes to your version, you may want to request that those changes be added to the main version of the repository. For example, if you wanted to add a new feature to Bootstrap, you could fork the repository, make some changes, and then submit a pull request. This pull request could then be evaluated and possibly accepted by the people who run the Bootsrap repository. This process of people making a few edits and then requesting that they be merged into a main repository is vital for what is known as open source software, or software that created by contributions from a number of developers.
GitHub Pages: GitHub Pages is a simple way to publish a static site to the web. (We’ll learn later about static vs dynamic sites.) In order to do this:
Create a new GitHub repository.
Clone the repository and make changes locally, making sure to include an index.html file which will be the landing page for your website.
Push those changes to GitHub.
Navigate to the Settings page of your repository, scroll down to GitHub Pages, and choose the master branch in the dropdown menu.
Scroll back down to the GitHub Pages part of the settings page, and after a few minutes, you should see a notification that “Your site is published at: …” including a