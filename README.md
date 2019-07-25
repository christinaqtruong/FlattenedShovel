# Flattened Shovel
This web app that lets users view and leave comments on the latest news. It utilizes Mongoose and Cheerio to scrape news from The Onion. Each scraped article is saved to the application database. The Flattened Shovel app scrapes and displays the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article

Users are able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also able to delete comments left on articles. All stored comments are visible to every user.


1. It utilizes the following npm packages and is deployed on Heroku at: 

   1. express

   2. express-handlebars

   3. mongoose

   4. cheerio

   5. axios