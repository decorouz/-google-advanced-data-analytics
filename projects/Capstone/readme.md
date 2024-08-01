# Projects/Capstone: Salifort Motors Workforce Analysis

## Background of the Salifort Motors Scenario

### About the company

Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles.

### Business case 
As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points you deem helpful.

### The value of your deliverable

For this deliverable, you are asked to choose a method to approach this data challenge based on your prior course work. Select either a regression model or a tree-based machine learning model to predict whether an employee will leave the company. Both approaches are shown in the project exemplar, but only one is needed to complete your project.

## Insights

### Suggestions/Recommendations

**Predictive Model**
* **Refine Workload Management**: Balance workloads across all models and ensure that no employee consistently endures excessive hours. This is crucial since all models indicate a link between high average monthly hours and turnover.

* **Foster Professional Growth**: Strengthen career advancement frameworks to provide clear and attainable growth opportunities. Our analysis across all models confirms that lack of promotion is a strong turnover predictor.

* **Boost Job Satisfaction and Performance**: Develop programs to increase job satisfaction and address performance-related issues, as highlighted by the decision tree model. The insights from the more complex RF and XGB models support these findings and suggest that deeper, more nuanced factors may also play a role.

* **Project Allocation Scrutiny**: Monitor the number of projects assigned to employees. The decision tree model identified a higher project count as a risk factor for turnover, a pattern that was less pronounced but still observable in RF and XGB models.


**K-Means**

* **Green Cluster Employees**:** Balanced average on both average monthly hours and last performance rating but have a lower satisfaction level. It is advisable to investigate the underlying factors contributing to this dissatisfaction. Enhancing workplace conditions, providing recognition, or offering professional development opportunities could improve their job satisfaction.

* **Pink Cluster Employees**: Characterized by higher average monthly hours, these employees have a lower satisfaction level yet a high performance rating. This group may be at risk of burnout due to high workload despite their strong performance. Recommendations include reviewing their workload, considering more flexible hours, or offering additional support and incentives to maintain their performance without sacrificing well-being.

* **Blue Cluster Employees**: Wide range of performance ratings and satisfaction levels, but consistently report high average monthly hours. This suggests a potential imbalance in work distribution or inefficiencies that need to be addressed. Strategies might involve optimizing work processes, reassessing task allocations, or providing time management training to ensure that high work hours translate into productivity and job satisfaction.

* **Gold Cluster Employees**: Exhibit high performance ratings with mixed satisfaction levels and average to slightly lower monthly hours. This suggests they are efficient and effective but may need incentives to increase satisfaction, such as opportunities for advancement, recognition of their efficiency, or involvement in more challenging projects to align with their high performance.

### Conclusion

The comparative analysis of the decision tree (DT), random forest (RF), and XGBoost models (XGB) underscores several key factors influencing employee turnover. While the decision tree offered foundational insights, the RF and XGB models unveiled a richer, more detailed landscape of turnover predictors. The nuanced differences between these models suggest that a multi-faceted approach to retention strategies might be necessary, considering not only the quantity but also the quality and complexity of workload and career development opportunities

## Model Deployment
TODO
