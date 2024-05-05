# Web/Api userdata scraper skeleton

This is the scafholding for your web/api scraper, simply add the logic and you will have a nice, fast program with everything needed to start building a scraper. 
This will controll the data, files, cookies, headers and cli interface so you can get right to building without having to worry about QOL functions.

# AccountRoof.py 

Made for services where you know the amount of accounts on a given service (you can figure this number out by signing up to the service) or where you can request content based on uid;
this is my favourite as you dont need to use other methods to find usernames/ID's .

# ScraperUsers.py 

Made for services where you do not know the amount of accounts on a given service / you cannot request user data via ID or the ID is not related to one another i.e: some arbitrary value instead of incremental values.
this assumes you can find usernames by some other means, i.e: scraping the follower/following list .
