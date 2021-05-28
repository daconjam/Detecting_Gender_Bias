# Does Gender Matter in the News? Detecting and Examining Gender Bias
This repository contains code to reproduce analysis in ["Does Gender Matter in the News? Detecting and Examining Gender Bias"](https://camps.aptaracorp.com/ACM_PMS/PMS/ACM/WWW21COMPANION/80/f5cc74ef-7609-11eb-8d84-166a08e17233/OUT/www21companion-80.html#) by Jamell Dacon and Haochen Liu, as part of the The World Wide Web Conference 2021 -- WWW'21.

    
If you publish material based on material and/ or information obtained from this repository, then, in your acknowledgements, please note the assistance you received from utilizing this repository. By citing our paper and dataset repository as follows below, feel free to star ![GitHub stars](https://img.shields.io/github/stars/daconjam/Detecting_Gender_Bias?style=social) and/or fork ![Github forks](https://img.shields.io/github/forks/daconjam/Detecting_Gender_Bias?style=social)
both repositories so that academics i.e. university researchers, faculty and other scientists may have quicker access to the available datasets and large lists of gender-specific and gender-neutral possessive nouns, and career and family words. This will aid in directing others in obtaining the same datasets and files, thus allowing both replication and improvement of detecting, examining and mitigating gender bias.


## Addition Information: Correspondence

Personal Page: [Portfolio](https://www.cse.msu.edu/~daconjam/)


## Citation

Paper BiBTeX citation:
    
    @inproceedings{Dacon2021GenderBias,
      author = {Dacon, Jamell and Liu, Haochen},
      title = {Does Gender Matter in the News? Detecting and Examining Gender Bias},
      booktitle = {WWW},
      year = {2021}
      }
      

## Datasets
We conduct experiments to detect and examine the bias across the two datasets. We will now detail the datasets as follows:

### MIND
The [MIND](https://msnews.github.io/) dataset was collected from the Microsoft News website, for more detailed information about the MIND dataset, you can refer to the following paper: [MIND paper, (Wu et al., 2020)](https://msnews.github.io/assets/doc/ACL2020_MIND.pdf). They randomly sampled news from from October 12 to November 22, 2019 for 6 weeks creating two datasets i.e., MIND and MIND-small both totalling in 161,013 news articles. Each news article contains a news ID, a category label, a title, and a body (url); however, not every article contains an abstract resulting in 96,112 abstracts. We used the training set (largest set of news articles) since both the validation and test sets are subsets of the training set. MIND is created to serve as a new news recommendation benchmark dataset.

    
### NCD
The [NCD](https://www.kaggle.com/rmisra/news-category-dataset) dataset was collected from [Huffpost](https://www.huffpost.com/). The news articles were sampled from news headlines from the year 2012 to 2018 totalling in 202,372 news articles. Each news article contains a category label, headline, authors, link, and date; however, not every article contains a short description (abstract) resulting in 200,853 abstracts. NCD serves as a news classification and recommendation benchmark dataset.


### Centering Reasonance Analysis 

Please refere to [Sociology Hacks](http://www.sociology-hacks.org/?p=151) for a step by step tutorial on Centering Reasonance Analysis (CRA) and mentions the necessary python packages needed for implementation.
    

>In addition, before you download the dataset(s), please read these terms and click below button to confirm that you agree to them for their respective usage licenses, acknowledgments and other details.



