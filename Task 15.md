&gt;                        Task 15: Intro to ML


# Machine Learning Concepts Report

---

## Video 1: Core ML Principles and Decision Trees

### Example of a Decision Tree
* A decision tree can be applied to decide admiration for StackQuest.
* Decision Trees are a form of Machine Learning.

### Overview of Machine Learning
* Machine learning is prediction and classification all over.

### ML Lingo
* Original Data (red dots): Training Data.
* Testing Data (blue dots): To compare predictions of the black line and the green squiggle.
![](https://github.com/Rehanljacob/Marvel-Level-0-/blob/main/pic%201.jpg?raw=true)

![](https://github.com/Rehanljacob/Marvel-Level-0-/blob/main/pic2.jpg?raw=true)

![](https://github.com/Rehanljacob/Marvel-Level-0-/blob/main/pic%203.jpg?raw=true)

### Observation:
* Although the green squiggle fitted training data more than the black line, the black line performed better in predicting speeds with the testing data.

### Morals of ML
1. We use testing data to test Machine Learning approaches.
2. Never be deceived by how good a ML algorithm fits the training data.

### Bias-Variance Tradeoff
* The green line fitting the training data but making poor predictions illustrates the Bias-Variance Tradeoff.

### Final Note
* New ML algorithms keep surfacing in the development stage.
* No matter the algorithm, the most important factor is not how fancy our model it is, but how it performs with the test data.

### Summary
* Machine Learning is predicting and classification.
* There are a lot of ways to do it, but the fact of the matter is that we choose which method suits our requirements using test data.

---

 

## Video 2: Data Preparation and Model Bias

### Case Study: Amazon's Recruitment Tool
* Amazon developed an experimental recruitment tool to select employees, but it favored men.
* It penalized resumes mentioning the word "women's" (e.g., "women's softball team captain").
* The problem was that the model had been trained on 10 years of resumes, which were largely men-dominated.

**Central Question**
Data preparation for Machine Learning: how?

---

### Step 1: Planning and Formulating the Problem
* Identify the problem to be addressed by Machine Learning.
### Step 2: Creating the Training Dataset
* **First obstacle:** How much data is needed to train a good model?
* *Answer:* There is no one formula. It depends on numerous factors.
* **Rule of thumb:** Collect as much data as possible, since it is difficult to determine the exact amount required.

**Examples of Dataset Sizes:**
* Gmail Smart Replies: 238 million sample messages.
* Google Translate: Trillions of examples.
* Tamkang University professor: Only 630 samples to train a neural network predicting compressive strength of high-performance concrete.

---


### Step 3: Data Processing
* Not only the size of the dataset but also the quality that counts.
* Principle: Garbage In, Garbage Out, models learn what they are trained for.
* Amazon's model did not work because training data was biased.
* Data collection needs to guarantee both quality and sufficiency for the task.
* Selected data needs to be converted into a processable form: this is Data Preparation.

---

### Data Processing Steps
1. **Labeling**
2. **Reduction and Cleansing**
* Dimensionality Reduction
    * Sampling
    * Cleaning:
        * Fill in missing cells with constants (e.g.,  median value for numeric columns).
        * Delete invalid or corrupted data.
3.	**Data Wrangling**
    * Convert raw data into a form that best describes the problem.
* **Formatting**: Convert dataset format to text  based format (e.g., CSV). Keep consistency (e.g., if "Florida" and "FL" are the same, choose one).
* **Normalization**: Unify the scale of values (e.g., scale between 0.0 and 1.0 using Min-Max Normalization).

---

### Feature Engineering
* Creating impactful features to enhance model performance.

---

### Conclusion

* A machine learning model is only as intelligent and precise as the data it's trained on.
* It can't correct for bias on its own (e.g., Amazon's case of semism was because of biased data).
* No perfect datasets exist, but striving to create good datasets is important.
* Preparing data is absolutely crucial and can take up to 80% of any data science project's time.


---
