
The approach used in the cloud section included the following steps:  
1. Choosing a cloud platform like Amazon Web Services (AWS), Google Cloud Platform (GCP), and Microsoft Azure. 
2. Create a virtual machine (VM on a cloud platform with the necessary specifications like memory, cpu, and storage to run my python code.  
3. Install python and necessary libraries like scrapy, pandas, json, and requests on the VM to fetch items from edge.com.   
4. Write code to fetch articles from threverge.com using the libraries installed in the previous step. The code should extract the article title, author, and publication date from the html code of the website.  
5. Save the extracted data (article headline, author, and publication date) to a database or cloud storage service such as Amazon S3 or Google Cloud Storage. This will allow me to easily access the data and analyze it later.   
6. Use a scheduler such as cron or a cloud service such as AWS Lambda to schedule the analyzer to run periodically and fetch new items as you go. and as they are published on theverge.com.   
7. Monitor VMs and scrapers to make sure they are working properly and there are no issues with your code. You may want to configure alerts to notify you if there is a problem with the virtual machine or if the data extraction process fails.
