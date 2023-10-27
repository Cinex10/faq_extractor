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

| Cluster name | Questions |
| --- | ----------- |
| cluster_28 | Can you provide information on your room types?<br>Is room keycard access required for specific hotel areas?<br>Can I request a specific floor or room location?<br>Are there any security measures in place within the hotel? |
| cluster_29 | What are your hotel's check-in and check-out timings?<br>How can I access the hotel's guest reviews?<br>How can I access the hotel's event calendar?<br>How can I receive notifications about hotel promotions?<br>Can I participate in a hotel loyalty program upon check-in?<br>How can I access the hotel's VIP or concierge lounge?<br>How can I access information on hotel awards and accolades?<br>How can I access information on hotel partnerships or affiliations? |
| cluster_6 | Are there any extended stay discounts available?<br>What's the process for extending my stay? |
| cluster_19 | Is there a fitness facility or gym within the hotel premises?<br>Is there a pool or spa on the hotel premises?<br>How do I access the hotel's spa or wellness center?<br>Are there options for in-room massages or spa treatments? |
| cluster_3 | How do I request a late check-out?<br>Can I request a late-night check-in or early check-out?<br>Is there a security escort service for late-night arrivals? |
| cluster_1 | Is there an airport shuttle service available?<br>Do you provide airport pick-up services?<br>Is there a helipad or space for helicopter arrivals? |
| cluster_13 | May I reserve a room with a scenic view?<br>Can I book a room with a balcony or terrace? |
| cluster_31 | Could you detail the room service options and operational hours?<br>How do I access room service menus and pricing? |
| cluster_20 | Are there recommended nearby restaurants and attractions?<br>Are there any outdoor seating or dining options on-site?<br>Is there a designated area for picnics or outdoor dining? |
| cluster_18 | Could you explain the hotel's reservation cancellation policy?<br>What's the hotel's policy on lost and found items?<br>What's the policy on lost or misplaced room keys?<br>Do you have a lost and found department for guests? |
| cluster_15 | Do you offer any special packages for events or celebrations?<br>Can I pre-order amenities like flowers or champagne for special occasions?<br>Do you offer assistance for planning proposals or special occasions?<br>Are there options for arranging surprise gifts or decorations?<br>Is there a photography service for special occasions? |
| cluster_10 | How can I arrange transportation to local attractions?<br>Can I get assistance with tour bookings or tickets?<br>Is there a courtesy shuttle to popular tourist attractions?<br>Can I get assistance with planning local sightseeing tours?<br>Can I receive detailed maps of local walking tours? |
| cluster_12 | What's the policy for holding luggage before check-in or after check-out?<br>Can I leave my luggage at the front desk before check-in? |
| cluster_24 | Can I choose my room preferences when I book?<br>Can I change my room type upon arrival if available? |
| cluster_2 | Do you offer discounts for senior citizens or AARP members?<br>Do you provide discounts for military personnel or veterans?<br>Are there discounts for government employees or diplomats? |
| cluster_4 | What's your policy on early check-in requests?<br>What's the procedure for early check-out? |
| cluster_17 | Are there any on-site meeting or event facilities?<br>Are there designated meeting or event coordinators on staff? |
| cluster_16 | Is there a quiet time policy in the hotel?<br>Is there a curfew or quiet hours in the hotel?<br>Is there a library or reading room within the hotel?<br>Is there a quiet area for reading or studying within the hotel?<br>How can I access the hotel's library of books or movies? |
| cluster_11 | Can you provide recommendations for nearby shopping areas?<br>Do you offer transportation services to the city center? |
| cluster_22 | Do you offer laundry or dry-cleaning services?<br>Can I schedule in-room laundry or dry-cleaning services? |
| cluster_8 | Are there designated smoking areas on the property?<br>Can I request a designated smoking balcony or terrace? |
| cluster_5 | Can I arrange for a wake-up call in the morning?<br>Can I arrange for early morning coffee or tea delivery? |
| cluster_7 | Do you offer babysitting or childcare services?<br>Are there designated pet-friendly rooms?<br>Are there options for in-room babysitting or childcare? |
| cluster_0 | Are there any nearby scenic walking or jogging trails?<br>Are there any nearby scenic walking or jogging trails? |
| cluster_23 | What's your policy on accommodating dietary restrictions for meals?<br>Can I have special dietary preferences noted for dining? |
| cluster_30 | Can I upgrade my room after checking in?<br>Can I schedule room cleanings at specific times? |
| cluster_14 | Are there any cultural or artistic events in the area?<br>Is there a designated area for art or craft workshops? |
| cluster_26 | Are there options for in-room cooking or kitchenettes?<br>Are there options for in-room cooking or kitchenettes? |
| cluster_9 | Can I schedule wake-up calls with specific music or sounds?<br>Are there options for arranging live music or entertainment? |
| cluster_25 | How can I access the hotel's art or sculpture gallery?<br>How can I access the hotel's cultural or historical exhibits? |
| cluster_21 | Can I receive information on hotel sustainability efforts?<br>How can I receive a copy of the hotel's sustainability report? |
| cluster_27 | Are there options for in-room cooking lessons or classes?<br>Are there options for in-room language or cooking lessons? |


## Authors

* **Yassine DRISS** - *Final year AI and Data science student* - [Yassine DRISS](https://github.com/cinex10)

