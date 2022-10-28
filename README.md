# Crowdfunding-ETL
 
## Analysis 
the purpose of this challenge including Module 8 was for us to have a better understanding on how to use data modeling and analsis through the concepts of Extracting, Transforming, and Loading processes or ETL for short. For the challenge used Python dictionary methods to extract the data in Deliverable 1. We extracted the dated from the backer_info.csv file. After pulling the data form the csv file, we then converted the rows in the file to a dictionary in order to get values in each row. Then we created a new dataframe with new columns for the backer_info data. Then we created a new csv file after the extraction with the new columns. I named each backer's file differntly so I didn't get confused. The second option we did to extract the data was through the regex method. Throught this method we were able to created columns next to the original date and extract the date into the new columns. After that was done we drop the column of the original data to make it more clean. We made sure it was correct because it should match the same dataframe as in option 1. This is what the dataframe is supposed to look like.

![image](https://user-images.githubusercontent.com/111409181/198515559-e25170f7-c39c-4ac9-a7ee-7b03682f1e4b.png)

In Deliverable 2 we transformed the dataframe we created in deliverable 1 and cleaned it to make it look nice. We check the data types then switched the type on cf_id into an int64. One way we made the date more clean was to seperate the name column into two different columns with 'first name' and 'last name'. That data set looked liek this 

![image](https://user-images.githubusercontent.com/111409181/198516793-936c15d7-9141-4fe2-8b70-12ef5b0629ce.png)
We then proceeded to save that into a csv file. 
For Deliverable 3 I transported the clean data into pgAdmin to create a table for backers to add it with the other tables we created earlier for the module 8. after adding the contraints, creating the tables and assigning the primary and foreign keys we imported the data into their tables. I got stuck on this a while becuase my csv files were not getting imported into the file. At the end of the module they had csv files of what campaign, category, subcateogry, and contacts supposed to look like. Wehn I compared to how my csv files looked like I noticed the my csv files added an extra column numbering off each row twice. Same thing happened on my backer.csv files. After removing that extra column I was finally able to import the csvs into a database table. This was the result of the backers database table. I will also show a pic of what backer_re_df.csv looked like(I left the extra column on this one to show on the readme). From the pic of backer_re_df.csv it showed that Column A was numbered like the rows

![image](https://user-images.githubusercontent.com/111409181/198521081-a8201bdc-b697-4c0a-b292-6cdb77fb62da.png)

![image](https://user-images.githubusercontent.com/111409181/198521358-3e68eff0-80dd-4fe9-a0b1-3e5b03f909a2.png)


All in all this was a pretty neat challenge to do and understand how ETL process worked and then how to import them into a database table. 
