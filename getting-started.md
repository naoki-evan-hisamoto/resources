# Setting up Sketch [:link:](https://sketchapp.com)
_Don't even pretend like there's a better design tool._ [[Direct download]](https://sketchapp.com/download/sketch.zip)

## 1. Sketch Toolbox [:link:](http://sketchtoolbox.com)
  Plugin manager for Sketch&mdash;like Homebrew, but for Sketch. [[Direct download]](http://sketchtoolbox.com/Sketch%20Toolbox.zip)

#### Recommended Plugins   
   _Available for install using the Toolbox, just search_

   - **Sketch Iconfont** [:link:](https://github.com/keremciu/sketch-iconfont)   
    _You'll need these [font bundles](https://github.com/keremciu/font-bundles) to start_

   - **Sketch Measure** [:link:](http://utom.design/measure/)   
    _Helpful for sharing specs outside of the Invision inspect mode_
  
   - **Sort Me Sketch** [:link:](https://github.com/romashamin/sort-me-sketch)   
    _ctrl+shift+O or P makes sorting lots of layers very nice_

   - **Sketch Select Similar Layers** [:link:](https://github.com/wonderbit/sketch-select-similar-layers)   
    Super helpful for...selecting similar layers. _Note: this is the plugin by wonderbit._ 
  
   - **Renameit** [:link:](https://github.com/rodi01/RenameIt)   
    Batch renaming layers, because 'Layer Copy 4' doesn't help anyone.
  
   - **Pixel Perfecter** [:link:](https://github.com/swiadek/pixel-perfecter-sketch-plugin)   
    Keep it professional.
    
   - **SVGO Compressor** [:link:](https://github.com/BohemianCoding/svgo-compressor)  
    A nice plugin for the [SVGO tool](https://github.com/svg/svgo) so you don't _have_ to use the command line.

## 2. Craft [:link:](https://www.invisionapp.com/craft)
> Craft is a suite of plugins to let you design with real data in mind.  

That and more&mdash;we use this for our [Invision](https://invisionapp) workflow.

# Basic Development Tools
A list of stuff to install when you're setting up a new laptop


## 1. Git / GitHub [:link:](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
  1. [Set up Git and authenticate with GitHub](https://help.github.com/articles/set-up-git/)  
  _N.B. You should have installed Xcode which includes the latest version of Git_

## 2. Homebrew [:link:](http://brew.sh)
  _Homebrew is a package manager that makes it easier to install other stuff_  
  1. Paste this into a Terminal prompt:    
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

  _From the [Treehouse blog](http://blog.teamtreehouse.com/install-node-js-npm-mac):_
  > Homebrew is a great tool for web developers. First, it makes removing Node very easy (otherwise you have to crawl through your file system and delete a bunch of files manually). Second, it greatly simplfies the installation of other useful packages like Git, Ruby, or the very useful wget utility.


## 3. Node / NPM [:link:](https://www.npmjs.com)
  1. Enter `brew install node` into a Terminal prompt.
  2. To check the install, enter `node -v; npm -v`. You should see two numbers print out which are the versions for node and npm respectively.
