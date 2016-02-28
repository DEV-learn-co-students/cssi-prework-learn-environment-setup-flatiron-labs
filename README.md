# Setup

## Setting Up Your Environment for Learn.co

** If you've already set up your environment and downloaded the Learn App, feel free to skip this readme! **

You need a proper development environment to learn to code. There are two ways to do this

* Option 1: Environmentalizer, the Learn OSX Companion App
* Option 2: Manually install the necessary software 

The easiest way is to download the app, but if you want to set up your environment yourself, feel free.

## Option 1: Automating the Setup with Environmentalizer

You can setup your computer using the [Learn OSX Companion application](https://flatironschool-static.s3.amazonaws.com/learn.zip).

If you use that app, a Github account is all you need (and you presumably already have one, since you're reading this document!).

### **If you use the Learn Companion App, you don't need to continue reading this guide; you are done!**

*If you're curious, or want more control over your environment, feel free to continue on for manual instructions.*


## Option 2: Manual  Install & Requirements

In general the list of requirements for using Learn are:

1. A [GitHub](https://github.com/join) account. You can use the free account on GitHub—you won't need private repositories at this point.

2. You should have your GitHub account tied to your shell preferably via [SSH](https://help.github.com/articles/generating-ssh-keys/) but you can use [OSX Keychains](https://help.github.com/articles/updating-credentials-from-the-osx-keychain/).

3. You'll need a way to compile software. If you're on OSX, the best thing you can do is use [XCode](https://developer.apple.com/xcode/downloads/) and [XCode Command Line Tools](https://developer.apple.com/library/ios/technotes/tn2339/_index.html) [download for 10.10 XCode 6.3.1](http://adcdownload.apple.com/Developer_Tools/Command_Line_Tools_OS_X_10.10_for_Xcode_6.3.1/commandlinetoolsosx10.10forxcode6.3.1.dmg) to get GCC.

4. You'll probably need a package manager of some sort. We love [Homebrew](http://brew.sh/) on OSX.

5. You're going to need [git](http://git-scm.com/downloads). It generally comes with most modern operating systems, can be installed via Homebrew, apt-get, and most package managers easily.

6. A Ruby Interpreter. Having a working interpreter is a great idea because so much tooling is built in Ruby. This is even true for the web development you will complete with Python. If you can type `ruby -v` and not get an error, you probably have enough of a Ruby environment. If you are studying Web Development with Ruby (such as the Rails framework) you definitely need a great Ruby environment. We love [RVM](https://rvm.io/) for managing Ruby versions and environments.

7. The `learn` gem. Simply type: `gem install learn-co` or if you get a permissions error, `sudo gem install learn-co`. Then type in `learn` to configure it with your github account and you'll be all set.

8. A Text Editor. For iOS, XCode is a great IDE,  but your CSSI students will be using [Atom](https://atom.io/).  Therefore, it is beneficial to use Atom at your text editor.

Those are the absolute requirements.


Good luck!!!

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/learn-environment-setup' title='Setup'>Setup</a> on Learn.co and start learning to code for free.</p>
