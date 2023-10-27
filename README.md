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
| 1 | How can I arrange transportation to local attractions?<br>Can I get assistance with tour bookings or tickets?<br>Is there a courtesy shuttle to popular tourist attractions?<br>Can I get assistance with planning local sightseeing tours?<br>Can I receive detailed maps of local walking tours? |
| 2 | Is there a quiet time policy in the hotel?<br>Is there a curfew or quiet hours in the hotel?<br>Is there a library or reading room within the hotel?<br>Is there a quiet area for reading or studying within the hotel?<br>How can I access the hotel's library of books or movies? |
| 3 | Can you provide information on your room types?<br>Is room keycard access required for specific hotel areas?<br>Can I request a specific floor or room location?<br>Are there any security measures in place within the hotel? |
| 4 | Is there a fitness facility or gym within the hotel premises?<br>Is there a pool or spa on the hotel premises?<br>How do I access the hotel's spa or wellness center?<br>Are there options for in-room massages or spa treatments? |
| 5 | Could you explain the hotel's reservation cancellation policy?<br>What's the hotel's policy on lost and found items?<br>What's the policy on lost or misplaced room keys?<br>Do you have a lost and found department for guests? |
| 6 | How do I request a late check-out?<br>Can I request a late-night check-in or early check-out?<br>Is there a security escort service for late-night arrivals? |
| 7 | Is there an airport shuttle service available?<br>Do you provide airport pick-up services?<br>Is there a helipad or space for helicopter arrivals? |
| 8 | Are there recommended nearby restaurants and attractions?<br>Are there any outdoor seating or dining options on-site?<br>Is there a designated area for picnics or outdoor dining? |
| 9 | What are your hotel's check-in and check-out timings?<br>How can I access the hotel's guest reviews?<br>How can I access the hotel's event calendar?<br>How can I receive notifications about hotel promotions?<br>Can I participate in a hotel loyalty program upon check-in?<br>How can I access the hotel's VIP or concierge lounge?<br>How can I access information on hotel awards and accolades?<br>How can I access information on hotel partnerships or affiliations? |

## Authors

* **Yassine DRISS** - *Final year AI and Data science student* - [Yassine DRISS](https://github.com/cinex10)

