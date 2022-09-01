# [Data Science Portfolio One Project overview](https://github.com/DataEngineeringGuru/Data-Science-Portfolio-One)

## Steps for setting up the website:
1.  Create a github account
2.  Make a new github repo and initialize the readme
3.  Go to settings 
4.  Go to GitHub pages and select master branch
5.  Select theme if you would like
6.  Go to the link at the top of the github pages section 
7.  Make any changes you would like to the markdown of the readme to get your content
8.  You now have a data science portfolio website!
9.  Note This is inspired fron a tutorial: How to Make a Data Science Portfolio by KenJee The Data Professor. 

# [Project One Ball Image Classifier Project Overview](https://github.com/PlayingNumbers/ball_image_classifier)
* Data science project example using deep learning for image classification 
* For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain  country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. 
* This is the underlying model for building something with those capabilities. 
* I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. 
* To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 
![]( "matrix results")


# [Project Two Data Science Salary Estimator: Project Overview](https://github.com/PlayingNumbers/ds_salary_proj)
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* Built a client facing API using flask 

![]( "Salary by Position")
![]( "Job Opportunities by State")
![]( "Correlations")
