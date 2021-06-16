# How to Contribute to This Repository

- If you **find a resource for NYU Tandon students**, just fork the repository, add the resources, commit and make a pull request
- If you have **ideas for changing/improving the repository**, create an issue and describe your ideas.

## What to Contribute

All contributions, documentation improvements, and ideas are welcome; if you're new to open source, we recommend looking at the [Github "Issues" tab][issues].

### Claim an Issue

Let us know that you are working on the issue by posting a comment below the issue that you are trying to fix. Simply state that you are trying to resolve it - this way other people are not jumping in and duplicating your work.

(If you do not have any activity for a while after claiming the issue, we will assume that you abandoned it so other people can work on it.)

### Git and Github

You'll first need to [create a Github account][sign-up-gh] and [download Git][git-desktop]. If you're new to either of these two systems, here's a few good resources to get you started:

- [CS61 Git][cs61-git] - Git introduction by CS61 professor at Harvard
- [How to Contribute][open-source-guide] - This guide by Alaina Kafkes describes how to contribute to projects on Github; if you're completely lost, or just need a refresher on the basics, this is a good place to start
- [Git Basics][git-basics] - A more technical look at the basics of Git itself
- [Git Cheatsheet][git-cheats] - Github's Git cheat sheet
- [How to Create a Pull Request on GitHub][create-pull-req] - A guide specifically for creating pull requests on Github. We recommend learning a little more about Git before reading this, because it can't help with troubleshooting Git problems
- [Matthew Brett's Git Guide][curious-git] - A beginner's guide to Git, how it works, and how to use it. It's written like a story, so skimming might be appropriate depending on your comfort level
- [The Git Parable][git-parable] - A beginner's guide to Git on a more technical level. It's also written like a story, so skimming might be appropriate

[git-cheats]: https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf
[open-source-guide]: https://medium.com/clarifai-champions/99-pr-oblems-a-beginners-guide-to-open-source-abc1b867385a
[git-basics]: https://git-scm.com/book/en/v2/Getting-Started-Git-Basics
[create-pull-req]: https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github
[git-desktop-guide]: https://help.github.com/desktop/guides/getting-started-with-github-desktop/
[curious-git]: https://matthew-brett.github.io/curious-git/curious_intro.html
[git-parable]: http://practical-neuroimaging.github.io/git_parable.html
[issues]: https://github.com/Ajinkya-Sonawane/nyu-tanon-resources/issues
[git-desktop]: https://git-scm.com/downloads
[sign-up-gh]: https://github.com/join
[cs61-git]: https://cs61.seas.harvard.edu/site/ref/git/

In general, you'll need to first fork the repository to your own account, then clone it to your own computer with

```shell
git clone https://github.com/YOUR-USER-NAME/nyu-tanon-resources.git
```

Next you'll want to set up your local `main` branch to track your forked repository. You can do this with:

```shell
git branch set-url --push origin https://github.com/YOUR-USER-NAME/nyu-tanon-resources.git
git branch -u origin/main
```


## Make sure all directory names are in lower case, just to keep a standard format

**NOTE:** You should replace `YOUR-USER-NAME` with _your_ username.

Now, whenever you type `git push` you'll push to your own forked repository, and when you type `git pull` you'll pull from nyu-tanon-resources's main repository.
