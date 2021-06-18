# Java Notes
This repo contains my study notes for `Java SE 8` [Foundations Certification](https://education.oracle.com/java-foundations/pexam_1Z0-811) in [Jupyter Notebooks](https://jupyter.org/). They're numbered in the order that I created them as I was covering each topic. 

In order to be able to execute the code examples in the notebooks you can install [BeakerX](http://beakerx.com/).

## Installing Jupyter Notebook
There are a [number of ways](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) you can install but I've found the most user-friendly and consistent across different OS's to be [Anaconda](https://www.anaconda.com/products/individual#Downloads) which comes with Jupyter Notebook by default.

## Installing BeakerX
If you installed Anaconda then you can simply follow the instructions in the [BeakerX documentation](http://beakerx.com/documentation#tutorials-and-examples) by running the following in terminal:
<br>`conda create -y -n beakerx 'python>=3'`
<br>`source activate beakerx`
<br>`conda config --env --add pinned_packages 'openjdk>8.0.121`
<br>`conda install -y -c conda-forge ipywidgets beakerx`

If you didn't install __Anaconda__ you can find alternative instructions [in the documentation](http://beakerx.com/documentation#tutorials-and-examples).

## Running BeakerX
The documentation says that after installing with the above instructions you can run it with just `beakerx`, however, that's not my experience. On my system in order to run it I first need to activate it with `activate beakerx`, *then* running `beakerx` launches Jupyter in the default web browser. So, if just running `beakerx` doesn't work for you try that. I've added an alias to my .bashrc so that running `beakerx` actually runs `activate beakerx && beakerx` to make it easier.

