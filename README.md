<p align="center">
  <h1 align="center">Frequently Asked Questions Extractor</h1>

  <p align="center">
    A notebook that leverage the power of NLP and Unsupervised learning in order to extract the most asked question from a huge corpus of question.
    <br/>
    <br/>
  </p>
</p>



## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Results](#results)
* [Authors](#authors)

## About The Project

![cluster plot](images/clusters_plot.png)

This project focuses on using advanced natural language processing techniques to extract and cluster frequently asked questions from a company's website. By generating an initial set of 130 potential questions, representing them numerically with pretrained BERT models, calculating their semantic similarity, and applying HDBSCAN clustering, we aim to automate the creation of a comprehensive FAQ section, ultimately improving customer support and enhancing the user experience on the company's website.

## Built With

This project is built with a powerful stack of tools, including :

* [Python]()
* [PyTorch]()
* [SentenceTransformer (BERT Model)]()
* [T-SNE for Dimensionality reduction]()
* [HDBSCAN for Clustering]()
* [Bokeh for Data visualization]()

## Results

This is the 10 frequently asked questions from the dataset that i have choose :

| Cluster name | Questions |
| --- | ----------- |
| 1 | Do you offer discounts for senior citizens or AARP members?<br>Do you provide discounts for military personnel or veterans?<br>Are there discounts for government employees or diplomats? |
| 2 | Do you offer babysitting or childcare services?<br>Are there designated pet-friendly rooms?<br>Are there options for in-room babysitting or childcare? |
| 3 | Are there any extended stay discounts available?<br>What's the process for extending my stay? |
| 4 | May I reserve a room with a scenic view?<br>Can I book a room with a balcony or terrace? |
| 5 | Could you detail the room service options and operational hours?<br>How do I access room service menus and pricing? |
| 6 | What's the policy for holding luggage before check-in or after check-out?<br>Can I leave my luggage at the front desk before check-in? |
| 7 | Can I choose my room preferences when I book?<br>Can I change my room type upon arrival if available? |
| 8 | What's your policy on early check-in requests?<br>What's the procedure for early check-out? |
| 9 | Are there any on-site meeting or event facilities?<br>Are there designated meeting or event coordinators on staff? |
| 10 | Can you provide recommendations for nearby shopping areas?<br>Do you offer transportation services to the city center? |

## Authors

* **Yassine DRISS** - *Final year AI and Data science student* - [Yassine DRISS](https://github.com/cinex10)

