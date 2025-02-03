# Contributing

So, you want to contribute to something I'm working on?

Well, first of all, thank you! Now let's continue.

## Creating a Fork

From the GitHub website, fork the repository by pressing the fork button:

<details>

![A screenshot showing the "Fork" lunk on GitHub, accessible from the first tab "Code". It shows the repository Smartparens, which introduces a mode for structural editing in Emacs.](../images/forking.png)
</details>

On the next page, no need to change anything, only click on "Create fork".

## Making a Branch

After making a fork, you'll be taken to its page, from there, click on the branch button, and then on "View all branches".

<details>

![A screenshot on the same tab, "Code", but now on the fork repository, which the user is automatically taken to. On this page, the button labelled "master branch" was pressed, which shows a drop down menu. On this menu, one should navigate to the link "View all branches" to proceed.](../images/branching.png)
</details>

After clicking on "View all branches", proceed by clicking on "New branch", then name your branch.

If it fixes an issue, prefix its name by the ID of the issue and its name (or part of it if it's too long).

Example: `1-typo-on-readme`

Then navigate to your branch.

### Why?

You may ask, "why is this done?". This is done because it helps you on contributing, as your changes are all isolated on different places. Also, you get a notification for making a pull request.

## Making Changes

After going in to your branch, you can make changes directly from GitHub. If you prefer making them in your editor of choice, then I assume you already know how to clone a repository and switch to a branch. Then let's proceed to the final step, the commit message.

## Commit Message

I ~~try to~~ follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) guidelines. Give them a read if you have some time. If not, here's the gist of it:

Changes should have their type as a prefix to the description.

The types I use the most are:

- `docs` (documentation)
- `feat` (features)
- `fix` (bug fixes)
- `refactor` (changes to the organization of code)

For them, I also provide pull request templates.

Here is an example message from one of my repositories for you:

```text
docs(readme): reword recomendation

Reword recomendation, as the previous phrasing could imply that this channel
doesn't feature builds from source.

This commit clarifies that these recomendations are safer options, as they
don't feature automation.
```

The first line is the commit title. The scope (text inside parentheses) for me is the file name, which can also include the path to avoid confulsion (when there's two files with the same name, for example).

And that was it, I skipped some basic points, but I think I covered everything for anyone editing from the site.

Thanks!
