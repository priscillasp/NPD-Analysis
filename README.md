# Analysis of Narcissistic Personality Disorder in Reddit Posts
![Screenshot 2024-08-05 at 5 45 08 PM](https://github.com/user-attachments/assets/7830cd8d-8ab3-4191-b11f-2a61ac0eaad0)
Created using Tableau Desktop. 


## Project Overview
This project analyzes a dataset of Reddit posts related to narcissistic personality disorder (NPD), focusing on identifying common themes and experiences shared by victims of narcissistic abuse. The analysis includes data preprocessing, identification of key terms and roles associated with narcissists, frequency analysis of victim experiences, and thematic analysis using Non-negative Matrix Factorization (NMF) to uncover prevalent topics within the posts.


## Repository Contents
- original_npd_reddit_posts.csv: Original dataset of Reddit posts.
- victim_experience_category.csv: Contains frequencies of target terms related to manipulative behaviors.
- found_terms_frequency.csv: Frequency of specific terms found in the dataset contributing to target categories.
- final_data.csv: Final cleaned and processed dataset.
- narcissist.ipynb: Jupyter notebook containing all scripts used for data analysis.

## Project Structure
### Data Preprocessing
The Jupyter notebook begins with data preprocessing steps including cleaning date and time formats, dropping unnecessary columns, and general data cleaning using Pandas.

### Role of Narcissist in Victims' Lives
This section explores how frequently various roles associated with narcissists (e.g., mother, father, church leader) are mentioned. Functions were developed to search through titles and content of posts to identify mentions of specific person types, helping categorize posts based on the mentioned narcissist role.

### Common Victim Experiences
Analysis of common victim experiences involved defining target terms for various manipulative behaviors:

Emotional Abuse: Terms like 'gaslight', 'manipulate', 'emotional blackmail'.
Coercive Control: Includes 'control', 'dominate', 'trackers', 'clothes'.
Physical Abuse, Financial Control, etc.
The frequency of these target terms was analyzed to understand how often each term appeared in the posts and contributed to their respective categories. Interesting finding is that a large part of coercive control was restrictions around what the victim wears. 'forbidden dressing' and 'clothes' were some of the most common victim experiences that fell in to control category. 

### Found Terms Frequency Analysis
This analysis focused on the frequency of terms contributing to identified target categories, illustrating the prevalence of specific behaviors or experiences within the posts.

### NMF Topic Modeling
Non-negative Matrix Factorization was applied to discover underlying topics in the dataset. The analysis revealed four distinct topic clusters related to the nature and impact of narcissistic abuse.

## Technologies Used
- Python: Primary programming language.
- Pandas & NumPy: For data manipulation and numerical analysis.
- NLTK: Used for text processing and frequency analysis.
- Scikit-learn: Applied for NMF topic modeling.
- Matplotlib & Seaborn: For generating visualizations.

## Contributions
This project was solely developed by Priscilla Morales, @priscillasp. Contributions, issues, and feature requests are welcome.

## Contact
For any inquiries, please priscillatm24@gmail.com.

 
