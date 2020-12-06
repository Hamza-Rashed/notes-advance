## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Scope in python ::
In programming, the scope of a name defines the area of a program in which you can unambiguously access that name, such as variables, functions, objects, and so on. A name will only be visible to and accessible by the code in its scope. Several programming languages take advantage of scope for avoiding name collisions and unpredictable behaviors. Most commonly, you’ll distinguish two general scopes:

    Global scope: The names that you define in this scope are available to all your code.

    Local scope: The names that you define in this scope are only available or visible to the code within the scope.

Scope came about because early programming languages (like BASIC) only had global names. With this kind of name, any part of the program could modify any variable at any time, so maintaining and debugging large programs could become a real nightmare. To work with global names, you’d need to keep all the code in mind at the same time to know what the value of a given name is at any time. This was an important side-effect of not having scopes.

Some languages like Python use scope to avoid this kind of problem. When you use a language that implements scope, there’s no way for you to access all the variables in a program at all locations in that program. In this case, your ability to access a given name will depend on where you’ve defined that name.

Note: You’ll be using the term name to refer to the identifiers of variables, constants, functions, classes, or any other object that can be assigned a name.

The names in your programs will have the scope of the block of code in which you define them. When you can access the value of a given name from someplace in your code, you’ll say that the name is in scope. If you can’t access the name, then you’ll say that the name is out of scope.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/02/Scopes-01.jpg)
