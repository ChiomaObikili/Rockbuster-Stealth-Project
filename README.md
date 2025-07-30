<h2>Description</h2>
Rockbuster Stealth LLC is a movie rental company that used to have stores around the world. Facing stiff competition from streaming services such as Netflix and Amazon Prime, the Rockbuster Stealth management team is planning to use its existing movie licenses to launch an online video rental service in order to stay competitive
<h2>Goal</h2>
To help Rockbuster Stealth LLC, a traditional video rental company, transition to an online streaming platform by identifying key customer behaviors and content trends.
<h2>Context & Duration</h2>
This project was completed over 2 weeks as part of a SQL-focused module. Rockbuster faced fierce competition from digital platforms like Netflix and Amazon Prime and needed a data-driven strategy for market re-entry.
<h2>My Role</h2>
Data Analyst – I conducted exploratory and descriptive analysis using SQL and visualized insights with Tableau to guide strategic decisions.

<h2>Data Source</h2>
Dataset was sourced and provided by CareerFoundry
<h2>Tools Used</h2>
PostgreSQL database (via pgAdmin 4)

Tableau for visualization

SQL (CTEs, subqueries, joins, aggregation)

<h2>Steps Taken</h2>
I cleaned the dataset
Queried the database to analyze movie rentals, customer locations, and revenue patterns.
Identified top-performing movies based on rental frequency and revenue.
Mapped customer concentration by region and city.
Visualized customer distribution, top revenue-generating titles, and customer lifetime value.
<h2>Analysis and Result</h2>
To better understand customer preferences and rental performance, I created a column chart to visualize revenue distribution across Rockbuster’s film catalog. The chart quickly revealed standout performers: Telegraph Voyage generated the highest revenue, followed closely by Zorro Ark, Wife Turn, and Innocent Usual. Interestingly, these top films had an average rental duration of just 3 days, indicating strong demand and quick turnover.On the other end of the spectrum, Duffel Apocalypse brought in the lowest revenue. Other underperformers included Oklahoma Jumanji, Texas Watch, and Freedom Cleopatra, each with longer rental durations of 5 to 7 days.This insight suggested a potential trend: shorter rental durations were associated with higher revenue, while longer rentals did not necessarily translate into higher earnings.

  
<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/81effe7a-730d-4836-a50e-be2788592cf6" />      <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/66c7c863-c30a-4913-918e-4917b52e5850" />



To gain insights into Rockbuster’s global customer distribution, I used a map visualization to display customer density by region. The analysis revealed a strong customer presence in high-population areas such as India, China, Japan, the United States, and Mexico—regions that represent key markets for Rockbuster’s services.In contrast, countries like Greenland, Sweden, and Madagascar showed significantly lower customer counts, indicating limited engagement in those regions.


<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/1cd2f100-3b57-473a-b933-0483e9885d68" />


To further break down Rockbuster’s customer base, I created a map visualization highlighting the top 10 cities within the top 10 countries by customer count. This granular view revealed that Aurora and London lead in customer numbers, making them key urban hubs for Rockbuster’s market presence.By focusing on cities within already high-performing countries, the analysis provided a more targeted understanding of where Rockbuster's customers are concentrated. This city-level insight is essential for informing location-specific marketing campaigns and resource allocation.


<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/ab9e6494-41ae-4863-af15-0ac8a489db25" />


The statistical measurements of the films are:

<img width="619" height="264" alt="image" src="https://github.com/user-attachments/assets/1fc9fb41-f2cc-49f0-923a-183ad5c8b730" />


To identify Rockbuster’s most valuable individual customers, I created a map highlighting the top 5 customers by total spending. The analysis showed that Alexander Fennell, based in Bergamo, Italy, ranked highest in overall customer value.This visualization helped spotlight high-value customers who contribute significantly to revenue and could be targeted for premium services or loyalty programs.


<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/572820bc-7388-4cc6-9d09-a4e6b2de6ab2" />



<h2>Insights</h2>
This project helped Rockbuster better understand its customers, movie performance, and global reach. The data showed that a small number of movies, like Telegraph Voyage, bring in most of the money, while many others earn very little. This means Rockbuster can focus on promoting top movies and group less popular ones into bundles to increase their value.

Rental patterns showed that customers usually keep movies for a short time, which could be a good reason to offer more flexible rental options. We also saw that most of Rockbuster’s customers are in a few key countries, and some high-spending customers are located in places like Italy, the U.S., and the U.K.

Sales are stronger in certain countries than others, so it makes sense for Rockbuster to focus marketing and expansion efforts where the company is already doing well or has room to grow.

<h2>Key Success</h2>
I found useful patterns in what customers rent, how long they rent for, and where the most valuable customers are.

<h2>Challenges</h2>
Cleaning up location data and making sure customer records matched across the datasets.

<h2>Lessons Learned</h2>
Using customer and sales data can help make better decisions for pricing, marketing, and content planning.
With these insights, Rockbuster is better prepared to move its business online and compete with today’s digital streaming platforms.





