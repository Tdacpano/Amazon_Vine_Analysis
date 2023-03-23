# Amazon_Vine_Analysis
# Overview of the analysis: Explain the purpose of this analysis.
Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Using Pandas determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, you'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

# Results
# How many Vine reviews and non-Vine reviews were there?
  Through filtering the data we were able to retrieve all the rows that include a review that was written as part of a Vine program. There were a total of 94 Vine reviews. 

<img width="432" alt="Screen Shot 2023-03-22 at 5 46 58 PM" src="https://user-images.githubusercontent.com/117120227/227070441-45c0e209-83f4-4489-bb6e-259b7ffa9fc2.png">
<img width="292" alt="Screen Shot 2023-03-22 at 5 47 37 PM" src="https://user-images.githubusercontent.com/117120227/227070514-fe44a4f4-759a-40a6-b0e9-be9dc24c4032.png">

  Additionally, there were a total of 39,915 reviews that were not part of the Vine program. 

<img width="438" alt="Screen Shot 2023-03-22 at 5 49 09 PM" src="https://user-images.githubusercontent.com/117120227/227070695-c5f4a96e-f6f3-46da-ba8a-713cf553925f.png">
<img width="310" alt="Screen Shot 2023-03-22 at 5 49 23 PM" src="https://user-images.githubusercontent.com/117120227/227070723-87edd21e-f5ba-43f3-87bb-05575fa51508.png">

# How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? Along with the percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  
  There were also a 48 paid 5 star reviews, equaling to about 51% of 5 star Vine reviews. 
<img width="370" alt="Screen Shot 2023-03-22 at 5 50 25 PM" src="https://user-images.githubusercontent.com/117120227/227070840-cb80a62d-1a76-4b8e-8007-3647a8fa6210.png">
<img width="312" alt="Screen Shot 2023-03-22 at 5 51 16 PM" src="https://user-images.githubusercontent.com/117120227/227070954-a0e3cafb-e073-42ea-96f2-bb0e5a6c4aba.png">

  There were also a 15,556 unpaid 5 star reviews, equaling to about 38% of 5 star non-Vine reviews. 
  <img width="407" alt="Screen Shot 2023-03-22 at 5 52 28 PM" src="https://user-images.githubusercontent.com/117120227/227071104-610319b0-8a85-468b-9227-b1c65d88235e.png">
  <img width="350" alt="Screen Shot 2023-03-22 at 5 52 54 PM" src="https://user-images.githubusercontent.com/117120227/227071151-4e22ec31-9084-4c6d-85aa-2dddd04560d6.png">



Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
