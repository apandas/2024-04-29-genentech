---
title: Setup
---

## Getting Started

Data Carpentry’s teaching is hands-on, so participants are encouraged to use their own computers to insure the proper setup of tools for an efficient workflow.
These lessons assume no prior knowledge of the skills or tools.

### Prerequisites

This lesson requires a web browser, a working copy of spreadsheet software (such as LibreOffice 24.2.1), OpenRefine version 3.7.2., R 4.3.3, and RStudio 4.x.x. You will also need to download the data we will be using during the workshop. Please ensure that the data files are stored in a readily accessible location within your file system, such as on your desktop.

To most effectively use these materials, please make sure to download files and install software before your workshop.

## Setup Part 1: Spreadsheets

### Data

**Download** this data file to your computer: [https://ndownloader.figshare.com/files/2252083](https://ndownloader.figshare.com/files/2252083)

#### About the data

The data for this lesson is a part of the Data Carpentry Ecology workshop.
It is a teaching version of the Portal Database. The data in this lesson
is a subset of the teaching version that has been intentionally 'messed up'
for this lesson.

The data for this lesson and the workshop are in the
[Portal Project Teaching Database](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459)
available on FigShare, with a CC-BY license
available for reuse.

> Ernest, M., Brown, J., Valone, T., and White, E.P. (2017). Portal Project Teaching Database. Version 6. Figshare. [DOI: 10.6084/m9.figshare.1314459.v6](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459)

### Software

To interact with spreadsheets, we can use LibreOffice, Microsoft Excel, Gnumeric, OpenOffice.org, or other programs. Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same.

For this lesson, if you don't have a spreadsheet program already, you can use LibreOffice. It's a free, open source spreadsheet program.

#### Windows

- Download the Installer
  - Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Windows should automatically be selected. Click Download Version X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically.
- Install LibreOffice
- Once the installer is downloaded, double click on it and LibreOffice should install.

#### Mac OS X

- Download the Installer
  - Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Mac should automatically be selected. Click Download Version X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically.
- Install LibreOffice
- Once the installer is downloaded, double click on it and LibreOffice should install.

#### Linux

- Download the Installer
  - Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Linux should automatically be selected. Click Download Version X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically.
- Install LibreOffice
- Once the installer is downloaded, double click on it and LibreOffice should install.

## Part 2: OpenRefine

### Data

**Download** the data file [Portal\_rodents\_19772002\_simplified.csv](https://datacarpentry.org/OpenRefine-ecology-lesson/data/Portal_rodents_19772002_simplified.csv), which is a csv file that will open in a new browser tab. Be sure to right click or control click in order to save the file (NOTE: In Safari, right click and select `Download linked file`; in Chrome and Firefox, right-click and select `Save link as...`). Make a note of the location (i.e. the folder, your Desktop) to which you save the file.

#### About the data

The data for this lesson is a part of the Data Carpentry Ecology workshop.
It is a teaching version of the Portal Database. The data in this lesson
is a subset of the teaching version that has been intentionally 'messed up'
for this lesson.

The data for this lesson and the workshop are in the
[Portal Project Teaching Database](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459)
available on FigShare, with a CC-BY license
available for reuse.

### Software

For this lesson you will need **OpenRefine version 3.7.2** and a web browser.

Note: OpenRefine is a Java program that runs on your machine (not in the cloud). It runs inside your browser, but no web connection is needed.

Download OpenRefine version 3.7.2 from [https://openrefine.org/download](https://openrefine.org/download).

- Do not download beta versions or the release candidates. These are only for development and testing of the software.
- If you are on Windows and do not have Java installed, download the version `Windows (including Java)`.
- Unzip the downloaded file into a directory and name that directory something like OpenRefine.
- Check below for further instructions depending on your operating system.

#### Windows

1. Go to your newly created OpenRefine directory.
2. Launch OpenRefine by double clicking on `openrefine.exe` (this will launch a black command prompt window first; ignore this window, and wait for OpenRefine to launch in the web browser, which is where you will interact with the program).

- If Windows displays a blue notification titled `Microsoft Defender SmartScreen prevented an unrecognized app from starting`, click on `More info` and then click on `Run anyway`.

1. If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](https://127.0.0.1:3333/) or [http://localhost:3333](https://localhost:3333) to launch the program.

#### Mac

1. Go to your newly created OpenRefine directory.
2. Drag the OpenRefine icon into Applications folder, and `Ctrl-click/Open…` it.

- If Mac shows a notification when you try to run the program that it cannot verify the developer, click `Cancel`. Then, `Right-click` or `Ctrl-click` the icon and select `Open`. The notification will now have an `Open` button. If it does not allow to open the program, repeat the process and there will be an `Open` button the second time. For additional details, consult the [OpenRefine installation guide](https://docs.openrefine.org/manual/installing#install-or-upgrade-openrefine).

1. If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](https://127.0.0.1:3333/) or [http://localhost:3333](https://localhost:3333) to launch the program.

#### Linux

1. Navigate to your newly created OpenRefine directory using the command line.
2. Type `./refine` into the terminal within the OpenRefine directory
3. If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](https://127.0.0.1:3333/) or [http://localhost:3333](https://localhost:3333) to launch the program.

### Web Browser

OpenRefine requires one of these web browsers installed in your computer:

- Google Chrome
- Chromium
- Safari
- Opera
- Microsoft Edge

OpenRefine has some issues with Firefox. Internet Explorer is not supported.

Note: Other versions of OpenRefine should work, but the results might be different due to changes in the software or default settings.

## Part 3: R and RStudio

R and RStudio are two separate pieces of software: 

* **R** is a programming language and software used to run code written in R.
* **RStudio** is an integrated development environment (IDE) that makes using R easier. In this course we use RStudio to interact with R. 
  
If you don't already have R and RStudio installed, follow the instructions for your operating system below. You have to install R before you install RStudio. 

<br>


#### For Windows

* Download R from the [CRAN website](https://cran.r-project.org/bin/windows/base/release.htm).
* Run the `.exe` file that was just downloaded
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **RStudio x.yy.zzz - Windows Vista/7/8/10** (where x, y, and z represent version numbers)
* Double click the file to install it
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.

#### For MacOS

* Download R from the [CRAN website](https://cran.r-project.org/bin/macosx/).
* Select the `.pkg` file for the latest R version
* Double click on the downloaded file to install R
* It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed by some packages)
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)** (where x, y, and z represent version numbers)
* Double click the file to install RStudio
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.


#### For Linux 

* Download R from the [CRAN website](https://cran.r-project.org/bin/macosx/).
* Select the `.pkg` file for the latest R version
* Double click on the downloaded file to install R
* It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed by some packages)
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)** (where x, y, and z represent version numbers)
* Double click the file to install RStudio
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.


### Update R and RStudio

If you already have R and RStudio installed, first check if your R version is up to date:

* When you open RStudio your R version will be printed in the console on the bottom left. Alternatively, you can type `sessionInfo()` into the console. If your R version is 4.0.0 or later, you don't need to update R for this lesson. If your version of R is older than that, download and install the latest version of R from the R project website [for Windows](https://cran.r-project.org/bin/windows/base/), [for MacOS](https://cran.r-project.org/bin/macosx/), or [for Linux](https://cran.r-project.org/bin/linux/)
* It is not necessary to remove old versions of R from your system, but if you wish to do so you can check [How do I uninstall R?](https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f) 
* After installing a new version of R, you will have to reinstall all your packages with the new version. For Windows, there is a package called `installr` that can help you with upgrading your R version and migrate your package library. A similar package called `pacman` can help with updating R packages across
To update RStudio to the latest version, open RStudio and click on 
`Help > Check for Updates`. If a new version is available follow the 
instruction on screen. By default, RStudio will also automatically notify you 
of new versions every once in a while.

The changes introduced by new R versions are usually backwards-compatible. That is, your old code should still work after updating your R version. However, if breaking changes happen, it is useful to know that you can have multiple versions of R installed in parallel and that you can switch between them in RStudio by going to `Tools > Global Options > General > Basic`.

While this may sound scary, it is **far more common** to run into issues due to using out-of-date versions of R or R packages. Keeping up with the latest versions of R, RStudio, and any packages you regularly use is a good practice.

### Install required R packages

During the course we will need a number of R packages. Packages contain useful R code written by other people. We will use the packages `tidyverse`, `lubridate`, and `ratdat`. 

To try to install these packages, open RStudio and copy and paste the following command into the console window (look for a blinking cursor on the bottom left), then press the <kbd>Enter</kbd> (Windows and Linux) or <kbd>Return</kbd> (MacOS) to execute the command.

```{r}
install.packages(c("tidyverse", "lubridate", "ratdat"))
```

Alternatively, you can install the packages using RStudio's graphical user interface by going to `Tools > Install Packages` and typing the names of the packages separated by a comma.

R tries to download and install the packages on your machine. 

When the installation has finished, you can try to load the packages by pasting the following code into the console:

```r
library(tidyverse)
library(lubridate)
library(ratdat)
```

If you do not see an error like `there is no package called ‘...’` you are good to go! 

### Updating R packages

Generally, it is recommended to keep your R version and all packages up to date, because new versions bring improvements and important bugfixes. To update the packages that you have installed, click `Update` in the `Packages` tab in the bottom right panel of RStudio, or go to `Tools > Check for Package Updates...` 

You should update **all of the packages** required for the lesson, even if you installed them relatively recently.

Sometimes, package updates introduce changes that break your old code, which can be very frustrating. To avoid this problem, you can use a package called `renv`. It locks the package versions you have used for a given project and makes it straightforward to reinstall those exact package version in a new environment, for example after updating your R version or on another computer. However, the details are outside of the scope of this lesson.

### Download the data

We will download the data directly from R during the lessons. However, if you are expecting problems with the network, it may be better to download the data beforehand and store it on your machine.

The data files for the lesson can be downloaded manually:

 - [cleaned data](https://datacarpentry.org/R-ecology-lesson-alternative/data/cleaned/surveys_complete_77_89.csv) and 
 - [zip file of raw data](https://datacarpentry.org/R-ecology-lesson-alternative/data/new_data.zip).
