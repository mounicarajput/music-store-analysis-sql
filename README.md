# SQL Project: Music Store Analysis SQL

## Description

This project uses SQL to analyze the dataset of an online music store. The goal of the project is to answer a set of questions about the store's business performance and help in its growth by making better decisions.

## Installation

To run this project on your machine you need to install any SQL-supported DBMS then follow the steps below:
1. Create a database.
2. Create tables using the schema diagram provided below.
3. Import csv files provided in the <a href="https://github.com/avishek09/Music-Store-Analysis/tree/main/dataset">dataset</a> folder.

Note: If you are using PostgreSQL then restore the <a href="https://github.com/avishek09/Music-Store-Analysis/blob/main/music_store_db_backup">backup</a> file of the database and save yourself some time.

## Schema Diagram

![Schema Diagram](https://github.com/avishek09/Music-Store-Analysis/assets/75924699/993e1d5d-0ae0-4034-9e20-202a2916c84c)

<!-- ## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![schema](MusicDatabaseSchema.png)
    ``` -->

## Database and Tools

* Postgre SQL
* PgAdmin4

## Credits

Throughout the development of this project, I have sought inspiration from a pivotal video source: https://youtu.be/VFIuIjswMKM

## License

You can use this dataset to build your own project and practice your SQL skills.

---

## Badges

![postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

## Questions Answered

The following are a few of the questions that are answered in the project (check out <a href="https://github.com/avishek09/Music-Store-Analysis/blob/main/QnA.txt">QnA.txt</a> file for the rest):

* What are the most popular genres of music?
* What are the most popular artists?
* What are the most popular songs?
* What are the average prices of different types of music?
* What are the most popular countries for music purchases?
* Who is the senior most employee based on job title?
* Which countries have the most Invoices?
* What are top 3 values of total invoice?
* Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. Write a 
query that returns one city that has the highest sum of invoice totals. Return both the city name & sum of all invoice totals.
* Who is the best customer? The customer who has spent the most money will be declared the best customer. Write a query that returns the 
person who has spent the most money.
* Write query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically 
by email starting with A
* Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total 
track count of the top 10 rock bands
* Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each 
track. Order by the song length with the longest songs listed first
* Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent.
* We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest 
amount of purchases. Write a query that returns each country along with the top Genre. For countries where the maximum number of 
purchases is shared return all Genres.
* Write a query that determines the customer that has spent the most on music for each country. Write a query that returns the country 
along with the top customer and how much they spent. For countries where the top amount spent is shared, provide all customers who spent 
this amount.

## Results

The results of the project are as follows:

* The most popular genre of music is "Rock".
* The most popular artist is "Queens".
* The most popular song is "War Pigs".
* The average price of an album is $1.
* The most popular country for music purchases is the United States.

## Conclusion

The project was successful in answering the set of questions about the store's business performance. The results of the project can be used by the store to make decisions about its marketing and product offerings.


<!--## How to Contribute

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.-->



<!-- ## Conclusion

The project was successful in answering the set of questions about the store's business performance. The results of the project can be used by the store to make decisions about its marketing and product offerings.


I hope this is helpful! -->
