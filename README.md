#  Workshop On LaTeX for Scientific Writing

### Workshop Description

[LaTeX](https://www.latex-project.org/) is a high-quality typesetting system which comprises of technical and scientific features for high-quality document production. It can be used for manuscripts, presentations and dissertations/thesis production that range from small to medium to large size documents. This 2 days workshop is inteded to create hands-on experience, awareness and enrich knowledge for research scholars, faculty and students on LaTeX. The sessions will be fully filled with hands-on presentation giving you enough opportunity to practice and explore more.

### Programme Contents

* Overview of LaTeX.
* Installation of LaTeX Tools. 
* Producing simple documents.
* Text formatting.
* Typsetting programming codes.
* Typesetting mathematics formulas.
* Tables and graphics.
* Bibliography and cross-refences text.
* Journal paper and thesis report. 
* Presentation slides.
* Collaborating with LaTeX and git.
			

### Who can attend?

The target audiences for this workshop are Faculty members and Students (Master and doctoral students). Bring with you a laptop with Linux, MacOS or Windows installed.


###   Trainer Profile

The training materials have be prepared by [Anthony Faustine](sambaiga.github.io), a PhD machine learning resercher at [IDLab](https://www.ugent.be/ea/idlab/en), [imec](https://www.imec-int.com/en/home), [Ghent University](https://www.ugent.be/en).

## Software preparation in advance of course  (separate instructions are provided):

* MiKTEX
* TextStudio
* Dropbox (optional)
* BitBucket (optional)
* Mendeley
* Source Tree (optional)
* Notepad ++
* Minted (optional)

### MiKTEX

You first need a TEX Distribution software that contains all the software that you need to create a LATEX document. Several options exist for windows, Mac OS and Linux.

* [MiKTeX](https://miktex.org/): A a free TeX distribution for Windows systems.
* [MacTeX](https://tug.org/mactex/): A a free TeX distribution for Mac.
* [TeXLive](https://www.tug.org/texlive/): A a free TeX distribution for for most avors of Unix and windows.

You also need a text editor to create a LATEX source file. We will use TexStudio (text editor); a free package that allows you to edit tex documents, compile and view them, has syntax highlighting, autiocompletion, inline spell and gramma checker and much much more.


### [MiKTEX](https://miktex.org/) and [TextStudio](http://www.texstudio.org/).

**Download and install [MiKTEX](https://miktex.org/)** 

 1. First of all get the latest [64-bit/32-bit Net Installer of MikTeX Setup](https://miktex.org/download), which downloads all available pakets at once. 
    * Do not select the Basic Installer, because on-the-fly downloading is a nice idea but is likely to break with limited user rights.
 2. Once the download has finished, start the installer again and chose the pre-selected option to install from local directory.
 3.  During installation, you will be asked for selecting your preferred paper size (choose A4) and for package installation. 
     * For the second option you may choose if MiKTeX is allowed to install packages on the fly, meaning if we are referencing a package in your code that is not yet installed, MiKTeX is recognizing it and installs it automatically. 
     * You may also prefer to be asked before, as this will help you know which packages are being installed on your ystem. 
     * Remaining installation is just straight forward.
 4. When you have installed MiKTeX, it is recommended that you [run the update wizard](https://miktex.org/howto/update-miktex-2-9) in order to get the latest updates.
  
  
**Download and install [TextStudio](http://www.texstudio.org/):** 

  1.  Download [TexStudio](http://www.texstudio.org/) for your distribution.
  2. Make sure to install TexStudio when MiKTeX installation is completed.
  3. You may follow this [link](http://math65740.blogspot.com/2015/06/installing-miktex-and-texstudio-on.html) for installation procedure.
  5. TexStudio will automatically congure the settings for you
  4. The installation of LaTeX is now complete.
    
**Note**: You may also follow this [video tutorial](https://www.youtube.com/watch?v=cPXzIUR-YsY) on how to install and use TexStudio with MiKTeX

### [Dropbox (optional)](https://www.dropbox.com)

We will use  cloud drive service like Dropbox for saving our works into. For Dropbox installation procedure follow this [link](https://www.dropbox.com/en/help/243). Once it is installed create  a new folder in your Dropbox folder called Latex.

###  [Notepad++ ](https://notepad-plus-plus.org/)

This is a text editor that serves anything you will need when editing text files. We will be using it later for managing our bibliography file. You may download it [here](https://notepad-plus-plus.org/).

### [Mendeley](https://www.mendeley.com/) 

A desktop and web program produced by Elsevier for managing and sharing research papers, discovering research data and collaborating online. You may download and install Mendeley by following this [link](https://www.mendeley.com/download-mendeley-desktop/windows/instructions/).

### [BitBucket (optional)](https://bitbucket.org/dashboard/overview) and [SourceTree (optional)](https://www.sourcetreeapp.com/)

**Cloud Storage (Dropbox) Vs Version Control (Bitbucket)**

Cloud storages services like Dropbox are very important in scientific writing as they provide file backup and syncronisation. They may work for collaboration on files, but they are [not meant for two people editing the same file at once](http://academia.stackexchange.com/questions/5277/why-use-version-control-systems-for-writing-a-paper). Most of these cloud storage are created to keep files in sync over a multitude of platforms and to provide backup. They are not created to monitor changes and they dont have merge functionalities as the results one author changing a file can overwite changes made by by other authors. Apart from that most of cloud storage services dont provides history such as knowing wether anyone has worked on the file you want to work on it or added or modified any other files etc.


[Version control](https://en.wikipedia.org/wiki/Version_control) makes it safe to work on the same file, and makes it easy to track history (i.e. previous versions). [Git](https://git-scm.com/) is the most common version control systems and BitBucket is the cloud-based git solution. SourceTree is the free git client for windows and Mac that provides graphical interfaces for git repostories.


**To use [BitBucket](https://bitbucket.org/):** 

Signup for an BitBucket account, go to https://bitbucket.org/ and click the Get started for free button. For more information on how to create BitBucket account follow [this link](http://www.tecmint.com/bitbucket-for-version-control/) or [these instruction](https://confluence.atlassian.com/bitbucket/sign-up-for-bitbucket-cloud-728138044.html).

**Set up SourceTree ** 

Follow [these steps](https://confluence.atlassian.com/bitbucket/set-up-sourcetree-603488472.html) in this link to install SourceTree 

### [Minted (optional)](https://github.com/gpoore/minted)

A LaTeX package that facilitates expressive syntax highlighting using the [Pygments](http://pygments.org/) library. The package also provides options to customize the highlighted source code output. Since minted uses Python pygments library, so you need to:

* Install [Python](https://www.python.org/), choose any version you like: x64 or x86, it better to choose [2.7.5 version](https://www.python.org/download/releases/2.7.5/).
* Add Python to your PATH: 
 > My Computer > Properties > Advanced System Settings > Environment Variables >`

* Append ;C:\Python27 to the PATH variable.
* Install python-pip: Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py), being careful to save it as a .py file rather than .txt. Then, run it from the command prompt:
 > python get-pip.py

* Add ;C:\Python27\Scripts to the PATH variable.
* Then install Pygments.
 > pip install pygments
 


## Resource

1. [Writing Scientific Papers](http://flow.byu.edu/posts/writing-sci-papers).
2. [Version control for scientific research](http://blogs.biomedcentral.com/bmcblog/2013/02/28/version-control-for-scientific-research/).
3. [Beginners Tutorial](https://www.sharelatex.com/blog/latex-guides/beginners-tutorial.html).
4. [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX).
5. [Helpful LaTeX symbols](http://cs.brown.edu/about/system/software/latex/doc/symbols.pdf).
6. [LaTeX Reference Card](http://www.math.brown.edu/~jhs/ReferenceCards/LaTeXRefCard.v2.0.pdf)
