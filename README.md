# Detecting_Gender_Bias
The primary goal of this project is to detecting and examining gender bias in news articles. 
This repository contains code to reproduce analysis in "Does Gender Matter in the News? Detecting and Examining Gender Bias" by Jamell Dacon and Haochen Liu, as part of the The Web Conference 2021 -- WWW'21.


 
 ## Datasets
We conduct experiments to detect and examine the bias across the two datasets. We will now detail the three datasets as follows:

### MIND
The [MIND](https://msnews.github.io/) dataset was collected from the Microsoft News website, for more detailed information about the MIND dataset, you can refer to the following paper: [MIND paper, (Wu et al., 2020)](https://msnews.github.io/assets/doc/ACL2020_MIND.pdf). They randomly sampled news from from October 12 to November 22, 2019 for 6 weeks creating two datasets i.e., MIND and MIND-small both totalling in 161,013 news articles. Each news article contains a news ID, a category label, a title, and a body (url); however, not every article contains an abstract resulting in 96,112 abstracts. We used the training set (largest set of news articles) since both the validation and test sets are subsets of the training set. MIND is created to serve as a new news recommendation benchmark dataset.

    
### NCD
The [NCD](https://www.kaggle.com/rmisra/news-category-dataset) dataset was collected from [Huffpost](https://www.huffpost.com/). The news articles were sampled from news headlines from the year 2012 to 2018 totalling in 202,372 news articles. Each news article contains a category label, headline, authors, link, and date; however, not every article contains a short description (abstract) resulting in 200,853 abstracts. NCD serves as a news classification and recommendation benchmark dataset.
    

>In addition, before you download the dataset(s), please read these terms and click below button to confirm that you agree to them for their respective usage licenses, acknowledgments and other details.



