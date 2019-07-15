# Predicting Bike Sharing Patterns
This Repository stores my solution to the _"Predicting Bike Sharing Patterns"_ problem presented as the first project in the Deep Learning Nano Degree by Udacity.

### Overview
For this project I was given a dataset of bike sharing patterns, which can be found <a href="https://www.capitalbikeshare.com/system-data">here</a>. This data included the following attributes: 
<ul>
<li>Duration – Duration of trip</li>
<li>Start Date – Includes start date and time</li>
<li>End Date – Includes end date and time</li>
<li>Start Station – Includes starting station name and number</li>
<li>End Station – Includes ending station name and number</li>
<li>Bike Number – Includes ID number of bike used for the trip</li>
<li>Member Type – Indicates whether user was a "registered" member or a "casual" rider</li>
</ul>

### Purpose
The goal of this project was to create a prediction model that took in the above attributes as inputs and predicted the number of bikes hired as an output.

![](assets/neural_network.png)

### Methadology
First, I read the dataset into memory. Then I extract the relevent fields and scale the inputs against a mean and standard deviation found in the dataset. 

Next, I implement the solution for creating a Neural Network in python. All code for the implementation can be found <a href="https://github.com/MrDaubinet/Predicting-Bike-Sharing-Patterns/blob/master/my_answers.py">here</a>. 

Lastly, the Neural Network is initialized and trained. Its performance for training and validation loss can be seen in thhe image below. 

![](assets/loss.png)

### Results
Finally, the Neural Network is run against unseen testing data with its accuracy shown in the image below.

![](assets/test.png)