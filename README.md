# Nutrition Facts Label Scanner

Final project of the Building AI course


## Summary

Nutrition Facts labels can be confusing or unclear to everyone.
The objective of this project is to create a mobile application that can scan labels with nutritional information and give the user recommendations about possible health risks in a general way and also based on personalized information about the user's diseases.


## Background

The Nutrition Facts label is intended to inform you of food choices that may have positive or negative effects on your health.
Calories, Sodium, Calcium, Vitamin D, Potassium, Saturated Fat, Dietary Fiber, Added Sugars are examples of items reported per serving or package.

Eating too much or too little of some nutrients can increase the risk of certain diseases, including cardiovascular disease, osteoporosis, and high blood pressure (which can increase the risk of heart attacks, heart failure, stroke, kidney disease, and blindness).
Making healthy dietary choices helps reduce the risk of developing these diseases that are common in older adults.

Using AI, the user can easily scan the label, identify the components and get recommendations on the risks of eating the product depending on their age and pre-existing health conditions.


## How is it used?

The user installs an application on his mobile phone, where he enters some personal data
Once the configuration is done, the user can scan the label of a product with the nutritional information.
The data is sent to a back-end server where an AI system can identify all the input data and output health recommendations for the user.


## Data sources and AI methods

Sources:
- Personal data of the user such as age, sex and some common diseases such as high blood pressure, heart disease, diabetes, etc.
- Image of the Nutrition Facts label, scanned with the app

AI Methods:
- Machine learning for text recognition for scanned labels
- Neural network to process the input data and obtain final recommendations, based on test data validated by medical professionals


## Challenges

Limitations:
- The user should take the output of the application as a recommendation, not a medical diagnosis.
- Product labels may be in poor condition or difficult to scan due to product packaging


## What next?

Next steps:
- Interviews with doctors and specialists to get feedback and collect data
- Create a high level design, with application/server architecture
- Build a low level design
- Implementation of prototypes 
- Train and test the prototype model
- Alpha and Beta testing
- Final version for production


## Acknowledgments

Thanks the [Elements of AI](https://www.elementsofai.com/) team and the Helsinki University https://www.helsinki.fi/ for the knowledge sharing and the inspiration to go further
