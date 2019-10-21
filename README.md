# Living Token Network

This project will be a prototype of one of my ideas.

I worked now four years for an software company that is developing an ERP-System. Our software department consists only of 15 programmers. So we are not very big and cause to many older leader, many people are not happy with "crazy" innovations and tests. So I showed them this project as an suggestion for my bachelor-thesis. But sometimes you have bad luck and they rejected my idea.

This is the reason i want to share my idea with the internet, try to implement a prototype of the idea and test it.

### The Idea
In my daily circumstance our software is an client-server architecture that works with the Microsoft IIS. Behind the server that is hosted by the IIS there is one database. These database has an scheme that we develop, but it is important to say that noboy of us is an database-developer and the scheme is developing about 20 years now. So you can think of the mess and problems that been created over time.

One of our largest problem is the performance, there are many clients that request data or manipulate them. Due to the bad ddesign of the database there can be performance issues. Nowadays we try to fix our scheme as good as it can be, without blowing up our whole software.

But on another day i get an idea how to replace the database as the communication base. I want the network of clients be the communication base. And the database is only some form of persisting the changes of the objects. 

These theroy is on the one hand inspired by an object oriented design and on the other by the behavior of the human beeings. In my opinion there is no more intresting way then observe our selfs (evolution) to get an improvement in comupter science.

I want to design an network that consists of objects. But each object exists only one-time in an writable manner. Beside this one "source" objects there is the possibility to create copies of the source-object. This necessary cause not every client wants to manipulate the object. I considered that in an software there is about 80% only readonly request. (Careful that is only my feeling no study, not yet)

### Source Object
The source object differs itself from an copy of the object by the living token, that makes an object "alive". It is like an painting, you can make photos of it as often as you want. But there will be remain only one original painting. And if you modify that paiting all other copies get invalid. Lets stick to this example to show antoher challange with this idea. To take an new copy you have to know where the original object is, to locate it and take your copy. 

### Advantages 
What i expected from this idea is that you reduce the traffic with the database as an frequently used medium. I hope that when each client is communivcate with each other you are able to increase the performance by not requesting every object by the databse. 


In the next time i try to extend this file with my ideas and thoughts. Also i correct my spelling and language in this ReadMe, i just wanted to sum up my idea quickly and now try to work on it.
