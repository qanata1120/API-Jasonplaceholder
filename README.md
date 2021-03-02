# API-Jasonplaceholder
Manual API tests performed with Postman



**Base URL** https://jsonplaceholder.typicode.com.


No authorization required to perform API calls.


**API documentations** here https://jsonplaceholder.typicode.com/guide/.


**When to use**

JSONPlaceholder is a free online REST API that you can use whenever you need some fake data. It can be in a README on GitHub, for a demo on CodeSandbox, in code examples on Stack Overflow, ...or simply to test things locally.


**Resources**

JSONPlaceholder comes with a set of 6 common resources:

/posts	100 posts

/comments 500 comments

/albums	100 albums

/photos	5000 photos

/todos	200 todos

/users	10 users

Note: resources have relations. For example: posts have many comments, albums have many photos, ... see guide for the full list.


Routes


**All HTTP methods are supported. You can use http or https for your requests.**


GET	/posts

GET	/posts/1

GET	/posts/1/comments

GET	/comments?postId=1

POST	/posts

PUT	/posts/1

PATCH	/posts/1

DELETE	/posts/1
