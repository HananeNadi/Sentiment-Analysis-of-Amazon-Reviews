# WinPro: A Website for Selecting Winning Products in E-commerce Through Review Analysis

## Overview 🚀
Online shopping presents a vast array of choices, making it increasingly challenging for both sellers and buyers. Sellers, especially those utilizing cash-on-delivery (COD) networks, face heightened financial risks due to manual selection processes. Traditional methods demand substantial time and resources, necessitating a smarter alternative. This research introduces a methodology enriched with sentiment analysis to streamline product selection. By integrating sentiment analysis with machine learning, it addresses sellers' unique challenges and enhances decision-making precision in the dynamic e-commerce landscape.

## Key highlights : 

- **Data Collection**: Utilized a vast dataset of Amazon's fashion reviews to train our model, ensuring comprehensive coverage and relevance.
  
- **Data Cleaning & Pre-Processing**: Employed meticulous data cleaning and preprocessing techniques to refine textual data, including the removal of punctuation and stop words, tokenization, and lemmatization, enhancing the effectiveness of sentiment analysis. 

- **Feature Extraction**: Implemented advanced text processing methodologies to convert fashion reviews into numerical vectors, leveraging techniques such as TF-IDF and n-grams to capture nuanced insights.

- **Exploratory Data Analysis (EDA)**: Conducted insightful visualizations and analyses to unravel key patterns and distributions within the dataset, facilitating a deeper understanding of underlying trends.

- **Machine Learning Models**: Explored a diverse range of machine learning algorithms, including SVM, Logistic Regression, Naive Bayes, and XGBoost, to discern the most suitable approach for classifying Amazon fashion reviews accurately.

- **Evaluation**: Employed rigorous evaluation metrics, including accuracy, precision, recall, and F1-score, to meticulously assess model performance. Leveraged grid search techniques to optimize model parameters, ultimately selecting SVM as the top-performing classifier for our task.

- **Deployment**: Created a user-friendly website with HTML, CSS, and Flask, offering intuitive design and enabling input of Amazon product URLs.

## Tools Used

- Python
- Flask
- HTML
- CSS

  
## Preview
 
<img width="849" alt="1" src="https://github.com/HananeNadi/Sentiment-Analysis-of-Amazon-Reviews/assets/127529925/b4031cca-4f3c-45a6-ad70-b484e1ecc4a9">

<img width="849" alt="2" src="https://github.com/HananeNadi/Sentiment-Analysis-of-Amazon-Reviews/assets/127529925/9ef75d23-7deb-4437-bde2-6975fb8969ff">

<img width="849" alt="3" src="https://github.com/HananeNadi/Sentiment-Analysis-of-Amazon-Reviews/assets/127529925/a7a161d0-ac0f-4eb8-9531-69384e9ed52f">

<img width="849" alt="4" src="https://github.com/HananeNadi/Sentiment-Analysis-of-Amazon-Reviews/assets/127529925/4b9c8825-7636-411c-b65b-2d079828199c">


## Behind the scenes

![URL](https://github.com/HananeNadi/Sentiment-Analysis-of-Amazon-Reviews/assets/127529925/dd33282a-e7b0-44d6-a457-09faace5e8f9)


## Requirement 
Web scraping Amazon can be challenging due to JavaScript rendering. For that, we used Splash to render JavaScript pages efficiently.

### Setup Instructions
Follow these steps to set up the project:

- **Step 1**: Install Docker to utilize the Splash rendering service.
Visit the official Docker website to download and install Docker: [https://www.docker.com](https://www.docker.com)

- **Step 2**: Download Splash Image
  Open a terminal and execute the following command to download the latest Splash image:

```bash
docker pull scrapinghub/splash
```

- **Step 3**: Start Splash Container
Run the following command to start the Splash container at port 8050:

```bash
docker run -it -p 8050:8050 --rm scrapinghub/splash
```
The Splash service is now running, and you are ready to use it for rendering JavaScript pages.
Now, You can run the code .


## Authors

- [@HananeNadi](https://github.com/HananeNadi)

## Contact Me

Feel free to contact me at:

- Email: nadi.hanane01@gmail.com
- LinkedIn: [Hanane Nadi](https://www.linkedin.com/in/hanane-nadi-32089a251/)





