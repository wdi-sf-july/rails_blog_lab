# Blog CRUD Lab

For tonight's lab, we'd like you to create a Blog app where a user can create a post, see and update an exiting post and delete a post. The user should also be able to assign tags to each post and for every post they should be able to do full CRUD on the tags as well.

### Objectives

1. Each post should have a name, description and author
2. Each tag should have a name
3. Remember that many blogs can have many tags, and many tags can belong to multiple authors

### How to get started

1. Generate your models and migrations and begin to model your relationships (remember this is a many to many relationship that you should model using has_many through)
2. Run your migrations and make sure you have the correct foreign key setup
3. For each model, make sure everything is working in rails console before you start building your routes, controllers and views (create a post, create a tag, see what posts belong to a certain tag etc.)
4. Once you have tested your models in Rails console, create the routes required for full CRUD 
5. With your routes set up, create your controllers and then your views

If you get stuck with the first two steps, look at the notes from this morning and try those examples to help solidify the concepts. Once you are past step 3, look back at the notes from this afternoon to help you with routing, your controllers and views.

### Bonus

Try to include your own styling, bootstrap or another CSS framework in your application and style your blog.


