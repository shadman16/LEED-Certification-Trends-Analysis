# LEED-Certification-Trends-Analysis
This project focuses on analyzing the patterns Leed certified buildings have using ML models such as Random Forest, KNN, Logistic Regression and Catboost
## Overview
LEED (Leadership in energy and environmental design) certification is one of the widely accepted 
green building certification types promoted by US Green Buildings Council. Being LEED certified 
offers various benefits to building owners such as tax incentives, saving money on operational 
cost, attracting tenants, improving indoor air quality, reducing energy use and carbon emissions, 
and achieving energy saving goals. There are 4 levels of certification – Certified, Silver, Gold and 
Platinum and different version numbers. Of all LEED credits, 35% relate to climate change, 20% 
directly impact human health, 15% impact water resources, 10% affect biodiversity, 10% relate to 
the green economy, and 5% impact community and natural resources.
The problem we aim to address is the lack of awareness and understanding of LEED certification 
among stakeholders such as policy makers and property developers.  
• Currently, it can be challenging for LEED certification applicants to stay informed on the 
latest LEED certification trends across different states in the US.  
• Additionally, there is a lack of decision support tools available that can recommend a 
suitable certification level based on input parameters such as project type, LEED system 
version number, and GrossFloorArea.  
Our solution is to build an exploratory web application that addresses these gaps and provides 
an interactive and comprehensive decision support tool for LEED certification.

## Solution Architecture
![Capture](https://github.com/shadman16/LEED-Certification-Trends-Analysis/assets/66548483/8490d3a3-eeb6-4a11-95f6-854e499b9ffe)

## Dashboard of Geographical scenario of Leed certified Buildings

![georgraphic view](https://github.com/shadman16/LEED-Certification-Trends-Analysis/assets/66548483/763a1252-f180-4254-bc1d-478b5b0a5de4)
## DESCRIPTION
The package contains the Jupyter notebook containing the code for loading the data, exploratory data analysis, cleaning and trnasforming the data, ML models (Logitic Regression, KNN, Random Forst, CatBoost), Tableau Notebook and Excel data. 
Python Packages used: pandas, numpy,sklearn, imblearn, os, seaborn, matplotlib, catboost, pickle, streamlit


## INSTALLATION - How to install and setup your code
There is no need to install and set up any code. Our web application has embedded Tabueau and StreamLit form for capturing inputs. 
Dataset is included in the package. It needs to be in the same folder as the Python notebook.

The URL for the website is https://sites.google.com/view/leedcertification-trendsandins/home

## EXECUTION - How to run a demo on your code
Hover over tha map in Tableau to view the LEED trends for State-specific data. 
To perform the leed certifcation prediction using the streamlit form, go to the form on the web site and provide input parameters to view the prediction of certification tier.

