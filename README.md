# survey_response_tex_IQ
Outside of work, this project was accomplished to add value to my Github. It is a practice session cleaning and presenting text.

Bit-ereum Lending Exploratory Data Analysis (EDA)
Case Study and Problem
Bit-ereum Lending is tearing it apart with our innovative blockchain based lending platform. We have experienced tremendous growth since we launched our one-of-a-kind lending product three years ago.

We take our customers feedback seriously and our Head of Lending is asking you to analyze all the customer survey data since last September because we want to understand how we are stacking up against our competitors.

Please analyze all the survey comments (Column G) and give us some insights on what our customers are saying about their interaction with us.

Focus of EDA
Our service level
Are we responding to our customers on timely basis? People hate waiting…

Our agent’s performance
Are we making positive connection with our customers? Providing world-class service is our goal.

Our product
We need to know if we are putting up too many barriers for them to qualify for a loan with us.

Steps for Analysis and Solution:
1) Read in Data and Evaluate Cleaning/Tidiness
2) Data Cleaning
3) Data Exploration
4) Key Take-Aways
1) Read in Data and Evaluate Cleaning/Tidiness
Summary:
Within the section, the dataset will be explored to validate data integrity. Those changes necessary to ensure data integrity will be noted for the next section which will directly address each issue. The importance here lies in the integrity of the analytical support provided to key stakeholders to drive positive value creation within strategic management initiatives.

The data will be assessed both visually and programmatically. Furthermore, statistical distributions will be used to ensure that anomalies are detected and properly imputed or erased. This will ensure a lack of pull on variance accounting within the Eigenvalues during dimensional reduction.

The steps for this sections are described generally below for clarity:

1) Read in dataset and import necessary packages

2) Visually Assess the Data

3) Programmatically Assess the Data

4) Note Necessary Changes for Cleaning Section

Notes for Cleaning, Wrangling, and Tidiness
Use Case Normalization
Make Spelling Maps and Correct Spelling
Remove stop words for character variance normalization
/, r, n, and \ need to split words to columns and be dropped for tokenization
Remove Punctuation
Utilize Stemming to properly interpret word meaning numerically
There are random character entries which require removal. These and stop words need to be NaNs so as to impute with the above sections in turn so as to not disrupt the integrity of the character distributions

2) Data Cleaning
Summary:
The purpose of this section is to correct issues found within the previous section. Those issues to be addressed are:

Use Case Normalization
Make Spelling Maps and Correct Spelling
Remove stop words for character variance normalization
/, r, n, and \ need to split words to columns and be dropped for tokenization
Remove Punctuation
Utilize Stemming to properly interpret word meaning numerically
There are random character entries which require removal. These and stop words need to be NaNs so as to impute with the above sections in turn so as to not disrupt the integrity of the character distributions

3) Data Exploration
Summary:
Within this section the text was explored and visualized to gain insight into the customer reviews.

The process will be similar for total, top response, and bottom response reviews. Each review will be disected by looking at distributions for comment character length, word count, and word lengths. Next words will be visualized by their occurence and then by their occurence in groups of 2 throughout reviews. Finally, a wordcloud visualization will be generated to show those words which occured most throughout the data.

This process will be repeated for the entire dataset, then for the top responses and bottom responses. This will allow for a complete understanding of customer sentiment from both satisfied and dissatisfied customers.

4) Key Take-Aways
The purpose of this Exploratory Data Analysis is once again:
To build an analysis based on our core focus areas:

Our service level – Are we responding to our customers on timely basis? People hate waiting…
Our agent’s performance – Are we making positive connection with our customers? Providing world-class service is our goal
Our product – We need to know if we are putting up too many barriers for them to qualify for a loan with us.
Breakdown of the T2B responses.
What are we doing right?
Why do our customers like us?
Breakdown of the B2B responses
What are we doing wrong?
How can we improve?
Breakdown of T2B Responses
What are we doing right?
Accomplished 'Core Focus' Areas:
Our Agent's Performance Specific Examples from Reviews:
  - About 1600 mentions of the word helpful
  - Similar mentions of the words: service, friendly, professional, and my questions
Our Product Specific Examples from Reviews:
  - Around 400 mentions among top reviews of the word loan
Why do customers like us?
Simply put, customers like us for our professional service and product. We should look to use this identity relationship that has formed with our customers for strategic marketing initiatives. This will lead to a sustainable brand image of customer/product centric.

Breakdown of B2B Responses
What are we doing wrong?
Neglected 'Core Focus' Areas:
Our Service Level Specific Examples from Reviews:

  - From the grouped occurrences, it is apparent our customers are telling us that response time using email, phone, 
    and any other method, is too slow. 
Our Product Specific Examples from Reviews:

  - Excessive mentions of the word loan cause concern. However, the axiom of the use of this term is ambigious,
    meaning the term may be used as a subject verses an identifier e.g. "The service was slow to respond on my 
    loan".
How can we Improve?
We need to investigate further into the subject of loan quality. Currently, it stands to be proven that our product is lacking. It does stand evident that our processes and ticket turn around times are too long for customers' liking. We need to dive into operations and gather ticket times for customer out-reach. The following steps would be to benchmark with competitors and refer to HR for employee trainings, or a logistics consultant for process improvement.

End of Presentation
