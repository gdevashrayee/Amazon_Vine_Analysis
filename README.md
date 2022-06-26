# Amazon_Vine_Analysis

## Analysis Overview
This project explores the Amazon Vine service to see if there is a predominance of favourable Vine users' reviews.
In order to extract the dataset, transform the data, connect to an AWS RDS instance, load the changed data into pgAdmin, and calculate various metrics, the study uses PySpark to carry out the ETL process.


## Results

* How many Vine reviews and non-Vine reviews were there?

- Vine reviews <p align="center">

![x](./img/img_1.png)

</p>

<br>

- Non-Vine reviews <p align="center">

![y](./img/img_2.png)

</p>

<br>


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 5 Star Vine reviews <p align="center">

![z](./img/img_3.png)

</p>

<br>

- 5 Star Non-Vine reviews <p align="center">

![a](./img/img_4.png)

</p>

<br>

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- Percentage of Vine reviews with 5 Stars <p align="center">

![b](./img/img_5.png)

</p>

<br>

- Percentage of Non-Vine reviews with 5 Stars <p align="center">

![c](./img/img_6.png)

</p>

<br>


## Summary
Only 39% of reviews that weren't part of the Vine programme were rated with five stars, compared to 51% of Vine reviews. This explains an optimism bias for Vine programme reviews.
In addition, we could evaluate the statistical distribution of the star rating for both Vine and non-Vine reviews.


























