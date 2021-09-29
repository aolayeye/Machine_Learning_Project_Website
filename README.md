# Machine_Learning_Project_Website
## Overview
The website contained in this repo contains a summary readme, links to the machine learning code, a google slides presentation and the online interactive Tableau dashboard.
This readme also provides a self-assesment, team assessment, and project summary 

[Link to Website](https://aolayeye.github.io/Machine_Learning_Project_Website/ "Link to Website")

### Project Experience
#### Self-Assessment

##### Segment One – Triangle, Circle, and X Roles

While the final project had clearly defined roles for every segment, I actively took all four roles from start to finish. From sourcing for a suitable dataset and a topic for the team to designing a database approach, selecting appropriate technologies, and building the first basic model, I ensured that the team could deliver segment one in record time.

##### Segment Two – Square, Triangle, Circle, and X Roles

I ensured that the machine learning component was completed over segments two and three while gradually developing the database component.

##### Segment Three – Square, Triangle, Circle, and X Roles

I completed the fully developed machine learning algorithm by the end of segment three, which fetches data and stores intermediate results to a live online AWS database.
The AWS database, which contained the intermediate results of the machine learning algorithm, served as input data to the Tableau dashboard.

##### Segment Four – Square, Triangle, Circle, and X Roles

I ensured we had the requirements.txt file generated and pushed to the main branch by the end of segment four. Also, I created a project website that contained a summary readme and links to the machine code, the presentation slides, and the dashboard.
While I did not take the square role in segment one, I ensured the GitHub was sanitized and complete with a comprehensive readme. I guided every team member to create their branches for each segment of the project. After a thorough review of individual branch changes, I merged all pull requests to the main branch. 

##### The challenges

The second and third segments of the project presented unique technical challenges, ranging from computation resources required to run memory-intensive models to cohesively combining the model, database, and dashboard components of the control flow established in the first segment.
One way I got around the computation resources was to adopt a phased approach to model parameter selection. While this may have proved time-consuming, it significantly reduced computation time and system resources. This stepwise scaled-down approach also meant I could determine the best model parameters in a timely fashion.

Also, designing and implementing a dashboard from a dataset with features extracted from PCA proved particularly challenging at first. Until I synthesized EDA data and model results into the AWS database, which then served as input to an online interactive Tableau dashboard

#### Team Assessment

The team developed a communication plan early in the project. This plan includes communication via
1. slack, where ideas are exchanged and documented.
2. All team members created individual branches where they could work on different portions of the project
3. Team members commit changes to their GitHub branches frequently.
4. Progress is shared in slack, and pull requests are created at periodic intervals after approval by the team
5. A designated member reviews the pull request, executes the merge.
6. A significant accomplishment for the team was finishing the considerable parts of the project with some time to spare; this is due in part to finding a topic and dataset before the project started.
7. The team was visible and available, and everyone offered to help each other whenever possible. As a result, the team can reduce the cycle time between changes and validation.


#### Project Summary

The final project was credit card fraud detection as a classification problem. The imbalance in the dataset was compensated for by undersampling and oversampling the majority and minority class, respectively, across multiple linear and non-linear models including logistic regression, random forest, decision tree, SVM and KNN.
The performance metric was Recall and then Accuracy. The project also implemented an AUC-ROC curve to determine optimum classification thresholds for the different machine learning algorithms. Finally, we implement the learning curve to determine the goodness of fit for the five algorithms developed.

The machine learning models pulled data from the AWS S3 bucket and stored intermediate results AWS Postgresql.
The intermediate results of the AUC-ROC curve, together with EDA, forms the basis for the dashboard of the project. 
The dashboard tells the imbalanced story of the dataset in a series of interactive univariate pie charts and bivariate distribution plots. The dashboard also tells the story of the AUC-ROC curve and the different classification thresholds for each of the five machine learning algorithms implemented for this project.
Finally, a project website is implemented. This website contains a summary readme, links to the machine learning code, a google slides presentation and the online interactive Tableau dashboard.

