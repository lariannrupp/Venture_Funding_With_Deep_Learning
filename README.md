# Venture_Funding_With_Deep_Learning

---

![Emotion-Woman-Psychology-Microchip-Brain-Chip-5750666](https://user-images.githubusercontent.com/95719899/162646215-81acfb26-deef-426e-b7ff-fbf797e8efad.jpg)


---

The purpose of this exercise is to add hidden layers to a neural network until the predictive model for "success of venture funding applicants" reaches best fit




---




## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 


![Screenshot 2022-04-10 181740](https://user-images.githubusercontent.com/95719899/162646265-0890547e-8699-4f32-a150-6d9647ab672b.jpg)



---

## Installation Guide

To use the app, from the Github repository, download:
- **venture_funding_with_deep_learning.ipynb** Jupyter file 
- **Resources** folder for .csv data

Use either Terminal or GitBash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

You may need to install TensorFlow in Terminal or GitBash.

Install TensorFlow by using the conda install command as follows:
> pip install --upgrade tensorflow


To run the app, navigate to the root directory, which contains **venture_funding_with_deep_learning.ipynb** and the **Resources** folder and then type
'jupyter lab'

Alternatively, the program can be ran in Google Colab.



---

## Usage

As you run through the exercise, observe how I optimized my neural network by doing the following:


* Prepare the data for use on a neural network model.

* Compile and evaluate a binary classification model using a neural network.

* Optimize the neural network model by adding hidden layers until the model is overfit. 

---

## Results

Original Model using no additional optimizations

![Screenshot 2022-04-10 182906](https://user-images.githubusercontent.com/95719899/162646892-7d4e8486-88bf-4e99-99d0-f396320ff42e.jpg)



Alternative Model 1 using 2 hidden layers

![Screenshot 2022-04-10 182921](https://user-images.githubusercontent.com/95719899/162646897-818d0f0a-b9cc-494f-b20e-dfabcf982054.jpg)



Alternative Model 2 using 1 hidden layer

![Screenshot 2022-04-10 182934](https://user-images.githubusercontent.com/95719899/162646908-1ec19c57-2b49-4f0f-84a1-f7765dbbdcec.jpg)


Alternative Model 3 using 3 hidden layers

![Screenshot 2022-04-10 182954](https://user-images.githubusercontent.com/95719899/162646916-fe06fcf1-cdfa-48d7-a175-b954707ddd87.jpg)

---

## Discussion:

The most accurate model for predicting whether a venture funding applicant will be successful is Alternative Model 2, which uses 1 hidden layer and has an accuracy score of 73.29%.

The other models are either underfit or overfit, compared to Alternative Model 2.

---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module , accessed on 2022.04.10. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
