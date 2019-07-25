# Flattened Shovel
This web app that lets users view and leave comments on the latest news. It utilizes Mongoose and Cheerio to scrape news from IMDB's list of Top 50 Documentary Movies and TV Shows. Each scraped title is saved to the application database. The Flattened Shovel app scrapes and displays the following information for each article:

     * Headline - the title of the documentary/show

     * Summary - a short summary of the documentary/show

     * URL - the url to the documentary/show's IMDB page

Users are able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also able to delete comments left on articles. All stored comments are visible to every user.


1. It utilizes the following npm packages and is deployed on Heroku at: 
https://flattenedshovel.herokuapp.com/

   1. express

   2. express-handlebars

   3. mongoose

   4. cheerio

   5. axios