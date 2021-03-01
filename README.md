# Webscraping
Web-scraped detailed product information from President's Day Discounts on eBay using Python. 

Save URLs of sponsored and non-sponsored items separately
Create two folders and download pages of sponsored and non-sponsored items
Loop through the pages downloaded in previous step, open and parse them. Then identify and select: seller name, seller score, item price, # items sold, best offer available, title, returns allowed, shipping price, condition (e.g., used, new, like new, seller refurbished, ...).
Save information above into a SQL database
Run summary stats on each item
Summarize the differences between sponsored and non-sponsored items
Conclusion: Sponsored items generally tend to have lower mean seller score, higher mean number of items sold, higher percentage of mean returns allowed, higher mean shipping price, and lower number of listings. Based on the differences above, seller score can be used to predict the sponsor/non-sponsor items, because the difference of that seems the most obvious among all variables.
