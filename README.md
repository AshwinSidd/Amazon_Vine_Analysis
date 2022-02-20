# Amazon_Vine_Analysis

## Overview
In this analysis, we analyzed the Amazon reviews written by members of the paid Amazon Vine program. I picked the kitchen database and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I then used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.
*Vine Reviews -  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.*

## Results
**Vine reviews and non-Vine reviews**

The total number of Vine reviews (paid reviews) for the kitchen products were **1207** whereas the total number of unpaid reviews were **97839**

![image](https://user-images.githubusercontent.com/92342751/154853566-4aa9359a-b0fc-430a-9c4e-571bd7120c51.png)

![image](https://user-images.githubusercontent.com/92342751/154853700-2bfa173a-55e5-452d-9b4a-b9ce703d364c.png)

**5 star reviews**
- Vine reviews: total number of 5 star vine reviews were - 509

![image](https://user-images.githubusercontent.com/92342751/154853915-7bafcc3d-c060-45c6-882e-92b3724e36ae.png)

- Non-vine reviews: total number of 5 star non vine reviews were - 

![image](https://user-images.githubusercontent.com/92342751/154853957-d1698552-b0e5-45ed-9a30-89607639caf7.png)

**Percentage of 5 star reviews**
- Vine reviews percentage: percentage of 5 star vine reviews was 42.1

![image](https://user-images.githubusercontent.com/92342751/154854022-ea64bd3b-49c6-4400-9b72-2d4ef6419b10.png)

- Non-vine percentage: 5 star non vine reviews percentage stood at 46.8

![image](https://user-images.githubusercontent.com/92342751/154854070-aaae2387-8cb6-45f9-83b6-a13534241130.png)

## Summary
As per the results, the percentage of 5 star reviews via the Vine program is 42% while non-vine was at 46.8. Going by this, there seems to be no bias when consumers rate and review the kitchen products on Amazon. However, the Vine reviews percentage for 5 star only considered helpful votes which also subsequently reduced the total number of reviews. It would be helpful to take all reviews into account and not just the helpful votes. 

More-over, the data shows all kitchen products but we could try further filtering the kitchen items into small and large appliances as well as by the sellers. This would give an even more in dept analysis as to which kind of appliances and sellers are gaining good positive reviews. 
