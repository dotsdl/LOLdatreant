# Analyzing League of Legends match data using `datreant`

This repo gives a demo for how [`datreant`](http://datreant.org/) can be used to analyze a dataset organized in a traditional filesystem.
The dataset comes courtesy of Alyssa Adams (@alyssa-adams), using Riot Games' public API for pulling League of Legends match data. Over 5000 matches were collected and saved in their own respective data files. The idea is to position these files in an organizational manner so many scientific questions can be asked without doing extensive engineering on existing code. 

This demo was presented to Sara Walker's research group on Jan 26, 2017.
In it, we explore questions around banning of characters in a match, and the effect this has on a team's chances at winning or losing.
We don't conclusively answer any questions, but instead showcase how rapid exploration of many questions can be done using `datreant` and [`pandas`](http://pandas.pydata.org/).

Datreants is the core tool used when organizing vast numbers of data files for a project of this scale. For more information about the League of Legends project, including code and data repositories, visit www.nostrateemo.com and https://github.com/alyssa-adams/NostraTeemo.
