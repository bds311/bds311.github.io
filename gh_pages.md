## Creating a New GH-Pages Site

For this first part of homework 08 in BDS 311, you will be creating a GH-Pages site. Some of you may have started this process in class, while some of you may not have started at all. Either way, this will guide you through the process from scratch.

#### Part 1: Creating a new Repository
Go to <a href='https://github.com' target='_blank'>GitHub</a>. If you are logged in to your github account, you should be able to create a new repository by clicking the green button as pictured below:

<img src="./assets/images/new_repo_git.jpg" width="800" align='center'/>

Once clicked, you will be given options to configure your repository.

Your repository must be of the format `<account-name>.github.io`. In other words, repository should include **the exact same name as your account name**. If my account name were BillyBob, my github website repository will be called `BillyBob.github.io`.

<img src="./assets/images/ghpages_name.jpg" width="400" align='center'/>

This should be a public repository. No need to include a `README.md`, a `.gitignore`, or to choose a license.
<br>
#### Part 2: Convert the repository to gh-pages

Once the repository is created, you should be able to access it at the link `github.com/username/username.github.io`. If my username were `BillyBob`, the website would be `github.com/BillyBob/BillyBob.github.io`. 

Once at that URL, you should be able to click on the `Settings` Tab (with a gear icon).

In the `Settings` Tab, click on the `Pages` Icon under the `Code and Automation` section on the left of the screen.

Check to see if your screen matches the image below. Click on the button that says `change theme`. Choose whatever theme you like the most.

<img src="./assets/images/pages_code_automation.jpg" width="800" align='center'/>

Github will probably take you to a screen with a sample markdown file. No need to edit the file for now. Simply scroll down and hit the large green button saying `Commit Changes`.
<br>

#### Part 3: Get repository onto local computer.

Go to our class webpage on [Git Repositories](git_repos.md) to get your gh-pages repository onto your local computer.

#### Part 4: Populating your website
Your gh-pages repository should have a single Markdown file to begin with: `index.md`. Change this file and commit/push these changes to github. The changes made to `index.md` will show up on `username.github.io`.

Next, on your local computer, create a new markdown file called: `experience.md`. Add a few lines about some of your work or professional experience. These changes will show up on `username.github.io/experience`.

Add a link to your *experience* page in `index.md`. Commit and push these changes to the remote github repository.

#### Part 5: Link your GitHub Repository to HW08

Back in `mauna_loa.ipynb` in your personal `mauna_loa` Git repository, paste the link to your gh-pages GitHub repository in question 1.
