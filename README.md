# GH Fun
A repository where I'll try to document fun things to do with GH

For example, his whole repo was created from within terminal, no need to open a browser

```sh
gh repo create gh-fun --public
```

However, the repo itself is created to quickly show how to get visualizations in terminal
![picture of a visualization, except that it should be moving](image.png)

This is done by:

0. Installing [Scoop]
1. Opening up terminal and typing in the following:

```sh
scoop install gh
gh ext browse
gh extension install vilmibm/gh-screensaver
gh screensaver
```

*. If you run into any issues, you might need to login to your Github account first

```sh
gh auth login
```

- More info on GH[1]
- More info on Screensaver[2]

[Scoop]: (https://scoop.sh/)
[1]: https://cli.github.com/manual/
[2]: https://github.com/vilmibm/gh-screensaver
