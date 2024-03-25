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

This is the 10 frequently asked questions using the HDBSCAN clustering result :

| Cluster name | Questions |
| --- | ----------- |
| 1 | Can I choose my room preferences when I book?<br>Can I get assistance with tour bookings or tickets?<br>Can I arrange for a wake-up call in the morning?<br>Can I store valuable items in a hotel safe?<br>Can I change my room type upon arrival if available?<br>Can I arrange for early morning coffee or tea delivery?<br>Can I have flowers or gifts delivered to my room?<br>Can I use a hotel phone for local calls?<br>Can I upgrade my room after checking in?<br>Can I book a room for an extended period such as a month?<br>Can I request a late-night check-in or early check-out?<br>Can I get assistance with planning local sightseeing tours?<br>Can I book a conference room or business meeting space?<br>Can I have a private event with personal catering?<br>Can I receive detailed maps of local walking tours?<br>Can I have a personal trainer for in-room workouts? |
| 2 | What's your policy on early check-in requests?<br>What's the hotel's policy on lost and found items?<br>What's the policy on lost or misplaced room keys?<br>What's the procedure for early check-out?<br>What's the policy for receiving mail or packages?<br>What's your policy on accommodating dietary restrictions for meals? |
| 3 | Are there designated smoking areas on the property?<br>Are there any nearby scenic walking or jogging trails?<br>Are there any nearby scenic walking or jogging trails?<br>Is there a designated area for picnics or outdoor dining?<br>Is there a designated area for meditation or yoga?<br>Is there a designated area for art or craft workshops? |
| 4 | How can I access the hotel's full menu of services and amenities?<br>How can I access the hotel's digital concierge services?<br>How can I access the hotel's art or sculpture gallery?<br>How can I access the hotel's library of books or movies?<br>How can I access the hotel's VIP or concierge lounge? |
| 5 | Is there a fitness facility or gym within the hotel premises?<br>Is there a pool or spa on the hotel premises?<br>Is there a library or reading room within the hotel?<br>Is there a quiet area for reading or studying within the hotel? |
| 6 | Is there a quiet time policy in the hotel?<br>Is there a curfew or quiet hours in the hotel?<br>Is there a loyalty program for frequent guests?<br>Is there a car rental service available at the hotel? |
| 7 | Is there an airport shuttle service available?<br>Is there a courtesy shuttle to popular tourist attractions?<br>Is there a shuttle to nearby golf courses? |
| 8 | Do you offer any special packages for events or celebrations?<br>Do you offer assistance for planning proposals or special occasions?<br>Do you provide special amenities for honeymooning couples? |
| 9 | Do you offer laundry or dry-cleaning services?<br>Do you offer babysitting or childcare services?<br>Do you provide transportation to local hospitals or medical facilities? |
| 10 | Can I request a specific floor or room location?<br>Can I schedule wake-up calls with specific music or sounds?<br>Can I schedule room cleanings at specific times? |

## Authors

* **Yassine DRISS** - *Final year AI and Data science student* - [Yassine DRISS](https://github.com/cinex10)

