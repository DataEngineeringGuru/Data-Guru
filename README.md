# [Data Science Portfolio One Project overview](https://github.com/DataEngineeringGuru/Data-Science-Portfolio-One)

## Introduction
A data science portfolio website can greatly help your career opportunities. It is a clean way to showcase your data science projects, and it also shows that you can clearly communicate your work and findings. 

In this repository I demonstrate how you can quickly build a data science portfolio website using github pages. 
Your GitHub website is created using GitHub Gitpages allowing you to host links to all of your project work. Recruiters do not have the time or the ability to sift through your whole github repo. A GitHub pages website gives a high level view of your capabilities, allowing employers to focus in on areas of interest.
#### Credits: This project is inspired by The Data Professor and Ken Jee.
#### Instructions and Resources at end of this presentation.
  
## [Project One Ball Image Classifier Project Overview](https://github.com/PlayingNumbers/ball_image_classifier)

* Data science project example using deep learning for image classification 
* For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain  country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. 
* This is the underlying model for building something with those capabilities. 
* I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. 
* To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 
![](/images/matrix_results.png "matrix results")


## [Project Two Data Science Salary Estimator: Project Overview](https://github.com/PlayingNumbers/ds_salary_proj)

* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* Built a client facing API using flask 

![](/images/salary_by_job_title.png "Salary by Position")
![](/images/positions_by_state.png "Job Opportunities by State")
![](/images/correlation_visual.png "Correlations")

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
10. You should try to have at min four links to your data science project work repos, the following is a list some of must haves:
    1. Classification
    2. Regression
    3. Clustering
    4. Deep Learning
    5. NLP or Computer Vision Project.
The Data Professor reccommends you have as many as is possible.
 
## Summary: 
Try to showcasing unique and interesting insights, develop your own models to generate these unique insights from relevant data sets.
Best of luck and most of all enjoy the process.
Again credits to The Data Professor Ken Jee!

### Resources you can use:
![]("Link to a Markdown Cheat Sheet:" https://www.markdownguide.org/cheat-sheet/)
![]("Github Repo:" https://github.com/PlayingNumbers/Ken...)
![]("Github Pages Details:" https://pages.github.com/)

## Next Tutorial:
How to create a more rebust Data Science Portfolio using HTML 
