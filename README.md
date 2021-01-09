# IITG Student's Grade Predictor
## Introduction
Freshers who don't know much about academics and college life. Everybody wants to get good grades along with that they want to enjoy and explore too, as the college is new to them. But most of them can't manage we see those who get good grades have to sacrifice exploring college life. On the other hand, those who choose to enjoy got penalize for their grades.
We must require proper planning at the very starting time of the semester, so you can plan accordingly, and by following that we enjoy college life as well as get good grades.
## Objective
Analyze the input features given by the user and predict their future grades accordingly.
## Methods
One can find the full report here: [here](https://github.com/modabbir24/Grade-Prediction/blob/master/Report.pdf).
Student_student_grad_pred.ipynb is the python notebook.
The training data set one can find:
1.[transformed_data.csv](https://raw.githubusercontent.com/modabbir24/Grade-Prediction/master/transformed_data.csv)
2.[y_train.csv](https://raw.githubusercontent.com/modabbir24/Grade-Prediction/master/y_train.csv)
## Deployment
Prepare a HTML form for taking inputs from user. One will get the Html template inside template folder there is a file name index.html,we also use css to decorate the main page. On can get it inside staic folder where there is another folder named CSS inside that we get the css file template.css ,and for the prediction, there is another page which is also inside templates folder named result.html file.
Now refer to script.py file where we generate a flask based api. Requirement.txt contains also useful lib required for the deployement process. Finally, under heroku environment deployed the model.
The link to final website for user is: [here](https://iitg-stud-grade-pred.herokuapp.com/).
## Conclusion
This web application takes input which contain data related to how serious and time they can devote for the sem. Accordingly, it can predict there future grades. It helps user to know where are the areas they need to improve. To balance both good grades and College life.
