<h1>Problem Statment</h1>
<div>
Consider a use case like Facebook/Linkedin posts where on average, every 1 min, 5
posts are created, Designing the database schema and the following REST APIs on
the following factors:-
  <div><br>
a. Create a post<br>
i. The post should have a title and content<br>
a. Fetch all posts on the following basis:<br><br>
b. Recency<br>
i. The latest new post should always come one top<br>
ii. The number of posts to be fetched can be changed and the
API should accordingly return those number of posts. For
example 10 posts, 20 posts<br><br>
c. The pagination for fetching those posts supports the use case of
infinite scrolling and not Page number-based pagination.<br>
d. There should be no duplication in the results from the API when
fetching the posts<br>
</div>
</div>
# ContentPostingAppBackend
Facebook/ LinkedIn kind of app for content posting

Application Deployed on Heroku Cloud

Click on the link below to check out the application.<br>
https://content-posting-app.herokuapp.com/

<h3 href="https://documenter.getpostman.com/view/11673082/UVkvHXu3">Postman API Document</h3>

POST API - Create POST

![image](https://user-images.githubusercontent.com/66467860/156801682-894c86b2-cbdd-42a2-8b5c-b0d63688ed58.png)

GET API - To fetch all post which will display on feed. 

![image](https://user-images.githubusercontent.com/66467860/156802146-15be8bd2-3e86-4139-91c2-672effea8375.png)


Note: In GET API pass the query.

Created a basic EJS front end for testing
![image](https://user-images.githubusercontent.com/66467860/156802965-919c8451-7543-4150-b924-629a2fb6b429.png)

ThankYou!

