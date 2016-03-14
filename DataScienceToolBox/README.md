DataScience Tool Box
=============

From http://datasciencetoolbox.org

This tool solves a problem of maintaining a set of versioned tools that your code requires in a virtual environment. This solves the problem of poluting your own machine with packages that constantly require updating.

## How to Use

1. Clone this Repo
2. Install Vagrant from https://www.vagrantup.com
3. Install VirtualBox from https://www.virtualbox.org 
4. Open a terminal to the folder you cloned this repo from.
5. Run: 
> vagrant up

## What happens next

The command will download and install an Ubuntu distribution with pre-installed packages for datascience including:

**Python**
IPython Notebook, NumPy, SciPy, matplotlib, pandas, scikit-learn, and SymPy.

**R**
ggplot2, plyr, dplyr, lubridate, zoo, forecast, and sqldf.

Once the box has been installed, you can login into the box using:

> vagrant ssh

You are now running an Ubuntu installation inside your own host machine with shared folders....

 




