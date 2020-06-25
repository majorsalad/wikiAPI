# WikiAPI [Using NodeJS and MongoDB]
WikiAPI is my first RESTful API for encyclopedia articles.

# How it works
- Must have the required node packages installed
- Since this application is an API and not a fully fleshed out web-app, you need to use a 3rd party application such as PostMan for input paths, parameters, and keys.


- If you send a get request to /articles all of the exising articles in the database will be loaded
- If you make a post request to /articles, you enter in an article title and content and it will save your document to the database (remember, this is using Postman to interact with the API)
- Making a delete to /articles will delete all of the existing articles

- Making a get request to /articles/<articleTitle> will display that specific article.
- You can make a put or patch request to /articles/<articleTitle> according to your preference. Both will update the existing article using different methods.
- Similarly you can delete a specific article selecting the delete option on postman and using the path /articles/<articleTitle>


# What I learned
- I learned more about APIs and the purpose they serve as an intermediary between applications. 
- I also learned what it means for something to be RESTful
- Gained more practice working with databases, specifically MongoDB
- Learned how to work my way around deprecated code and deprecated packages

