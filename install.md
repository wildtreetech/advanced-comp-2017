# Installing the required software

These instructions should get you from zero to a working setup on windows,
linux and Mac. Please try to follow them before the first lecture.

These instructions were taken directly from the amazing people at
[Software Carpentry](https://software-carpentry.org).

In general terms you will need a terminal, python3, scikit-learn 0.18,
matplotlib, git and jupyter. If you know what all these mean you probably do
not need to read these instructions.

👋 If you get stuck with these instructions create an issue [here](https://github.com/wildtreetech/advanced-comp-2017/issues/new).

# Windows

### bash
* Download the Git for Windows [installer](https://git-for-windows.github.io/).
* Run the installer and follow the steps bellow:
  1. Click on "Next".
  1. Click on "Next".
  1. Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
  1. Click on "Next".
  1. Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
  1. Keep "Use Windows' default console window" selected and click on "Next".
  1. Click on "Install".
  1. Click on "Finish".
* If your "HOME" environment variable is not set (or you don't know what this is):
  1. Open command prompt (Open Start Menu then type cmd and press [Enter])
  1.Type the following line into the command prompt window exactly as shown:
    `setx HOME "%USERPROFILE%"`
  1. Press [Enter], you should see SUCCESS: Specified value was saved.
  1. Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

### git
Nothing to do here, you already installed it as part of the `bash` step.

### python
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3 installer for Windows.
1. Install Python 3 using all of the defaults for installation except make sure to check *Make Anaconda the default Python*.


# Mac

### bash
The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). See the Git installation [video tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY) for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop.

### git
For OS X 10.9 and higher, install Git for Mac by downloading and running the most recent "mavericks" installer from [this list](http://sourceforge.net/projects/git-osx-installer/files/). After installing Git, there will not be anything in your /Applications folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" [available here](http://sourceforge.net/projects/git-osx-installer/files/).

### python
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3 installer for OS X.
1. Install Python 3 using all of the defaults for installation.


# Linux

### bash
The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash.

### git
If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run `sudo apt-get install git` and for Fedora run `sudo yum install git`.

### python
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3 installer for Linux.
1. Install Python 3 using all of the defaults for installation.
