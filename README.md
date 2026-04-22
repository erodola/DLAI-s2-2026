# Deep Learning & Applied AI @Sapienza

Course material, 2nd semester a.y. 2025/2026, Dept. of Computer Science

## News 🗞️
- **13/04/2026:** The **project topics and guidelines** have been published. Scroll down for details.
- **30/03/2026:** No lecture on **April 7-8-14** due to Easter holidays and exam sessions. The lecture of **April 15 will not be a lab**, so make sure to be there!
- **10/02/2026:** The course website is online. Welcome to DLAI 2025/26! **The course will start on Tue 24th February**.

## Logistics 🧭

**Lecturer:** Prof. Emanuele Rodolà

**Assistants:** [Dr. Daniele Solombrino](https://github.com/dansolombrino/), [Dr. Giorgio Strano](https://github.com/giorgioskij/)

**When:** Tuesdays 10:00--12:00 and Wednesdays 09:00--12:00

**Where:**

Tuesdays: Aula 2L - Castro Laurenziano (RM018-E01PTEL026)

Wednesdays: Aula 3L - Castro Laurenziano (RM018-E01PTEL025)

There is no virtual classroom; the lectures will not be recorded.

## Pre-requisites 🔑

Python fundamentals; calculus; linear algebra.

## Textbook, reading materials and video recordings 📖

Due to the continuously evolving nature of the topic, there is no fixed textbook as a reference. Specific material in the form of scientific articles and book chapters will be given throughout the lectures.

In addition:

- [here](https://drive.google.com/drive/folders/1NKU5nSAU-klicJEPxIiADDvuYbZF1Vpd) you can find video recordings of 2025 lectures
- In the GitHub pages of the previous academic years you can find longer versions of some video lectures
- [here](https://github.com/erodola/numMeth-s2-2022) you can find video recordings about topics that may come in handy when studying deep learning
- [here](https://github.com/erodola/DLAI-s2-2022/raw/main/resources/Course_notes_Crisostomi.pdf) you can find some supplementary course notes
- [here](https://github.com/FFMasterSlave/DLAI-alternative-notes/tree/main) you can find annotated slides
- [here](https://github.com/dansolombrino/DLAI-2022-23) you can find Anki flashcards on theoretical and practical lectures

Thanks to past and present students for the kind contributions!

**Accessibility 👁️‍🗨️**: Since last year, in an effort to create a more inclusive and accessible learning environment, all slides have been re-designed with readability in mind to support students with specific learning disabilities. We aim to ensure that everyone, regardless of learning differences, has equal access to the educational content provided. Should you need additional accommodations or have suggestions for further improving accessibility, please feel free to reach out.

## Grading 📊

**Exam dates**

Each exam session has **cutoff dates** for submitting the project. 

Only projects that are (i) submitted *before* the cutoff date and (ii) registered on Infostud will be graded.

- 19 June 2026 - *cutoff date 12 June*
- 17 July 2026 - *cutoff date 10 July*
- 18 September 2026 - *cutoff date 11 September*

Evaluation proceeds according to the following steps:

- A project (**mandatory**, accounts for 100% of the final grade)
- An oral exam (**optional**, attributes at most 3 points, added to or subtracted from the final grade)

We may require an oral exam in doubtful cases or whenever necessary.

- Project list: Check the [guidelines](https://github.com/erodola/DLAI-s2-2026/raw/main/guidelines.pdf).
- The template for the final project report is [here](https://github.com/erodola/DLAI-s2-2026/raw/main/template.zip).
- Please read the material above carefully!

## Past exams 📑 

Exam is now project-only, but you can still find some past theoretical questions [here](https://drive.google.com/drive/folders/1hwafIolYEOEjJYRnyKg2kodFqgKDZklZ)

## Running the Notebooks

### Online
In class, we suggest to run the notebooks via Google Colab. It's a free, online jupyter environment that allows to run python code with (limited) access to free low-tier GPUs. 

### Locally
All the notebooks can just as well be ran locally on your own machine by opening them in your favourite development environment (VS Code, PyCharm...). To do so, you need to create a *python environment* containing all the libraries that are used in the code.

The **only** correct way to create python environments is by using [uv](https://docs.astral.sh/uv/). You simply:
- install `uv` from their website;
- open the directory `labs` in your terminal and run `uv sync`. 
Then, you will have a correct, functioning environment (called `labs`) inside `labs/.venv`.

If you have never created python environments or used `uv` before, give the `uv` documentation a read: it's very easy to understand.


## Lectures 🗣️

**Date** | **Topic** | **Reading** | **Code & Data**
------------ | ------------- | ------------ | ------------
Tue 24 Feb | Introduction | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/01_intro/01-intro.pdf) |
Wed 25 Feb | Data, features, and embeddings | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/02_data/02-data.pdf) ; [linear algebra recap](https://github.com/erodola/DLAI-s2-2026/raw/main/03_linalg/03-linalg.pdf) ; [matrix notes](https://github.com/erodola/DLAI-s2-2026/raw/main/03_linalg/03b-matrix.pdf) |
Tue 03 Mar | Linear regression, convexity, and gradients | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/04_linear/04-linear.pdf) |
Wed 04 Mar | Tensor basics and Tensor operations | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/01_Tensor_basics.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/02_Tensor_operations.ipynb)
Tue 10 Mar | Overfitting and going nonlinear | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/05_nonlinear/05-nonlinear.pdf) |
Wed 11 Mar | Linear models and Pytorch Datasets | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/03_Linear_models_and_Pytorch_Datasets.ipynb)
Tue 17 Mar | Stochastic gradient descent | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/06_sgd/06-sgd.pdf) |
Wed 18 Mar | Logistic Regression and Optimization | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/04_Logistic_Regression_and_Optimization.ipynb)
Tue 24 Mar | Multi-layer perceptron and back-propagation | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/07_mlp/07-mlp.pdf) |
Wed 25 Mar | Autograd and Modules | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/05_Autograd_and_Modules.ipynb)
Tue 31 Mar | Convolutional neural networks | [slides](https://github.com/erodola/DLAI-s2-2026/raw/main/08_cnn/08-cnn.pdf) |
Wed 01 Apr | Convolutional neural networks | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2026/blob/main/labs/06_Convolutional_Neural_Networks.ipynb)
Tue 07 Apr | **Easter holidays** |  |  
Wed 08 Apr | **No teaching due to exam sessions** |  |  
Tue 14 Apr | **No teaching due to exam sessions** |  |  
Wed 15 Apr | Industry Seminars: Michele Mancusi and Giulio Starace |  |  
Tue 21 Apr | Engineering Seminar: Alessandro Bartolocci | coming soon! |
Wed 22 Apr | Research Seminar: Daniele Solombrino | [slides](https://github.com/erodola/DLAI-s2-2026/blob/main/10_quantization/Quantization%20-%20Part%20I.pdf) |
Tue 28 Apr | Engineering Seminar: Alessandro Bartolocci | coming soon! |


**End**
