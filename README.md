# DVA-Team-069-Project User Guide

## Description

This project contains the reproducable capability to pull in data from basketball-reference.com. It then cleans the data and performs correlation tests before handing off clean 
data for use by a prediction model. The linear regression model predicts total wins in the current season based on statistics gathered during that season that we have assessed to 
have a high correlation with wins. These predictions have then been fed into a Tableau workbook where they have been visualized in interactive charts. 

In these charts, users may notice that wins were accurately predicted in the current season using a limited number of statistics. This suggests that organizations may have the 
potential to improve their decision making by focusing their analytics teams on seaking for simple predictions of regular season wins. In doing so, the decision making process 
can be simplified as well, focusing on improving the production of these targeted statistics over time, while following a timeline that could be indicated by the same precitions.

## Installation

Prior to utilizing this project, users should first install the necessary dependencies, listed below.

	- Python
	- Jupyter Notebook
	- Tableau
	
The simplest way to install Python and Jupyter Notebook is by installing the [anaconda distribution](https://www.anaconda.com/). For Tableau, users may sign up for their 
[free trial](https://www.tableau.com/products/desktop/download). If preferred, other installs of these dependencies may be used to simplify the process.

Lastly, users should clone this repo to a local directory for use and explore any and all files inside. Though, the interface is best utilized by opening Workbook_v1.twb in Tableau.

**Note:** A copy of the python library *sportsreference* has been included for the sake of reproducability only. This library has been slightly modified so that it may work with the
current version of basketball-reference.com. Credit is due to the authors of this code and its inclusion here is not a claim of its originality by this group.

## Execution

To demo all code, open Master.ipynb and run all cells. The generated predictions can then be viewed by simply opening the Workbook_v1.twb file in Tableau. While in Tableau, 
the predictions can be easily interactived with to better understand all charts in full detail.
