---
layout: portfolio
title: Code Development
img: "assets/img/projects/code_preview.png"
color: "#223b7a"
---

In my opinion research should preferentially consist of new and unique tasks. Computers are ideally suited for repetitive tasks. Furthermore, in order to build and run an instrument such as [LION or CHILI](/research/04-rims) control software is required. I have worked and am currently working on multiple code development projects. Most of these projects that are of general interest can be found on my <a href="https://github.com/trappitsch" target="_blank">github profile</a>. Below I will outline a few projects that might be of general interest.

<a href="https://www.python.org" target="_blank">![Python Logo](/assets/img/projects/python_logo.png)</a>

As you will notice, my programming language of choice is python. Please feel free to [contact me](/contact) if you are interested in some code I wrote, want to contribute, collaborate, or you want like to discuss resources for getting started with scientific coding in python.

# iniabu

Iniabu is a package for python that you can use to easily calculate the inital abundances of the solar system and return ratios as $$\delta$$-values or in bracket notation. By default the initial abundances from <a href="https://doi.org/10.1007/978-3-540-88055-4_34" target="_blank">Lodders et al. (2009)</a> are called. You can install this module by simply calling:

	pip install iniabu

Help on how to use it can either be found in the <a href="https://github.com/LLNL/iniabu" target="_blank">readme file on github</a> or by accessing the docstring, e.g., from within ipython by calling:

	import iniabu                                                           
	ini = iniabu.IniAbu()                                                   
	ini?

# Mahon Fitting

In order to fit a linear regression we use the routine by <a href="https://www.tandfonline.com/doi/abs/10.1080/00206819709465336" target="_blank">Mahon (1996)</a>, also known as the "New York" regression, should be used. Along with the <a href="https://doi.org/10.3847/2041-8213/aabba9" target="_blank">Trappitsch et al. (2018)</a> publication we published a tool to easily apply the Mahon fitting routine to any dataset. The tool, including a detailed readme file, can be found on <a href="https://github.com/LLNL/MahonFitting" target="_blank">the respective github site</a>.



