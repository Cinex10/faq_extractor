# Frequently Asked Questions Extractor

a notebook that leverage the power of NLP and Unsupervised learning in order to extract the most asked question from a huge corpus of question.

<br/>
<p align="center">
  <h3 align="center">Frequently Asked Questions Extractor</h3>

  <p align="center">
    A notebook that leverage the power of NLP and clustering in order to extract the most asked question from a huge corpus of question.
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

This is a brief summary of the results :

| Cluster name | Questions |
| --- | ----------- |
| cluster_28 | Can you provide information on your room types?<br>Is room keycard access required for specific hotel areas?<br>Can I request a specific floor or room location?<br>Are there any security measures in place within the hotel? |
| cluster_29 | What are your hotel's check-in and check-out timings?<br>How can I access the hotel's guest reviews?<br>How can I access the hotel's event calendar?<br>How can I receive notifications about hotel promotions?<br>Can I participate in a hotel loyalty program upon check-in?<br>How can I access the hotel's VIP or concierge lounge?<br>How can I access information on hotel awards and accolades?<br>How can I access information on hotel partnerships or affiliations? |
| cluster_6 | Are there any extended stay discounts available?<br>What's the process for extending my stay? |
| cluster_19 | Is there a fitness facility or gym within the hotel premises?<br>Is there a pool or spa on the hotel premises?<br>How do I access the hotel's spa or wellness center?<br>Are there options for in-room massages or spa treatments? |
| cluster_3 | How do I request a late check-out?<br>Can I request a late-night check-in or early check-out?<br>Is there a security escort service for late-night arrivals? |
| cluster_1 | Is there an airport shuttle service available?<br>Do you provide airport pick-up services?<br>Is there a helipad or space for helicopter arrivals? |
| cluster_13 | May I reserve a room with a scenic view?<br>Can I book a room with a balcony or terrace? |

## Authors

* **Yassine DRISS** - *Final year AI and Data science student* - [Yassine DRISS](https://github.com/cinex10)

