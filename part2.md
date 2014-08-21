#Blog CRUD Lab Continued

##Overview
Continue working on the Blog app. We'll be adding additional functionality to have the ability to have comments to each blog post

##Requirements
* Refactor your code to have nested resources so that tags are accessible from posts, and comments are accessible from posts. 

* Make the root page, a list of blog posts, containing time stamp, author name, and blog body, and **number of comments**

* Use bootstrap or some other front end framework to properly style your page. This is a requirement. Add the necessary markup needed to make a complete bootstrap form. Add a `class:"something"` parameter to your rails style form input methods.

**Example URLs**

`/posts/1/tags`

`/posts/1/comments`

`/posts/1/comments/new`


##How to get started
1. Generate a new model `comment` to store information about the posts and information about that `comment`. This can include a field for guest name, comment body, and/or another field

2. Create a new comment form. This can be on the post page it self and `posts/xx/comments/new` 

3. Write all the necessary code to make the `comment` actions update to the parent. Use a parameter in a url to find the parent item, and chain on methods to create a new comment.
