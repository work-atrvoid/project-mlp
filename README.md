# Project MLP: Machine Learning Portfolio

![Project Overview](assets/project-overview.png)

**Project MLP**, which stands for **Machine Learning Portfolio**, is a collection of mini machine learning projects designed to showcase my understanding of ML concepts. I created this repository to evaluate my skills in ML and my capability to solve real-world problems. Throughout this project, I gained valuable insights into plotting different types of data and applying various algorithms to address them.

### Projects Included



The following problems have been solved in this repository:

1. **House Price Prediction**: Using simple and multiple linear regression.

2. **China's GDP Prediction**: Utilizing non-linear regression (sigmoid function).

3. **Fish Weight Prediction**: Implementing simple and multiple polynomial regression.

4. **Customer Churn Detection**: Applying decision trees.

5. **Heart Attack Probability Prediction**: Utilizing the k-nearest neighbors algorithm.

6. **Wine Quality Prediction**: Using logistic regression.

7. **Student Performance Prediction**: Applying the support vector machine algorithm.

8. **Customer Segmentation**: Utilizing three different algorithms:
   
   - K-means
   - DBSCAN
   - Hierarchical/Agglomerative Clustering

9. **Movie Recommendation System**: Implementing two different algorithms:
   
   - Content-Based Filtering
   - Collaborative User-Based Filtering

![Technologies Used](assets/technologies-used.png)

- Python programming language
- Jupyter Notebook
- NumPy library for mathematical purposes, array/matrix manipulations, and more
- Pandas library for DataFrame and dataset manipulations
- Scikit-learn library for machine learning models, preprocessing datasets, and model evaluation
- Matplotlib library for plotting and visualization
- Seaborn library for styling and creating pair plots
- Plotly library for interactive plots
- Dtreeviz library for visualizing decision trees
- SciPy library for optimization and dendrogram clustering

![Leanrning Outcomes](assets/leanrning-outcomes.png)

Throughout this project, I have developed a deeper understanding of the following:

- The application of various machine learning algorithms and their suitability for different types of problems.
- Data preprocessing techniques and their impact on model performance, such as one-hot encoding, label encoding, train-test splitting, normalizing with different methods (e.g., standardization or min-max scaling), and more.
- The importance of data visualization in understanding model outputs and improving insights.
- The need for careful analysis and consideration. For example, in GDP prediction, while a growth rate plot might suggest a polynomial relationship, it's important to recognize that moving from 0 to 0.9 is relatively easy, whereas moving from 0.9 to 1 is more challenging. Developing countries can progress more easily by following the paths of developed countries, while developed countries must innovate to achieve further growth, which led me to use a sigmoid non-linear function instead of a polynomial one.
- Sometimes, finding that there is no relationship between two parameters can be as insightful as discovering a relationship. For instance, in student performance prediction, understanding that there may not be a straightforward relationship between weekly study hours and better grades led me to consider the possibility of a hyperplane in a higher-dimensional space, which ultimately helped in solving the problem using the support vector machine algorithm.
- Hands-on experience with multiple libraries and tools commonly used in the machine learning field.

### Future Directions

I plan to explore deep learning and additional classic ML algorithms. If I discover any new mini-projects that align with this portfolio, I will gladly include them!

### Questions and Feedback

If you have any questions or feedback regarding this project, please feel free to contact me. I welcome any thoughts or suggestions you may have!

If you enjoyed my work or found this portfolio helpful, please consider giving it a star! Your support encourages me to keep improving and sharing my projects with the community. Thank you!
