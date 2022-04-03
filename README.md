# Tutorial: Advanced Colab Development Environment
A quick tutorial for setting up a machine learning development environment consisting of your favorite IDE and Google Colab code execution. If you find it helpful, slap that star button!

![alt text](https://github.com/DavidBellamy/advanced_colab_tutorial/blob/main/Colab%20tutorial%20diagram.png?raw=true)

# Summary

Colab is easy to use, free, and gives access to accelerated hardware (e.g. GPUs). But it also forces you to develop your code in notebooks. I'll leave it to Joel Grus to make the full argument as to [why notebooks sucks](https://www.youtube.com/watch?v=7jiPeIFXb6U). On the other hand, if you're an instructor and want to design an ML course that uses a professional IDE, what hardware will the students execute their code on? Most students don't have their own GPUs and renting cloud compute services is costly and cumbersome. That's what this tutorial aims to help with: enable the use of IDEs and proper software engineering practices while also easily executing your code on free Colab hardware.

The recipe for the approach is as follows: develop code as you typically would using an IDE, version control and virtual environments, use Google Drive Desktop to auto-sync the local copy of your project directory to Google Drive, and import the project directory from Google Drive into Colab. I've attempted to facilitate that last step by creating a [template Colab notebook](https://colab.research.google.com/drive/1j7EgNH1cgSrz1TUp8wex2NmL7BQYZYDq?usp=sharing) with instructions that help import your project repo into Colab (once it is already syncing with Google Drive).

# More info

To read the full tutorial, see the [PDF](https://github.com/DavidBellamy/advanced_colab_tutorial/blob/main/Tutorial__Advanced_Colab_Development_Environment.pdf) in this repo.
