# Hackathon Success and Technical Expertise

## 🎉 Thrilled to Share Some Great News! 🎉

My team and I proudly secured **3rd Prize at the 2024 ITDS Business Analytics Hackathon**! 🏆✨

The journey was nothing short of amazing, starting with the Hackathon Round, where over **20-30 talented teams** competed, followed by the Final Round, where the top 6 teams presented their findings to **industry experts**. The level of competition and innovation was truly inspiring.

Our presentation on the dataset provided by **Peterbilt Motors Company** was rigorously evaluated by seasoned professionals, and this recognition is a testament to the hard work, creativity, and analytical rigor that my team brought to the table.

### Team Members

A heartfelt thank you to:

- **Roberto Cavazos**
- **Sarvamangala Sahithi Pulugurta**
- **Sai Raj Pujolu**
- **Anas Syed**

This experience has been a fantastic opportunity to grow as a **data analyst, machine learning engineer, and problem solver**, and I’m excited to take these learnings into future projects.

Here’s to more milestones, collaboration, and innovation ahead! 🚀💡

---

## Technical Expertise

Our solution for the hackathon utilized advanced **data analytics** and **machine learning** techniques to address the challenge provided by Peterbilt Motors Company. Below are the details of our technical process:

### 1. Problem Statement

With the vast array of truck configurations offered by Peterbilt Motors, identifying the root causes of **higher warranty costs** is a complex task. The Advanced Analytics team tasked us with analyzing two datasets:

1. **Truck Attributes**
2. **Warranty Claims**

#### Key Questions:

1. Which attributes drive warranty costs?
2. How do attribute combinations influence costs?
3. What predictive frameworks can help mitigate future costs?

### 2. Methodology

#### **Data Preparation**

- **Datasets**: Two datasets were provided - Truck attributes and warranty claims.
- **Mapping**: Cost values were mapped to a numeric scale (Very Low = 1 to Very High = 5).

#### **Analysis Techniques**

- **Kruskal-Wallis H-Test**: Used for individual attribute significance analysis.
- **Interaction Term Analysis**: Studied interactions between attribute pairs.
- **Random Forest Regression**: Built a predictive model for warranty cost prediction.

#### **Implementation**

The following Python libraries and tools were utilized:

- **Pandas and NumPy**: For data manipulation and aggregation.
- **Scipy**: To perform the Kruskal-Wallis H-Test.
- **Scikit-learn**: For building and evaluating the Random Forest regression model.
- **Seaborn and Matplotlib**: For creating insightful visualizations.

### 3. Key Findings

#### Individual Attribute Analysis

- **Significant Attributes**: Attributes such as Attribute 4, Attribute 3, and Attribute 1 were strongly associated with increased warranty costs.

#### Attribute Pair Interactions

- Significant attribute combinations, such as **Attribute 2 + Attribute 8**, led to the highest combined costs (51.0 units).
- Other high-cost combinations included **Attribute 2 + Attribute 4 (49.0 units)** and **Attribute 4 + Attribute 1 (40.8 units)**.

#### Predictive Modeling Results

- **Model**: A Random Forest Regressor achieved a **test accuracy of 29.7%**.
- **Top Predictors**:
  - Attribute 4
  - Attribute 3
  - Attribute 1

#### Visual Insights

Below is an example of the visual analysis performed during the project:

![Mean Total Claim Cost by Attribute 1](image.png)

This bar graph shows the **mean total claim cost by Attribute 1**, with clear peaks indicating specific attribute options leading to higher costs.

---

## Recommendations

Based on our analysis, we recommend the following:

1. **Attribute-Based Customization**: Focus on reducing the impact of high-cost attributes and their combinations.
2. **Data-Driven Decision Making**: Implement predictive models to preemptively flag high-cost configurations.
3. **Continuous Monitoring**: Update models and analysis periodically as new data becomes available.

---

### Thank You!

This project was an incredible journey of **collaboration and innovation**. A special thanks to **Sourav Chatterjee, PhD**, and the organizing committee for providing such a great platform to learn, collaborate, and showcase our skills.

If you have any questions or need further insights, feel free to reach out!

