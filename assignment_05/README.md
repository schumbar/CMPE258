# Assignment 05

## Assignment Description

I am extending the assignment but there is a twist

You have to record a video showing checked in GitHub as well as clearly explaining what is happening in each code label with quick code walkthru of main code sections and the final output

It is mandatory to include the video in GitHub read.me along with clean explanation of each colab file ane and link and details

All public github url directory with proper clean documentation and clean list of files and public access

Note the changes i mentioned below -

a) you create a 3 layer neural network versus what colab does (at most 2 layer)

b) you must use tensorflow einsum instead of matrix multiply you see in colab.

Use 3 variables based non linear equation (the example i gave in class goes to 2 variables -https://docs.google.com/presentation/d/1r0u-mOhrkDMRXkd4g2wgtbudZ2VCmCE0N3pTgTDWSw0/edit#slide=id.gbb803640d1_0_76 . Generate synthetic data using the equation you used and plot using 4d plot

a) Write a colab numpy only from scratch 3 layer deep neural network for non linear regression . Use proper non linear activation functions and proper number of hidden layer neurons - show the results / loss and epochs training and final output . You will be doing manual backprop and chain rule based gradient propagation

Hint:

https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz Links to an external site.

b) Write a colab pytorch from scratch - 3 layer deep neural network for non linear regression withotu using pytorch builtin layer functionality

Hint https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525Links to an external site.

Hint:

https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQazLinks to an external site.

c) Write a colab pytorch classes based - 3 layer deep neural network for non linear regression using pytorch builtin functionality of modules etc.,. backprop etc.,.

d) Write a colab pytorch lightening version of the same

e)

Build the same using Tensorflow various variants low level, api, functional, model, builtin

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9Links to an external site.

Write a colab tensorflow only from scratch not using high level api of the same

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9Links to an external site.

Write a colab tensorflow only with builtin layers of the same

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=WavMVtXGQk-zLinks to an external site.

Write a colab with Use functional api high level api of tensorflow for the same

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=SyC7KfV-YcYSLinks to an external site.

hint : https://colab.research.google.com/drive/169PfzM0kvtA5UP4k6Sl1yCG9tsE2MLia?authuser=1#scrollTo=C_2FyZeXjHd1Links to an external site.

Write a colab with tensorflow only but using high level api

https://www.tutorialspoint.com/how-to-make-a-4d-plot-with-matplotlib-using-arbitrary-dataLinks to an external site.

h) repeat the above using JAX.

## Assignment Deliverables

Please see below for the list of deliverables that have been submitted for this assignment.
Please note that all deliverables are under the `assignment_05` folder.

1. `assignment_05/CMPE258_Assignment05_PartA.ipynb`: Google Colab implementing a 3-layer deep neural network for non-linear regression using numpy.
2. `assignment_05/CMPE258_Assignment05_PartB.ipynb`: Google Colab implementing a 3-layer deep neural network for non-linear regression without using PyTorch built-in layer functionality.
3. `assignment_05/CMPE258_Assignment05_Part#.ipynb`: TODO
4. `assignment_05/CMPE258_Assignment05_Part#.ipynb`: TODO
5. `assignment_05/CMPE258_Assignment05_Part#.ipynb`: TODO
6. `assignment_05/CMPE258_Assignment05_Part#.ipynb`: TODO
7. `assignment_05/CMPE258_Assignment05_Part#.ipynb`: TODO

## References Used

1. [Deep Learning Fundamentals Part 01](https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz)
2. [Tensors Fundamentals and PyTorch Slides](https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525)
3. [TensorFlow 2.0 + Keras Crash Course.ipynb](https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9)
4. [Intro to Keras for Researchers.ipynb](https://colab.research.google.com/drive/169PfzM0kvtA5UP4k6Sl1yCG9tsE2MLia?authuser=1#scrollTo=C_2FyZeXjHd1)
5. [How to make a 4D plot with Matplotlib using arbitrary data?](https://www.tutorialspoint.com/how-to-make-a-4d-plot-with-matplotlib-using-arbitrary-data)
