# NYC Taxi Trip Prediction
# Problem Description
Task is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

<h2> :floppy_disk: Project Files Description</h2>

<p>This repository includes 1 colab notebook (.ipynb) file and 1 pdf file of project presentation. </p>
<h4>About Files:</h4>
<ul>
<p align="justify"><li><b>NYC Taxi Trip Time Prediction Capstone Project.ipynb</b> - This file includes Features description, exploratory data Analysis, feature engineering, feature scaling and implemented algorithms for eg. <b>Linear Regression, Decision Tree, XGBoost.</b></li>
  <li><b>NYC_PPT</b> -  This is a power point presentation file of a project. It includes various visualaized plots of EDA using <b>Seaborn and Matplotlib</b>. The result chart of various implemented algorithms. </li></p>
  

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Summary</h2>
<p align="justify">The given dataset conatins more than 14 lac records and 11 columns. The main goal of this project to predict the trip duration. To get more insights about the dataset, performed Exploratory data analysis to understand the main characteristics of various features. Using existing features, created new features for model building and to interpret data more easily. After analyzing the dataset, it’s found that there is a some inconsistency in some recorded data. The passenger count was high like 7 to 9 passengers in taxi. The travelled distance is very less but trip duration is quite high. There were many outliers in many columns and after analyzing the data, those outliers removed and dataset prepared for model building. Various algorithms apllied on prepared datset afetr train and test split of dataset. <b>Linear Regression algorithm performed very poorly on given dataset. It predicted 0.60 R2 score on train and test dataset. Decision Tree predicted 0.99 for Train dataset and 0.49 for test. It’s observed that its a overfitting model. XG Boost predicted good accuracy on train and test dataset. It predicted 0.77 and 0.76 R2 score.<b/></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Saurabh Funde > | Avid Reader | Data Science enthusiast |

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurabhfunde/)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@saurabh.f)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>Jonathan Lee, 'Notes on Naive Bayes Classifiers for Spam Filtering'. [Online].</p>
      <p>Available: https://courses.cs.washington.edu/courses/cse312/18sp/lectures/naive-bayes/naivebayesnotes.pdf</p>
  </li>
  <li><p>Wikipedia.org, 'Naive Bayes Classifier'. [Online].</p>
      <p>Available: https://en.wikipedia.org/wiki/Naive_Bayes_classifier</p>
  </li>
  <li><p>Youtube.com, 'Naive Bayes for Spam Detection'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=8aZNAmWKGfs</p>
  </li>
  <li><p>Youtube.com, 'Text Classification Using Naive Bayes'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=EGKeC2S44Rs</p>
  </li>
  <li><p>Manisha-sirsat.blogspot.com, 'What is Confusion Matrix and Advanced Classification Metrics?'. [Online].</p>
      <p>Available: https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html</p>
  </li>
  <li><p>Pythonforengineers.com, 'Build a Spam Filter'. [Online].</p>
      <p>Available: https://www.pythonforengineers.com/build-a-spam-filter/</p>
  </li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h4>Source Directories:</h4>
<ul>
  <li><b>train directory</b> - Includes all emails for the training phase of the program.</li>
  <li><b>test directory</b> - Includes all emails for the testing phase of the program.</li>
</ul>


