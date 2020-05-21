# Web-Scraping on eBay
Web-scraped detailed product information from 1000 listings on eBay using Python with keyword "playstation 4 slim". 
Steps:
1. Save URLs of sponsored and non-sponsored items separately
2. Create two folders and download pages of sponsored and non-sponsored items
3. Loop through the pages downloaded in previous step, open and parse them. Then identify and select: seller name, seller score, item price, # items sold, best offer available, title, returns allowed, shipping price, condition (e.g., used, new, like new, seller refurbished, ...).
4. Save information above into a SQL database
5. Run summary stats on each item
6. Summarize the differences between sponsored and non-sponsored items  
Conclusion: Sponsored items generally tend to have lower mean seller score, higher mean number of items sold, higher percentage of mean returns allowed, higher mean shipping price, and lower number of listings.
Based on the differences above, seller score can be used to predict the sponsor/non-sponsor items, because the difference of that seems the most obvious among all variables.
