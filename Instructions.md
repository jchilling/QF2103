# Group Project: Research on Trading Strategies using Python

## Project Overview:

In this group project, you and your team will delve into the world of algorithmic trading by researching and implementing various trading strategies using Python. The goal is to gain hands-on experience in developing, testing, and optimizing trading algorithms while applying programming skills in Python.

## Project Details:

### Instructions:
- Compare the performance of two trading strategies applied to different stocks.
- Select 2 trading strategies of interest.
- For example, you may choose the strategies from Chapter 4 of the book: "Machine Trading: Deploying Computer Algorithms to Conquer the Markets" by Chan, Ernest P, published by Wiley trading (2017). The e-copy is available via NUS Libraries.
- The strategies you choose cannot be exactly the same as the one covered in lecture (Topic 8). Eg. if you want to use a classification method as the underlying technique, you should provide different features, etc.
- Data: Use the historical data in the file 'tr_eikon_eod_data.csv'. Focus on the five stocks 'AAPL.O', 'MSFT.O', 'INTC.O', 'AMZN.O', 'GS.N'.
- Split the time series into half for training and testing.

### (Recommended) Project Timeline:
- **Week 8: Selection**
  - Discuss the roles and responsibilities for each group member.
  - Choose and conduct research on the selected trading strategy.
  - Outline the logic, parameters, and key components of the strategy.
- **Week 9: Implementation**
  - Begin coding the trading strategy in Python.
  - Collaborate on coding tasks and ensure integration within the group.
  - Implement backtesting to evaluate the performance of the trading strategy using historical data.
  - Identify areas for improvement and optimization.
  - Experiment with different parameters and techniques to enhance strategy performance.
  - Discuss the potential challenges and risks associated with the chosen strategy.
- **Week 10-11: Documentation**
  - Work on the project report.
  - Practice and refine the group presentation.
- **Week 12: Presentation and report submission**

### Deliverables:
- A project report which consists of:
  - Overview of the chosen trading strategies.
  - Team roles and responsibilities (a table consisting of project tasks, team member involvement, descriptions of contributions, etc.).
  - Detailed explanation of the trading strategy logic.
  - Identification of key parameters.
  - Description of potential challenges and risks of the trading strategy.
  - Python code for the trading strategy.
  - Documentation within the code for clarity.
  - Results of backtesting, including performance metrics.
  - Analysis of optimization efforts and their impact on strategy performance.
  - Future improvements.
- **Final Presentation:**
  - 10-minute presentation including Q&A.
  - Showcase key findings, challenges faced, and lessons learned.
  - Each group member must present, and grades will be given based on the individual's presentation as well as the overall presentation.

### Evaluation Criteria:
- **Report (55%):**
  - The report will be evaluated in terms of efforts to obtain a better strategy, research depth, coding proficiency, and documentation. Five teams with the highest profit in training and testing data will be awarded a bonus mark.
- **Presentation (40%):**
  - The presentation will be evaluated in terms of the organization of the presentation, as well as clarity and professionalism in presenting findings.
- **Participation (5%):**
  - Group members will be asked to rate the effort given by each member.

  
  ## Additional Clarifications:

Here are some clarifications on the group project:

- You can search online to find more data (eg. volume/spread/etc.) for each stock. However, for the stock price and date range, please stick to the one provided in the csv file.
- You can use other libraries apart from what has been covered in the lecture.
- You should come up with two strategies to predict the stock price/direction and implement the buy/sell decision accordingly. The total returns can be computed like what we did in the lecture.
- **Correction and Clarification from the Previous Announcement:**
  - For the bonus mark, we will compare the maximum return you obtained (out of the two algorithms) for the return on the testing set.
  - To ensure consistency, please do a sequential train-test split and split the data such that 80% are the training set and 20% are the testing set.