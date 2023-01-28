# Multi-Source Data Generation and Parameter Estimation

## LaTeX Advice

You may wish to use [Overleaf](http://www.overleaf.com) to type up LaTeX, which has most of the packages that would be needed. Otherwise, for Macs, you can download [MacTeX](https://www.tug.org/mactex/).

## Data

The data can be found on [here](https://course.ccs.neu.edu/cs6220/homework-3/). There should be two CSV files, originally from the Kaggle website, but with rows removed. *Please do not commit the data to your repository as these are larger files.* (You can consider using `git-lfs`.)

## Homework Template Files

This templated repository has the following files

* `assignment3-questions.tex` - You can edit this for your assignment. If you do, make sure to rename the file `assignment3.tex` so that TA's know which file to compile and grade.
* `assignment3-questions.pdf` - These are the questions for the assignment. 

## Submission Guidelines

Please review the instructions from the [homework website](https://course.ccs.neu.edu/cs6220/homework-3/).

At the end of this assignment, your submission will point to a repository, where the following files will be reviewed and subsequently graded:

* `assignment3.tex` file with your homework writeup
* `assignment3.pdf` file of the compiled version of your `*.tex` file
* `assignment3.ipynb` or `assignment3.py` file. This could be downloaded from Colab (if you used Google Colab).

None of the other files in that repository will be reviewed. You can however, have a directory structure for supporting files. For example, the following repository structure could help keep your top level directory clean.

```
./
assignment3.tex
assignment3.pdf
assignment3.ipynb
./images
  graph_for_question-1.jpg
  results_for_question-2.jpg
./tex
  question_3_proof.tex
./code
  helper_functions.py
```

Do _NOT_ include data into your Git repository.
