
# Forms : 

An HTML form is a set of one or more user interface elements / fields on a web page, which can be used to collect information from users and send it to the server. Forms are a flexible mechanism for collecting user input because there are user interface elements suitable for entering many different types of data, including text boxes, check boxes, option buttons, date picker, and so on. Forms are also a relatively secure way to share data with the server as they allow us to send data in POST requests with cross-site request forgery protection.

* The form is defined in HTML as a collection of elements inside form tags, containing at least one input element of type="submit".

* The form attributes define the HTTP method used to send the data and the destination of the data on the server (action):

* action: The resource/URL where data is to be sent for processing when the form is submitted. If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.
### method:
* The HTTP method used to send the data: post or get.
* The POST method should always be used if the data is going to result in a change to the server's database because this can be made more resistant to cross-site forgery request attacks.
* The GET method should only be used for forms that don't change user data (e.g. a search form). It is recommended for when you want to be able to bookmark or share the URL.

# Steps to make a form:

* Declare a Form (model)
* Decide the fields and their data types
* Validate the data entered into form fields
