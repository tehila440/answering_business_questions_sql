# answering_business_questions_sql

The Chinook database contains information about a fictional digital music shop - kind of like a mini-iTunes store.

The Chinook database contains information about the artists, songs, and albums from the music shop, as well as information on the shop's employees, customers, and the customers purchases. This information is contained in eleven tables. 

The first part of this notebook is from a DataQuest guided project.  The last part of the notebook is exploring the data further, adding visualizations, and practicing alternate techniques.

Task 1 - Pick Three New Albums for Store
The task is to select the top three potential albums for the store based on which genres sell best in USA. THe genres from which to chose are Hip-Hop, Punk, Pop, and Blues.  Out of these four Punk, Pop, and Blues are more popular than Hip-Hop.  The top three genres sold in the US are Rock, Alternative & Punk, and Metal. It would be good to be on the lookout for albums in the Rock genre in the future considering Rock comprises over half of the sales. 


Task 2 - Analyze sales data for customers from each different country. 
For each country, calculate:
* total number of customers
* total value of sales
* average value of sales per customer
* average order value
For countries with one customer, group these into an 'Other' category.
The US, Canada, and Brazil have the highest sales and most customers. However, the country with the highest sales per customer is Czech Republic. Portugal and India also have sales averaging over $90 per customer. Marketing in these countries where the customers spend more could increase revenue. The sample size is too low to confidently expend too much money on marketing in these countries. Creating small campaigns would be a better approach to determine if the trend holds with new customers.

Task 3 - Albums or Individual Tracks
Customers of the Chinook store are able to make purchases in two ways:
* purchase whole album
* purchase individual tracks
The Chinook management is exploring strategies to save money. Management wants to find out what percentage of purchases are individual tracks versus albums to determine if purchasing only popular tracks from albums instead of whole albums will save them money.

Although over 80% of the invoices were not album purchases, there is still a decent amount of customers that purchase whole albums. There is a potential to lose about one fifth of the revenue by only purchasing single tracks from albums.

Task 4 - Which Artist Appears on the Most Playlists
Eugene Ormandy appears in seven playlists. 

Task 5 - Purchased vs Not Purchased
* How many tracks have been purchased and how many have not been purchased?
* Is there a relationship between genre and tracks not purchased?
Out of 3503 tracks 1697 tracks were not purchased. That is just under 50% tracks carried by the store but not purchased.

Over 50% of the tracks sold belong to the Rock genre. The genre with the highest percentage of tracks not sold is Latin, this is also one of the genres with less than 10% tracks sold. 

Actionable Insights:
There are more steps one to take to explore the data further. We could break down the results by country, look at popular albums, media type, price of tracks, etc. 

Conclusion
We explored eleven tables from the fictitious Chinook store. Used SQL to analyze the data, create visualizations, and answered a few questions. The most popular genre is Rock which dominates the majority of the sales in the US and the majority of track sales for all countries who purchase from the store. Album purchases comprise about 20% of the market therefore, it is suggested to continue to offer albums as part of the store's portfolio in lieu of purchasing only popular tracks.