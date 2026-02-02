Name: Kevin Makmur Kurniawan

Student ID: 2802547553

Class: B4AC


Article about FastAPI:

FastAPI is a state-of-the-art web framework for making Python APIs that is lofty for its amazing speed, ease, and convenience. We will go into the domain of FastAPI in this article, taking a gander at its primary elements, establishment method, advantages, and downsides. We'll likewise feature FastAPI's many use cases and proposition best practices for its turn of events. We'll likewise cover as often as possible some information about FastAPI, including its capability, how it varies from Django, and its capability as a backend arrangement.

What are APIs?

Imagine you went to a restaurant with your partner for a dinner date, and you want to place an order. How would you do it? Call the waiter and place an order. Now, what happens at the backend? The waiter goes to the chef and gives the order details. When the dishes are ready, he brings them to you.

Well, you just learned the way APIs typically work. In technical terms, the API is an intermediary between two software components to communicate with each other. API stands for Application Programming Interface. An interface between two entities.

We just learned how APIs work (superficially). So, what does it mean to have an API for a particular service? For example, Accuweather API for weather data. So, think of it as the waiter at our restaurant. What he does is he lets you access the dishes available in that restaurant. Similarly, an API lets the clients access particular resources of the backend or server. With Twitter API, you can pull tweet streams from a hashtag, follow, unfollow people, bookmark tweets, etc.

What Is FastAPI?

FastAPI is a state-of-the-art Python web system made to make it more straightforward to make superior execution APIs.Because of its speed, type hinting support, automatic documentation creation, and asynchronous features, it was developed by Sebastián Ramrez and has grown in popularity. FastAPI is a strong tool for creating reliable APIs with little code since it makes use of Python 3.7+ capabilities, such as type annotations.

Benefits of FastAPI

Advantages of FastAPI
High Performance: FastAPI offers remarkable performance thanks to its asynchronous features and effective request management.
Automatic Documentation: The documentation is generated automatically, which reduces development time and increases API comprehension.
Pythonic: FastAPI's syntax and methodology are understandable to developers who are familiar with Python.
Type Safety: Type hinting makes code more readable and lowers the risk of runtime problems.

Drawbacks of FastAPI

Disadvantages of FastAPI

While FastAPI is user-friendly for beginners, grasping its advanced features could necessitate some learning.
Young Ecosystem: FastAPI's ecosystem is still developing in comparison to more established frameworks like Django.
Limited Project Templates: Compared to certain other frameworks, FastAPI provides fewer project templates and conventions.

Install Requirements
First, We will install all the requirements to run Fast API applications. Like any Python project, we will create a virtual environment where we will install all the dependencies and libraries for the project. The reason for using a virtual environment is Python is not very good at resolving dependency issues. Installing packages to the operating system’s global python environment might conflict with system-relevant packages. So, we create virtual environments.

We can do that by running simple scripts.

python -m venv fastapi
We created a virtual environment named ‘fastapi’ in the current directory. Then we will launch it by typing the following code.

fastapi/Scripts/activate
It will activate our virtual environment. The next step is to install the required libraries.

Install Fast API with pip command. Open up your shell and type in the following code.

python -m pip install fastapi uvicorn[standard]
So, we installed the fastapi and uvicorn server in our virtual environment. We will see what it does in a few moments.