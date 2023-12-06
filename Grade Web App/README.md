# GradeWebApp
A basic web application which utilizes flask to load a Random Forest Machine Learning algorithm to predict a users grade based on some key data points. 

We have 2 subfolders currently (model and templates). CSS is embedded in the HTML document for simplicity.
- **model**: Model contains our Random Forest NN model which has been saved as a "pickled" file, or a byte stream.
- **templates**: Templates contain our HTML code which is used to display input boxes ,to retrieve user data, and display the models prediction using the POST HTTP method.

**app.py**: Our app.py program creates a flask web application which loads our html and loads our "pickled" random forest ML model. After receiving the user input, our application uses the POST HTTP method to display the output to the user.

**pca_components.py**: This file is utilized in app.py to apply data transformation required to run our model on the input data.

Here is a link to a video demonstrating how our app is used and functions!
[ECS 171 Group 21 Web App Demo](https://www.youtube.com/watch?v=KV83YQVV7es)
