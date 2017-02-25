# Forks and Clones

## Objectives

1. Fork a repo
2. Clone a repo
3. Push to different remote repos

##Forking a GitHub Repository
Forking a GitHub repository is just a way to create your own copy of it. We do this all the time while using Learn. Every time you fork a lab, GitHub creates a copy that you can use as a sandbox to play around, all while maintaining a canonical repo where the original lab remains intact. In other words, forking creates another remote that allows you to work in your own world without messing with the core learn-co-students content.

![Fork Button](http://readme-pics.s3.amazonaws.com/fork_button.jpg)

You can fork any repo by clicking the "Fork" button at the top right of any GitHub repository. Learn also makes it easy by allowing you to click the "OPEN" button at the top of any lab (if you use the Learn IDE) or to simply type `learn open` in your terminal (if you use a local development environment). It's also worthwhile to note that you can go to your fork of a given lab by changing the "learn-co-students" bit of the GitHub URL to your GitHub username. For example:

```
https://github.com/learn-co-students/first-lab-001-prework-web
```
Change "learn-co-students" to your username:
```
https://github.com/your-username-here/first-lab-001-prework-web
```

[More on forking in the GitHub docs.](https://help.github.com/enterprise/2.2/user/articles/fork-a-repo/)

##Cloning
Now we want to get our forked copy of the repository on our local machine. This is where cloning is useful. To do this:

1. Navigate to your forked repo on GitHub.
2. Click the "Clone or Download" green button on the right.
2. Make sure you select `Use SSH` as your URL type.

	![SSH URL](https://files.readme.io/UgsI2ndmR2aH5ky5G1OA_GitHub%20-%20SSH%20-%201.png)

3. Click the "Copy to clipboard" button (highlighted below). This will copy the URL for us to use when we clone.

	![Clone Repo Button](http://readme-pics.s3.amazonaws.com/clone-repo-clone-url-button.png)

4. In the terminal, run the `git clone` command. It takes the URL we just copied as an argument:

	```bash
	git clone your-copied-github-url
	```

	This will create a local copy of our forked GitHub repository.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/forks-and-clones-readme' title='Forks and Clones'>Forks and Clones</a> on Learn.co and start learning to code for free.</p>

<p class='util--hide'>View <a href='https://learn.co/lessons/forks-and-clones-readme'>Git Forks and Clones</a> on Learn.co and start learning to code for free.</p>
