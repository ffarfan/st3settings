# st3settings

Personal settings for Sublime Text 3.

Forked from [ptomato/st2settings](https://github.com/ptomato/st2settings)

## Location of Settings

**Mac OS X:**
```
~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
```

**Linux:**
```
~/.config/sublime-text-3/Packages/User
```


## Prerequisites

### Install Sublime Text 3

You may download it [here](https://www.sublimetext.com/3).


### Install Package Control
After installing Sublime Text, install Package control from the menu:

```
Tools -> Install Package Control
```


### Install Python 3

Ensure that Python3 is installed on your operating system:

```
# On my Mac, I use Brew
$ brew install python3
```


### Install (Python) Linters and other prerequisites

You may want to install linters and other requirements at this time. As an example, you may install flake8

```
$ pip3 install flake8
```

Once `flake8` is installed, you may want to install SublimeLinter from the Command Palette, from the menu:

```
Tools -> Command Palette ... -> Package Control: Install Package -> SublimeLinter
Tools -> Command Palette ... -> Package Control: Install Package -> SublimeLinter-flake8
```

Similarly, install Anaconda linter:

```
Tools -> Command Palette ... -> Package Control: Install Package -> Anaconda
```


## How to Use

Clone this repository in the location indicated above, according to your operating system, e.g.

 ```
 $ cd ~/.config/sublime-text-3/Packages

 $ git clone {this-repo} User
 ```

**Note:** Notice that you want to clone the repository as `User`, so that it takes the settings to all packages as user settings.
