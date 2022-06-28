# wiki-API

This is a RESTful API built by using Node.js, Express.js, MongoDB, and Mongoose.

You can make a 'get' request to "/articles" route amd it will return all articles in the database.

'post' request to "/articles" route with 'title' and 'content' values will add that article into databse. 

'delete' request to "/articles" route will delete all articles stored in the database.

-----------------------------------------------------------------------------------------

To make article specific requests, you can use "/articles/{articleTitle}" route. 

'get' request to "/articles/{articleTitle} will return corresponding article.

'put' request to "/articles/{articleTitle} will update article with given values.

'patch' request to "/articles/{articleTitle} will update article's requested fields only.

'delete' request to "/articles/{articleTitle} will delete corresponding article.
