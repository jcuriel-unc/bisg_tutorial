# bisg_tutorial
A repository for learning applications and validations of BISG. (update: 02/26/2024)

This tutorial employs the publicly available Mapping Police Violence Project (https://mappingpoliceviolence.org/) data to demonstrate the steps involved in BISG in semi-cleaned data, followed by a  validation against recorded race of the victims noted within the observations. These are then followed by some exploratory analyses meant for a larger paper and set of projects on the issue.  

Note that for this tutorial, a simpler version of the wru package (v 0.1-12) is used in order make it more compatible with a version of the zipWRUext2 package. Each Rmd file that employs BISG through wru therefore runs a preamble of installation code to ensure that the proper version of wru is installed and loaded. 

In what follows, I cover the main materials of interest. Note, for a self guided tutorial of the BISG process, please see the mpv_tutorialV2.Rmd. 

## Training of intetest 

mpv_tutorialV2.Rmd - The Rmd document that creates the initial exploratory report for the Mapping Police Violence project. Includes the full set of code to clean, get results, and plots of interest. More in depth version of the presentation, as it goes over each chunk of code and the rationale for it. Exports an html doc. Is meant for a self guided walkthrough of the project. 

mpv_presentation_bisg.Rmd - The Rmd document covers the same code as the mpv_tutorialV2, though is designed for an initial walkthrough of the basic processes of BISG as applied to the Mapping Police Violence Project. For sake of brevity, many of the results are hidden in the outputted html as ios slides. However, all of the code necessary to produce the results and graphics of interest as the mpv_tutorialV2.Rmd are present, albeit with less explanation. Intended for a presentational set up. 

custom.css - The css style file for the mpv_presentation_bisg.Rmd ios slides. DO NOT MOVE. Created by Matteo Courthoud, whose github can be found here: https://github.com/matteocourthoud/ioslides-theme



