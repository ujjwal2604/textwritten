

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Textwritten</h3>

  <p align="center">
    Convert text file to handwritten pdf
    <br />
    <br />
    <a href="https://github.com/ujjwal2604/textwritten.git/issues">Report Bug</a>
    ·
    <a href="https://github.com/ujjwal2604/textwritten.git/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

![Screen shot](../main/src/image/ss.png)

Hey friends, did you get bombarded by a lot of school assignments during this era of 'online education'? And you want to escape and do away from those stubborn professors who regularly threatens you of assignment deadlines?

Or you want to save some of your precious time doing something productive rather than just copying something from internet and pasting it in your handwriting for just the sake of some marks. Then this project is for you.


### Here's why: ###
* Your time should be focused on creating something amazing. A project that solves a problem and helps others.
* You shouldn't be doing the same tasks over and over like writing assignments.
* So this project *aims at taking input as a text file and generating a brand new handwritten pdf file from it*.


Of course, this project is highly documented for your convenience so that you can tweak it as you wish. You may also suggest changes by forking this repo and creating a pull request or opening an issue.



### Built With

* [Python3](https://www.python.org/)
* [Jupyter notebook](https://jupyter.org/)





<!-- GETTING STARTED -->
## Getting Started

Grab a python3 distribution and run the source code with the help of jupyter notebook. Both of these get set up if you install anaconda distribution on your system.

<p align="center">
    **OR**
</P>

Just install any python3 distribution, install the dependencies and run `textwritten.py` in the `src` folder.


### Prerequisites

* path.py
* numpy
* Pillow

After installing anaconda, run in the `src` directory 
```sh
pip install -r requirements.txt
```
in your terminal to install all the required dependencies and modules. Else they get installed automatically if you run the ipython notebook.

### Installation

1. Clone the repo
```sh
git clone https://github.com/ujjwal2604/textwritten.git
```
2. Install required modules
```sh
cd src
pip install -r requirements.txt
```
3. Run the ipython notebook in `src` folder 

Don't forget to put in the `INPUT_FILE` from which you want to generate pdf and resulting `OUTPUT_FILE` just above the `main()` function in the end of the notebook. . Check current directory and viola, you have generated the required pdf.

<p align="center">
    **OR**
</P>

3. Run the `textwritten.py` in the source folder with correct options and arguments.





<!-- USAGE EXAMPLES -->
## Usage
### Using Jupyter Notebook:

```sh
INPUT_FILE = 'infile.txt'
OUTPUT_FILE = 'outfile.pdf'

main()
```

### Using CommandLine:

```sh
OPTIONS
-i | --input : specify the input text file, required
-o | --output : specify the output pdf file, default is out.pdf
```


So practical usage will look like:
```sh
# cloning the repo in your machine
git clone https://github.com/ujjwal2604/textwritten.git.git

cd textwritten/src

pip install -r requirements.txt

python3 textwritten.py -i hello.txt -o output.pdf

```

And you are good to go:smile:

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/ujjwal2604/textwritten.git/issues) for a list of proposed features (and known issues)



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/ujjwal2604/textwritten.git](https://github.com/ujjwal2604/textwritten.git)


Ujjwal : [ujjwalkhandelwal10@gmail.com]










