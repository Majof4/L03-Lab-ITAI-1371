**Janice**
# L03-Lab-ITAI-1371
ML Workflow &amp; Learning Types - Complete Instructions Individual Work Complete the Module_03_Lab_Exercise.ipynb notebook to understand the complete machine learning workflow and distinguish between supervised, unsupervised, and reinforcement learning approaches.
From Janice Underwood
Your Reflection and Analysis
Instructions: Complete the reflection below by editing this markdown cell.

My Understanding of Machine Learning Types
Supervised Learning: [dataset already labeled, example photos of dog labeled dog, computer will learn from theses examples if the animal is or not a dog]

Unsupervised Learning: [analyse is made by a set of samples without previous labeled. examplo, would analyse a group of photos and provide information about quality of the photo, shape.]

Reinforcement Learning: [learning by rewarding , examplo game. if correct gain point , eventually computer will find better strategy to not lose point]

My Analysis of the Wine Classification Project
Best performing model: [Logistic Regression]
Why do you think this model performed better?: [Logistic Regression works well with linearly separable data, which appears to be the case here]
What would you try next to improve performance?: [collect more data]
Real-World Application Ideas
Industry of Interest: [Medical]
ML Problem: [Cancer Disease Diagnosis and Early Detection thorugh radiology image]
Type of ML: [Supervised and Unsupervised]
Data Needed: [age, sex, type of blood, Pre-existing conditions, tumor location, size, shape, texture, smoke, alcohol]
Key Learnings
Most important concept learned: [Understanding the data and choosing the right features is often more important than choosing the most complex model.]

Most challenging part: [evaluation was the most challenged]

Questions for further exploration: [How can we explain the model's predictions to non-technical stakeholders]

## Kim
### My Understanding of Machine Learning Types
**Supervised Learning**: computer is trained and taught what is correct.

**Unsupervised Learning**: computer finds relationships between data with no training or input data.

**Reinforcement Learning**: computer learns itself by trials with penalties and rewards to gain experience.
### My Analysis of the Wine Classification Project

**Best performing model**: Random Forest

**Why do you think this model performed better?**: It can use multiple factors like alcohol, malic acid, ash, etc. to and combine decision paths to classify wine accurately.

**What would you try next to improve performance?**: Dimensionally remove to reduce noise.

### Real-World Application Ideas

**Industry of Interest**: Customer service

**ML Problem**: understands the expectation of customers and categorizes it to deal with.

**Type of ML**: Unsupervized learning

**Data Needed**: age, locations, behaviors, shopping frequency, feedback.

### Key Learnings

**Most important concept learned**: Understand and use appropriately the type of Machine Learning.

**Most challenging part**: Deploy the ML model to an specific case.

**Questions for further exploration**: How can we clean and preprocess unstructured data?

=======
______________

**Omar**

Your Reflection and Analysis
Instructions: Complete the reflection below by editing this markdown cell.

My Understanding of Machine Learning Types
Supervised Learning: The type of machine learning that involves a labeled data set input for model training.

Unsupervised Learning: The tyoe of machine learning that involves an unlabeled data set input for model training.

Reinforcement Learning: The method used in this excersise that involves reward/punishment for each time the machine iterates through the training data. This model rewards the machine when it yeilds a correct reuslt while alos issuing a punishment for an incorrect one.

My Analysis of the Wine Classification Project
Best performing model: Logistic Regression

Why do you think this model performed better?: Since our data consists of regression (decimal) data, we ustilized the correct model.

What would you try next to improve performance?: Increase the number of training iterations.

Real-World Application Ideas
Industry of Interest: Architectrual design - land development

ML Problem: Machine learning could recognize land sizes and the various setbacks that are given to calculate/predict the number of single-family residential lots that can be created after subdividing the property.

Type of ML: Reinforcement learning and supervised learning

Data Needed: local zoning and development codes, land dimensions, total acreage, type of streets, setbacks from deed restrcitions.

Key Learnings
Most important concept learned: ML workflow.

Most challenging part: Model peformance evaluaiton and selecting the correct machine learning type for the job.

Questions for further exploration: What is the best criteria to follow to decide on the which model type fits best?

______________________________________________________________________________________________________________________________

**Maria Jose Viveros Riquelme**
Instructions: Complete the reflection below by editing this markdown cell.

My Understanding of Machine Learning Types
*Supervised Learning*: Supervised learning is when the model learns from data that already has labels. For me, it feels similar to using statistics with dependent and independent variables. The algorithm attempts to predict the correct output based on the input features, identical to regression or classification.

*Unsupervised Learning*: Unsupervised learning is when we do not have labels. Instead, the model tries to find hidden patterns or groups in the data. I connect this with clustering in statistics, where the data is organized into groups based on similarity.

*Reinforcement Learning*: Reinforcement learning is different because the model learns through trial and error. It receives rewards or penalties depending on its actions. It is a decision-making process, similar to optimization in statistics, but more dynamic.

My Analysis of the Wine Classification Project
*Best performing model*: Logistic Regression

Why do you think this model performed better?: Logistic regression is often better than a decision tree when the relationship between features and the target is mostly linear, the data is clean, and the target is binary or categorical. It handles numeric and binary variables well, is simple, stable, and less prone to overfitting. Decision trees can manage mixed data and nonlinear patterns but are more prone to overfitting and require careful tuning.

What would you try next to improve performance? To improve performance, consider including various types of variables, increasing the amount of data, scaling and normalizing features, handling missing values and outliers, applying regularization, exploring alternative models, and tuning hyperparameters using cross-validation.

Real-World Application Ideas
Industry of Interest: Healthcare / Neuroscience

ML Problem: Predict individual risk for psychiatric disorders based on personality traits and frontal lobe development.

Type of ML: Supervised learning (classification for disorder risk categories).

Data Needed: Neuroimaging data (MRI, fMRI) for frontal lobe structure and activity, standardized personality assessments, genetic markers, demographic and clinical history.

Key Learnings
Most important concept learned: Combining neurobiological data with psychological assessments can improve early detection and personalized interventions for psychiatric disorders.

Most challenging part: Integrating heterogeneous data types (imaging, behavioral, genetic) and ensuring enough high-quality data for accurate predictions.

Questions for further exploration: How can ML models account for developmental changes in the frontal lobe over time? Can personality assessments reliably improve predictive power alongside biological markers? What ethical considerations arise when predicting psychiatric risk?

