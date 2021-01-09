## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# A Beginner's Guide to Docker

This is a beginner’s guide to Docker which is a way to isolate and run entire applications. With Docker it doesn’t matter if you are using a Mac, Windows, or Linux computer anymore. The entire development environment is isolated: programming language, software packages, databases, and more.

With Docker we now longer have to mess around with virtual environments. We can faithfully reproduce a production environment locally. And Docker can be shared among team members so everyone is working on the same setup. Wins all around.

What’s the downside? Complexity. Docker is a complex beast under the hood. However a little knowledge can take you a long way and that’s the goal of this guide!

# Containers vs Virtual Environments
If you are a Python programmer (like me) a common question at this point is, what about virtual environments? How do they differ from containers?

Virtual environments are used to isolate Python software packages locally. We can create an isolated box for individual projects so one can use Python 2.7 and Django 1.5 while another can use Python 3.5 and Django 2.1 on the same computer. Virtual environments are great.

But…virtual environments can only isolate Python packages. They still rely on a global, system-level installation of Python albeit they can refer to the proper version. So when we use Python 2.7 in a project, we’re pointing to an installation of Python 2.7 on the computer itself, not actually within the virtual environment.

Also we can’t run a production database or other services within virtual environments so compared to Docker containers they are far more limited.

# Install Docker
Ok, enough theory. Let’s start using Docker before we explore further concepts.

To install Docker we need to download the desktop app on our computer and create a free account. The initial download of Docker might take some time to download. It’s a big file. Feel free to stretch your legs at this point!

Once Docker is done installing we can confirm the correct version is running. It should be at least version 19.

$ docker --version
Docker version 19.03.5, build 633a0ea
Docker Compose is an additional tool that is automatically included with Mac and Windows downloads of Docker. However if you are on Linux, you will need to add it manually. You can do this by running the command sudo pip install docker-compose after your Docker installation is complete.

Now run the command below to confirm you have a working version of it, too. The version should be at least 1.24.x.

$ docker-compose --version
docker-compose version 1.24.1, build 4667896b
