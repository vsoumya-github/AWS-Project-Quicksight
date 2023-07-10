# Visualize Data with Amazon QuickSight 

# Project Overview

In this mini project, I used two AWS services: Amazon S3 and Amazon QuickSight. 
I also had a dataset provided by Bright Data, which consisted of 50,000 best-selling products on Amazon.com. 
My goal was to store the dataset in an Amazon S3 bucket and then connect it with Amazon QuickSight to create interesting visualizations.

# Steps for the project:

# Step 1: Downloaded and Stored the Dataset in Amazon S3

* I went to AWS Management Console and searched for "S3".
*	I clicked on "Create bucket" to create a new bucket. I named it "soumya-amazon-project" (or any name I preferred).
*	I kept the rest of the settings as default and selected "Create".
*	Then, I clicked on the newly created bucket and uploaded my CSV file (Amazon bestseller dataset).
*	Additionally, I uploaded the "manifest.json" file. I opened the file and replaced the bucket name with my own bucket name.
*	I confirmed that both files were uploaded to the bucket.

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/460de6b6-8b1b-4ce2-bc93-dd316718cab0)

 
# Step 2: Set Up Amazon QuickSight

*	I opened a new tab and searched for "QuickSight" in the AWS Management Console.
*	Since I didn't have a QuickSight account, I signed up for a free trial of the Enterprise Edition.
*	I entered my preferred account name and email address. Then, I selected the S3 bucket I wanted to link to QuickSight and clicked "Finish".
*	I waited for a few minutes while my QuickSight account was created.
*	Once it was ready, I clicked on "Go to Amazon QuickSight" to access the QuickSight interface.

  ![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/cb83e395-eda8-4792-8e27-f33e9794ed45)


# Step 3: Imported the Dataset into QuickSight

*	In the QuickSight interface, I clicked on "Datasets".
*	Then, I clicked on "New dataset" and selected "S3".
*	I switched to the S3 tab and copied the URL of the "manifest.json" object.
*	After going back to QuickSight, I pasted the URL in the appropriate field and provided a name for the data source (e.g., "Amazon data source").
*	I clicked "Connect" and then "Visualize".
* I selected the "Interactive sheet" option and waited for the dataset to finish importing.

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/fe924b0c-0695-48c5-bfcb-ee6cb8b29d06)

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/c1ae3307-f8e7-4a0f-a721-20b60456b0cc)


# Step 4: Created Visualizations in QuickSight

*	I named the sheet as "Most Popular Brands".
*	I dragged the "brand" field into the graph to see the frequency of each brand in the dataset.
*	Then, I clicked on the "brand" field, went to "Sort options", sorted by "brand" in descending order, and applied the changes.
*	QuickSight displayed the most popular brands based on the dataset.
*	I explored other fields and combinations to create different visualizations, such as comparing prices, analyzing top-selling product titles, or identifying sellers with the most products.

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/e3411d8a-fa02-4c5e-a075-aed6cd7573e2)

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/ce43e44b-24ef-4c94-98de-71d16dfbee2e)

![image](https://github.com/vsoumya-github/AWS-project-Quicksight/assets/137465090/f718cf7f-1bc7-451d-8ac2-889589cf537e)


In summary, I have downloaded a large dataset, uploaded it to Amazon S3, and created a visualization dashboard using Amazon QuickSight. QuickSight offered various graph types, including bar charts, donut charts, pie charts, and word clouds. I experimented and got creative with my visualizations.

