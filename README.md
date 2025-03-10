# 👩🧑🍎🛒 8. User Behavior in a Product App  

## 📌 Project Objectives  
- **Sales Funnel Analysis:**  
  - Examine how users navigate through each stage of the funnel.  
  - Identify the number of users who complete purchases versus those who drop off.  
  - Pinpoint specific stages where users encounter obstacles.
    
## 📖 Project Description  
You are working for a startup that sells food products. Your task is to analyze user behavior within the company's app.  

### Goals:  
1. **Sales Funnel Analysis**:  
   - Examine the sales funnel to understand how users move through each stage.  
   - Identify the number of users who complete purchases versus those who drop off.  
   - Pinpoint specific stages where users encounter obstacles.  

2. **A/A/B Test Results Analysis**:  
   - Evaluate an A/A/B test conducted to study the impact of a new font design.  
   - Compare two control groups (old font) and one experimental group (new font).  
   - Confirm the reliability of results by ensuring the control groups behave similarly.  

### Context:  
The A/A/B test aims to decide if changing the font is viable. If the two control groups differ significantly, it may indicate issues affecting test validity. Reliable comparisons help in determining data requirements for future experiments.  

The same dataset is used for general app analysis and the A/A/B test, as real-world experiments continuously assess app quality regardless of experiment participation.  

---

## 📊 Data Description  

Each log entry represents a user action or event:  
- **EventName**: Name of the event.  
- **DeviceIDHash**: Unique user identifier.  
- **EventTimestamp**: Event timestamp.  
- **ExpId**: Experiment group number:  
  - **246, 247**: Control groups (old font).  
  - **248**: Experimental group (new font).  

---
## 📊 Project Results  

### 🧪 A/A/B Test Findings  
- **p-values** are significantly **higher** than the corrected significance level **(0.0167)**.  
- There are **no statistically significant differences** between the groups (**246, 247, and 248**).  
- This confirms that the groups were **properly divided**, ensuring **experiment reliability** and **valid decision-making**.  

### 📉 Sales Funnel Insights  
- **User participation** across all events **can be improved**.  
- The most **critical drop-off point** occurs **between the offer stage and the purchase stage**.  
- **Recommendations:**  
  - Introduce **discounts, special promotions, or bonus incentives** to encourage users to complete purchases.  
  - Optimize the user experience in key stages to **increase conversion rates**.
    

## 🛠️ Technologies Used  
- **Programming Languages**: Python  
- **Data Analysis**: Pandas, NumPy, SciPy  
- **Hypothesis Testing**: Stats  
- **Data Visualization**: Matplotlib, Seaborn  

---

## 📈 Skills Developed  
- Data Cleaning and Preparation  
- Event Funnel Analysis  
- A/B Testing and Experimentation  
- Statistical Hypothesis Testing  
- Data-Driven Decision-Making  
- Data Visualization and Reporting  

---

🔗 **Project Link**:https://github.com/Jeduardocastel/8.-User-Behavior-in-a-Product-App-/blob/main/projecto_integrado_11.ipynb
