# ConferenceRealignmentEffects
A senior capstone project focused around the effects of D1 FBS Conference Realignment.
# Description
As Power 5 college athletic programs buck the trend of regionality for conference opponents, these schools look to capitalize on the billions of dollars of revenue available through media deals to broadcast football and basketball games. Although those media deals will increase revenues these conference changes continue the arms race for better travel, facilities, and coaches increasing the expenses as well. I will be evaluating the marginal effects of conference realignment to see if these moves will promise the increase in revenues that are being claimed by athletic directors across the country. 
# Prerequisites
To run this project all that is needed is the newest version of R and the packages that come with it. This is all free and just requires a computer that can run the R software. 
# Data 
The data set comes from a collabration between the Knight Commission on Intercollegiate Athletics and the Syracuse University Newhouse School of Public Communications (https://knightnewhousedata.org/fbs). This data gives an expense report for all public Division 1 universities from 2005-2022. Some key variables for expenses include: coaches compensation, facilities, travel,and athletic student aid. Some key variables for revenue include: institutional support, media rights, donor contributions, corporate sponsorship, and ticket sales. 
Football Bowl Subdivision | College Athletics Database. Knight-Newhouse College Athletics Database. (n.d.). https://knightnewhousedata.org/fbs
This data was multiple excel files that were combined into a csv file that was used for analysis. That file is above and is called fbs_data.csv which should be used for analysis on this topic. 

# Analysis
Using the csv included in this repo, I ran predictive modeling on a training set from 2005-2018 and then a test set from 2019-2022. The predictive models included multivariable linear regressions for 10 different columns regarding revenues and expenses to see how the 2019-2022 actual finances compared to predicted values. After running the regressions I was able to compare the predicted to the actual and found that most of my predicted values were around $3-5 million off, either over or underpredicted. The distribution of the predicted values was very accurate. That analysis can be found in the file titled DA401 Capstone.Rmd in this repo. 


# Contact Info
My name is Mike Bednarek and I am a senior at Denison University and a Data Analytics & Economics double major. I can be reached at bednar_m2@denison.edu or 773-332-5061.
