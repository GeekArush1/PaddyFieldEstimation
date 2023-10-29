## Megathon '23
# Team: CyberSpace
Members:
-   Aditya Kulkarni
-   Arush Sachdeva (POC)
-   Himanshu Singh
-   Pranav Agarwal
-   Swarang Joshi

Institute: IIIT Hyderabad

Link to the submission: https://github.com/GeekArush1/PaddyFieldEstimation
## Problem Statement 1
by _Govt. of Telangana_
The challenge at hand involves the effective management of paddy cultivation and procurement in Telangana State. This includes:
1.	Paddy Cultivation Identification: Determining whether paddy is cultivated or not in a given area and identifying the type of paddy being cultivated.
2.	Stages of Paddy Growth: Monitoring the various stages of paddy growth, from sowing to harvesting.
3.	Online Procurement System Integration: Assessing the feasibility of issuing tokens to farmers within an Online Procurement System (OPMS) based on the successful harvest, with the objective of controlling external paddy sales in Telangana State.
4.	Identification of Fake Paddy: Developing methods to identify forged or substandard paddy to ensure the quality and authenticity of procured paddy.
5.	Utilizing Satellite Imagery: Exploring the use of satellite imagery as a potential tool for identifying paddy cultivation and monitoring its growth stages like sowing and harvesting.

This problem statement outlines the multiple components of the issue and the desired outcomes, setting the stage for further analysis and potential solutions.

## Abstract
Effective management of paddy cultivation and procurement is crucial for agricultural sustainability and economic growth, especially in regions like Telangana State. 

We have attempted to address this problem in a stagewise, divide and conquer fashion. Firstly, given a satellite view of a geographical area, we aim to notify whether there is scope of paddy cultivation or not. Secondly, we look at the probable areas flagged by our first model. The second model is trained to differentiate between paddy and other crops. Lastly, we have models to detect the health of paddy and identify the variety of paddy being cultivated.

## To run:
Open gui.ipynb and run all cells. A window will open.

## Refernce and Resources:
-   ### ChatGPT
    Prompts given:
    -   "using tkinter, write a code with widgets showing the title, description and to input an image"
    - "I am inputting the folder which contains separate folder containing images each of jute, maize, rice, sugarcane and wheat. Streamline the training of model according to that and return me full correct code to identify rice out of all the images, given one test image."
    - "Getting following error:

        ```
        Traceback (most recent call last):
        File "/home/aditya/Desktop/Megathon/model2.py", line 79, in <module>
            label = img.split("_")[0]  # Assuming the variety name is before the underscore
        TypeError: Image.split() takes 1 positional argument but 2 were given
        ```
    Also used it for debugging.

-  https://www.kaggle.com/datasets/girishkleit/riceonfiledimages/data
- https://agritech.tnau.ac.in/expert_system/paddy/TNvarieties.html

-   https://oar.icrisat.org/12010/1/Thesis_final.pdf
-   https://agritech.tnau.ac.in/expert_system/paddy/TNvarieties.html
https://www.mdpi.com/2072-4292/15/14/3575
-   https://www.researchgate.net/figure/The-effect-of-growth-stage-of-a-canola-crop-on-RADARSAT-1-backscatter-In-this-figure_fig3_233332101

