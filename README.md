# **Amazon Vine Analysis**

## ***Overview***
This project's main goal is to analyze the Amazon reviews that were done by members of the Amazon Vine program. To complete this analysis I used data that was related to reviews about the category of software.

### **How the analysis was conducted:**
I used AWS, PostgreSQL, PySpark, and Google Colab to perform an ETL on the data. 

## ***Results***
The analysis was based on reviewing the number of Vine and non-Vine reviews, as well as the number of stars for each, and the percentages of the 5 star reviews for those Vine and non-Vine reviews. 

Based on the analysis I was able to find that based on a total reviews of ***17,761*** there was ***17,513*** reviews from Vine members and only ***248*** from non-Vine members. 

![image](https://github.com/Loulwa-Alkaisi/Amazon_Vine_Analysis/blob/115623f26eeda232796b8a3a249c2f4e679f418f/Images/picture.png)

Moreover, there was a total of ***5255*** 5-star reviews and ***102*** of then were from non-Vine members while the rest, ***5153***, were all Vine members.

![image](https://github.com/Loulwa-Alkaisi/Amazon_Vine_Analysis/blob/115623f26eeda232796b8a3a249c2f4e679f418f/Images/picture1.png)

Lastly, I was able to display the 5-star review numbers in percentages and I got to the conculsion that 41.13% were paid reviews and 29.42% were unpaid.

![image](https://github.com/Loulwa-Alkaisi/Amazon_Vine_Analysis/blob/115623f26eeda232796b8a3a249c2f4e679f418f/Images/picture2.png)

## ***Summary***
Since the percentage og paid reviews is considerably significantly higher than the unpaid reviews, I think that there could be a positivity bias. Another thing I would analyze to confirm or deny this conculsion is by analyzing the verified purchased column. This would give us a better view of the data.