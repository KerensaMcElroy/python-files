---
title: Setup
---

## Sample Data

This lesson uses an example fastq file. Inside your dataschool folder, please make yourself the following directory structure:

~~~
python/data
~~~
{: .language-bash}

Download the following files to this directory:

[a_few_lines_of_text.txt]({{ page.root }}/data/a_few_lines_of_text.txt) 
[sample.fastq]({{ page.root }}/data/sample.fastq) 

{% include links.md %}


## Installing Anaconda

### CSIRO-specific instructions

1. The Anaconda Python distribution can be installed from the CSIRO IM&T
   Software Centre.
2. A full guide to using the Software Centre is [here][csiro-software-centre].
2. Open the Software Centre.
3. When the Software Centre opens, search for "anaconda" and install "Anaconda
   Python 3".

> ## Get Help from IM&T
> 
> You can get help from the IM&T Service Desk if you require help with
> installing Anaconda onto a CSIRO computer.
{: .callout}

### For Everyone Else
1. Visit the [Anaconda download page][anaconda].
2. Select your operating system (Windows, macOS, or Linux).
3. Download the Python 3.7 64-bit graphical installer.
4. After the download completes, run the installer to install Anaconda.

> ## Follow the Installation Guide
>
> If you need more detailed guidance, then please follow the [Anaconda
> Installation guide][anaconda-installation].
{: .callout}

## Updating Anaconda

1. Once Anaconda is installed, it is a good idea to update it.
2. The article [Keeping Anaconda Up To Date][anaconda-update] is a good guide to
   updating Anaconda after it is installed.
3. It boils down to opening an Anaconda terminal and running the command:
~~~
conda update --all
~~~
{: .source}

> ## Updating is not essential for this course
> 
> If you would rather skip updating, then it is not essential for this course.
{: .callout}

{% include links.md %}

[csiro-software-centre]: https://my.csiro.au/tasks/it-and-computing/it-hardware-and-devices/computers/desktop-software/installing-windows-software
[anaconda]: https://www.anaconda.com/distribution/
[anaconda-installation]: https://docs.anaconda.com/anaconda/install/
[anaconda-update]: https://www.anaconda.com/keeping-anaconda-date/
