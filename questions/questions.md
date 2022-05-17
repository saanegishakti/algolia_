*Question 1*  

 
From: marissa@startup.com  
Subject:  Bad design  

Hello,  
  
Sorry to give you the kind of feedback that I know you do not want to hear, but I really hate the new dashboard design. Clearing and deleting indexes are now several clicks away. I am needing to use these features while iterating, so this is inconvenient.  
   
Thanks,  
Marissa  

--

*Response 1*:



Hi Marissa, 

Thank you for providing your feedback. I believe there isn't a direct method to delete multiple indices at the moment but you can write a script to loop through and delete the indices you want. 

For further instructions, I have attached the document link here: https://www.algolia.com/doc/guides/sending-and-managing-data/manage-your-indices/how-to/delete-multiple-indices/#deleting-one-index

Please let me know if you have any questions. 
Thank you
  
--

*Question 2*:   
  
From: carrie@coffee.com  
Subject: URGENT ISSUE WITH PRODUCTION!!!!  
  
Since today 9:15am we have been seeing a lot of errors on our website. Multiple users have reported that they were unable to publish their feedbacks and that an alert box with "Record is too big, please contact enterprise@algolia.com".  
  
Our website is an imdb like website where users can post reviews of coffee shops online. Along with that we enrich every record with a lot of metadata that is not for search. I am already a paying customer of your service, what else do you need to make your search work?  
  
Please advise on how to fix this. Thanks.   

  
--

*Response 2*:

To: carrie@coffee.com
Subject: URGENT ISSUE WITH PRODUCTION!!!!  

Hi Carrie, 

Thank you for reaching out regards to the error. The error is due to a record beign larger than a threshold. There are two solutions for this problem. First solution would be upgrading your plan to Algolia Recommended, the pricing information can be found here: https://www.algolia.com/pricing/. 
Second solution would be reformat and break your records into smaller ones based on your use case. Reducing record size implementation document can be found in here: https://www.algolia.com/doc/guides/sending-and-managing-data/prepare-your-data/how-to/reducing-object-size/ .

Please let me know if you have any questions. 
Thank you

--
*Question 3*:   


From: marc@hotmail.com  
Subject: Error on website  
  
Hi, my website is not working and here's the error:  
  
![error message](./error.png)  
  
Can you fix it please?  

-----


*Response 3*:

Hi Marc, 

Thank you for reaching out regards to the error. Could you double check if searchkit is part of algolia product? 

Are you using react/elastic searhc? It might have been caused from react/elasticsearch according to quick google search.

Please let me know if you have any questions. 
Thank you
