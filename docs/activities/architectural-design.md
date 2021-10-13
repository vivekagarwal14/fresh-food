# Architectural Design
The Architectural Design phase in the first iteration entails an abstract discussion of the basic building blocks for our system. 
The following action items were assigned the highest priority as much of subsequent development hinges on their completion:


## Choose a architecture and why - Monolithic, Service Oriented, Lambda, Microservices,
MVC, 4 plus 1

## Language and Framework choice:
1. Application modality - web or mobile? For universality and ease of access, we have decided to create a web application, rather than mobile. A web application will ensure that we have the widest possible audience reach, and that there are likely to be fewer compatibility issues between various mobile OS releases.
2. In the preliminary stages of development, we have chosen to write our application in Python due to simplicity of syntax, universality of implementation, and prior group coding experience.
3. As the application is going to be web-based, we will be using the Flask web framework. The choice was made due to the vast array of existing Flask libraries that would ease our implementation and facilitate speedy delivery.

## I/O requirements:
1. The user should be able to log in with a simple text box, and their password input should be star-protected.
2. The output of the restaurant selection page should adapt to the screen window size selected by the user (window size agnostic).

## Various components of the system


###  adjust and reformat -
I/O requirements
How various services communicate with each other. ( eg  REST, JSON-RPC)
Choice of Database (eg. RDBMS, Document-based, KeyValue)
Caching layers & their storage - how many level of caching layer -  (eg.  memcached, in memory, redis)
Language Platforms / Framework
