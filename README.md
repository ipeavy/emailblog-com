# [GuideForNewEmailDevs](https://guidefornewemaildev.netlify.app/)

<!-- <img src="https://i.imgur.com/SkgbYzU.png" alt="download-1" border="0">
 -->
## About The Project


### Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

### Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/your-username/emailblog.git
```

where `your-username` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd emailblog
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b addAnotherTip
```

(Please let the name of the branch be descriptive of the changes you are about to make.)

### Make necessary changes and commit those changes

Now go ahead and make the necessary contributions you want to make.

You can execute the command `git status`, to see the files you have made the changes to.

Add those changes to the branch you just created using the `git add .` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m "Descriptive commit message on the changes you made."
```

### Push changes to GitHub

Please before you push your codes to the repository make sure you pull from the repository, so the recent changes that have been made to the main repo can be reflected on your local machine. This is to avoid merge conflicts. Use the git command line `git pull upstream main`

```
git pull upstream main
```

and fix any merge conflicts you might have before pushing your changes.

Now push your changes using the command `git push`:

```
git push origin your-new-branch-name
```

replacing `your-new-branch-name` with the name of the branch you created earlier.

### Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Your changes or contributions will be reviewed and if ok, merged into the main branch of this project. You will get a notification email once the changes have been merged.

[⬆ Back to Top](#title)

