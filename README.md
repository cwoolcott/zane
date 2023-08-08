# Book-Search-Engine

## About The Application

This application was already in working order using a RESTful API, and the activity was to change around the code to make it use the GraphQL API using the Apollo Server!

The application in general is a handy little tool to help you search for books and allowing you to save them for future reference! (Such as if you wanted to build a digital library of books you own or books you want to check out some time!)

When you search for a book, you will be met with 10 results that all tell you the;

* Book Title

* The Author(s)

* The cover image of the Book

* The Book Description

It is a pretty neat tool that definitely has some good use for those that enjoy reading!

## Issues

I ran into a few issues when building this, some were solved, some unfortunately remain!

* One of the biggest issues I ran into (and even in this entire class) was the pre-built code (that was supposed to work out of the gate) had some errors in it that would not allow me to even view its vanilla version. I spent time with our TA trying to debug it, to no avail, and so I consulted a tutor, after the entire hour spent trying to debug, we finally found that some issue was going on with the react-bootstrap elements. So instead of writing it as Form, Button etc, I rewrote it as a standard form and that fixed the issue! Roughly 2-3 hours of time went into debugging it so I could officially start the homework.

* A similar issue with the base code was that it just would not connect to the MongoDB, doing some debugging of my own, I found that in the connection, I just  had to change localhost to the proper Mongo connection string. Definitely another annoyance though!

* An issue that currently persists is that the app will not deploy to Heroku properly, I am not sure why, I followed the instructions to the T on how to do so, yet it remains broken. I think I am going to reach out to a tutor again and ask for some help debugging that portion.

* On that note too, for some reason with all the changes, now when you sign up, if you log out and try to log in again, it doesn't work, so quite a bit of debugging in my future.

* Have I mentioned how much I love debugging? Only sometimes, this is not one of them. I encountered another issue where the saveBook mutation isn't working properly, so I'll edit this issue once that is resolved.

## Screenshots

Below I will include some screenshots of the application!

![Book-Search-Engine](./Assets/Screenshot%201.png)
![Book-Search-Engine](./Assets/Screenshot%202.png)


## Conclusion

In conclusion, I'm not going to lie, I really disliked this project haha! Something about going in and editing the code to use something else was just a pain in the butt, I think it would of been more helpful with some todo comments in there or something, just a way to help the process be less messy! I understand we are supposed to use our resources, but I feel even with those, this entire project just felt so clunky and could of been a better experience! Who knows, maybe after all the debugging I will like it better, but we'll see about that one!

## The Link

Below is the link that will take you to the repository of this application!

https://github.com/Bidoofs-Dad/Book-Search-Engine

And here is a link to the Heroku link! (currently broken 😞 )

[GoSearchABook!](https://gosearchabook-f72cd92df0f6.herokuapp.com/)