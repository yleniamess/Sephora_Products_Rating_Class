# Sephora Products Rating Classification

### Project for Neural Computing Course of MSc in Data Science for Management (UniCT).

The work in this project is aimed at building a neural network infrastructure in the context of a classification problem.
In particolar, the problem outlined involved the prediction of the rating - from 1 to 5 stars - of any product in the Sephora online catalog, starting from some of the quantitative and non-quantitative information that can be found on the Sephora webpage.

The dataset used includes information about *Sephora sales*, the French multinational retailer of personal care and beauty products.

It consists of **9168 observations** (products) and **20 features** with mixed datatypes:

1.  **id** (*integer*): id of the product;
2.  **brand** (*object*): brand of the product at Sephora's website;
3.  **category** (*object*): category of the product at Sephora's website;
4.  **name** (*object*): name of the product at Sephora's website;
5.  **size** (*object*): size of the product;
6.  **rating** (*float*): customers can rate a product on a scale of 1 to 5 stars, so a product rating represents the average number of stars;
7.  **number_of_reviews** (*integer*): number of reviews of the product;
8.  **love** (*integer*): number of people loving the product, that is number of people who flagged the "heart" icon on the product sheet;
9.  **price** (*float*): price of the product;
10. **value_price** (*float*): value price of the product (for discounted products) that is the perceived or estimated value of the product for the customer;
11. **MarketingFlags** (*boolean*): marketing flags of the product from the website if they were exclusive or sold online only etc.;
12. **MarketingFlags_content** (*object*): kinds of marketing flags of the product;
13. **options** (*object*): options available on the website for the product such as colors and sizes;
14. **details** (*object*): details of the product available on the website;
15. **how_to_use** (*object*): instructions on how to use the product (if available);
16. **ingredients** (*object*): ingredients of the product (if available);
17. **online_only** (*integer*): whether the product is sold online only;
18. **exclusive** (*integer*): whether the product is sold exclusively on Sephora's website;
19. **limited_edition** (*integer*): whether the product is limited edition;
20. **limited_time_offer** (*integer*): whether the product has a limited time offer.

Out of the original 20 features, only 9 of them were considered as *predictors*:

* **number_of_reviews**
* **love**
* **price**
* **value_price**
* **category**
* **online_only**
* **exclusive**
* **limited_edition**
* **limited_time_offer**
