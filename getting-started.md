#Basic Tools
A list of stuff to install when you're setting up a new laptop

##Git
[Set up Git and authenticate with GitHub](https://help.github.com/articles/set-up-git/)
_N.B. You should have installed Xcode which includes the latest version of Git_

##[Homebrew](http://brew.sh)
_Homebrew is a package manager that makes it easier to install other stuff_
Paste this into a Terminal prompt:
```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

_From the [Treehouse blog](http://blog.teamtreehouse.com/install-node-js-npm-mac):_
> Homebrew is a great tool for web developers. First, it makes removing Node very easy (otherwise you have to crawl through your file system and delete a bunch of files manually). Second, it greatly simplfies the installation of other useful packages like Git, Ruby, or the very useful wget utility.

##Node and NPM
1. Enter `brew install node` into a Terminal prompt.
2. To check the install, enter `node -v; npm -v`. You should see two numbers print out in this format:
```vX.X.X
X.X.X```
