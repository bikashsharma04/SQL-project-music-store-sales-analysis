# SQL-project-music-store-sales-analysis
This project is about how to analyze the music playlist database. you can examine the database with SQL and help the store understand its business growth by answering business questions. Question set 1 - Easy Q1 Who is the senior-most employee based on the job title? q2 which countries have the most invoices? q3 what are the top 3 values of the total invoice? Q4: Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. Write a query that returns one city that has the highest sum of invoice totals. Return both the city name & sum of all invoice totals. Q5: Who is the best customer? The customer who has spent the most money will be declared the best customer. Write a query that returns the person who has spent the most money.

Question Set 2 - Moderate

Q1: Write a query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A.

Q2: Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the top 10 rock bands. Q3: Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first.

Question Set 3 - Advance Q1: Find how much amount spent by each customer on artists. Write a query to return the customer name, artist name, and total spent

/* Steps to Solve: First, find which artist has earned the most according to the InvoiceLines. Now use this artist to find which customer spent the most on this artist. For this query, you will need to use the Invoice, InvoiceLine, Track, Customer, Album, and Artist tables. Note, this one is tricky because the Total spent in the Invoice table might not be on a single product, so you need to use the InvoiceLine table to find out how many of each product were purchased, and then multiply this by the price for each artist. */

Q2: We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. Write a query that returns each country along with the top Genre. For countries where the maximum number of purchases is shared return all Genres. */

/* Steps to Solve: There are two parts in question- first most popular music genre and second need data at the country level. */

Q3: Write a query that determines the customer that has spent the most on music for each country. Write a query that returns the country along with the top customer and how much they have spent. For countries where the top amount spent is shared, provide all customers who spent this amount. */

/* Steps to Solve: Similar to the above question. There are two parts in question- first, find the most spent on music for each country and second filter the data for respective customers. */

THANK YOU
