# Setting up your R Environment

1. Follow the instructions in chapters 4-6 at https://happygitwithr.com/ to create a GitHub account, install R and RStudio. 
2. Open RStudio.
3. Follow instructions in this video to ensure git is installed: 

<p><a href="https://vimeo.com/511798611">Verify Git Installation</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

4. If git is not installed, follow instructions in chapter 7 at https://happygitwithr.com/
5. Edit your git config by following these instructions: 

<p><a href="https://vimeo.com/511798861">Edit gitconfig file</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

6. Create a personal access token by following these instructions, and be sure to set the expiration to 150 days: 

<p><a href="https://vimeo.com/511801645">Create a Personal Access Token (PAT) on GitHub</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

7. Store your personal access token by following these instructions: 

<p><a href="https://vimeo.com/511803103">Store Personal Access Token to Connect RStudio and GitHub</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

8. Copy the URL for this portfolio GitHub repo. It should look like this: https://github.com/SDS-237-Data-Ethnography-Spring-22/portfolio-YOUR_USER_NAME
9. Create a project in RStudio from this GitHub repo by following the instructions starting at 26 seconds of this video:

<p><a href="https://vimeo.com/511804881">How to Connect RStudio Projects with GitHub Repositories: GitHub First</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

10. Install the rmarkdown package in RStudio by entering the following lines of code in the Console Pane of RStudio (lower left hand corer on initial install).  

```
install.packages("rmarkdown")
library(rmarkdown)
```

![RStudio Panels](images/rstudio_panels.png)

11. In the Environment panel (upper right hand corner), click on the Git tab. The branch will be set to main (see image below). Add a new branch by clicking the icon with two purple boxes (See image below.) Name your branch yourinitials-getting-started (e.g. Lindsay's would be lp-getting-started). Make sure you are in your branch (i.e. where it used to say 'main', it will now have your branch name). 

![Git Panel/Branching](images/git_panel.png)

12. On the initial install, the Files tab will be in the lower right hand corner of RStudio. Open the setting-up-r-environment folder, and then open getting-started.Rmd, and follow instructions.
14. When the file tells you to commit your code, follow the instructions in this video starting at 14 seconds: 

<p><a href="https://vimeo.com/511800674">Make a Commit and View More History</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

15. Push your code to GitHub.com by following the instructions in this video starting at 27 seconds:

<p><a href="https://vimeo.com/511805399">General Workflow: Push</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

16. Navigate to https://github.com/SDS-237-Data-Ethnography-Spring-23/portfolio-YOUR_USER_NAME and click on the Pull Requests tab. Click New Pull Request. Where the button says 'base: ' make sure 'main' is selected. Where the button says 'compare: ' make sure your branch is selected. Click Create Pull Request.
