## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Overview :
Django web applications access and manage data through Python objects referred to as models. Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc. The definition of the model is independent of the underlying database — you can choose one of several as part of your project settings. Once you've chosen what database you want to use, you don't need to talk to it directly at all — you just write your model structure and other code, and Django handles all the dirty work of communicating with the database for you.

# Designing the LocalLibrary models
When designing your models it makes sense to have separate models for every "object" (a group of related information). In this case, the obvious objects are books, book instances, and authors.

We might need to store more information about the author than just their name, and there might be multiple authors with the same or similar names. We want to be able to sort information based on book title, author, written language, and category.


![](https://camo.githubusercontent.com/888ad5737b352fb8699d56e37183f9a14c93af5f6c182f1be0e6ebdd3fbb9287/68747470733a2f2f6d646e2e6d6f7a696c6c6164656d6f732e6f72672f66696c65732f31353634352f4c696272617279253230576562736974652532302d2532304d6f6e676f6f73655f457870726573732e706e67)
