# seinfeld-gram

This is a simple django-based social website similar to the original design of instagram. 

The application includes multiple features, such as:

- a fully functioning authentication system with a custom authentication backend to let users log in using their email address

- social authentication so that users can use their existing Facebook, Twitter, or Google account to log in

- all the necessary views for users to register, log in, log out, edit their password, and reset their password

- a model for custom user profiles and models with many-to-many relationships

- a JavaScript bookmarklet to share images from other websites

- AJAX views with jQuery and AJAX pagination for the image list view

- a follow system using many-to-many relationships with an intermediary model 

- an activity stream using generic relations and optimized QuerySets to retrieve related objects

- a signal receiver function to denormalize related object counts

In addition, the application utilzes the easy-thumbnails library fot the creation of image thumbnails. Lastly, the application utilizes Redis to store item views, and has an image ranking system built with Redis. 

It is populated entirely with Seinfeld characters and pictures.
