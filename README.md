1 . A n a l y z e t h e d a t a c a r e f u l l y
2 . C h e c k t h e c o n s i s t e n c y o f d a t a s e t ( N u l l
v a l u e s , b l a n k o r N A N v a l u e s )
3 . B u i l d t h e M L m o d e l u s i n g d e c i s i o n t r e e
a l g o r i t h m .
4 . F i n d t h e a c c u r a c y s c o r e f o r t e s t d a t a
5 . P r e d i c t t h e r e s u l t s o n t e s t d a t a s e t a n d
c o m p a r e a c c u r a c i e s w i t h t r a i n d a t a .
TECH STACKS USED

L I B R A R I E S F O R M A C H I N E L E A R N I N G

M O D E L
1. Random forest regressor
2. Python
3. Matplotlib
4. Seaborn
5. RandomizedSearchCV

FLOW PROCESS FOR MODEL

1. Data cleaning
2. Exploratory Data Analysis (EDA)
3. Model selection

4. Hyperparameter tuning
5. Price prediction

BRIEF EXPLANATION OF PROCESSES FOR

MODEL
1. As given in the problem statement we have to train a model to
predict the price of car. We will be using numpy to create array of our
dataset and we are using pandas to load our dataset and numbers
into tables called data frames .We will be using is.null() method to
check if any column is having null values .Then we will be converting
year object into time and remove kms from kms_drive.
2. We will be classifying each feature as either categorical, numerical,
continuous or discrete feature. Then we also used some libraries for
visualization of data such as Matplotlib and seaborn. For visualization
we will be using graphs and heat maps to find correlation between
values.
3. To train the model we will be using Random Forest Regressor.
Random Forest algorithm is an ensemble model of decision tree that
uses two or more models in combination for prediction. We are using
Random forest regressor because it gives better accuracy. Since we
will be predicting numerical value therefore it is always better to use
random forest. Random forest algorithm is also less prone to
overfitting.
4. RandomizedSearchCV is the best estimators and parameters for the
data.It will further more increases the r score of our model. So we
will be using it increase our accuracy.
5. Then we will be building the final final prediction model.

