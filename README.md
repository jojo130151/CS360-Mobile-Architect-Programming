# CS360-Mobile-Architect-Programming
CS-360-H7227 Mobile Architect &amp; Programming 22EW6 for SNHU


- Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The application that I developed was an inventory app that allowed users to insert items into an inventory database to keep track of the items and their quantities. It allowed users to add, delete, and edit the items in thier inventory list. They could also go to a settings page and enable a switch that would let them recieve SMS messages to notify them when an item's quantity was running low.


- What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

I had a total of 6 layout files and 5 screens for the user to navigate. There was the inital login screen, the main page showing the user their inventory, a page to edit an item, a page to add an item and its information, and then a settings page. I chose to have seperate screens rather than a pop up window for the add and edit functions to make room for more information that could be added later. Every button is clearly labeled to indicate what it will do. I will say that incorporating an in app back button rather than relying on the Android's would be better. 


- How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I started with making the layouts how I wanted. I planned what they would look and then played around with accent colors until I settled on a grey/red theme. As for the coding, I started with getting the databases set up how I wanted them. I started with the functions needed for the login process as that was what I needed to work before my inventory database would work. From the layouts, I had already created a majority of the Java files, I just needed to populate them with code functions. Once I had everything set up with the login so that way I could see how the inventory looked and reacted in the emulator, I started trying different strategies to try and get the results needed. I had to go through a lot of steps forwards and backwards to get my program to where it is now. I needed to do more documentation before and during my coding to keep better traack of what worked and what could possibly work.


- How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I incorporated output statements throughout the code to test object variables, that functions were running, and where there might be logic errors occuring. This was helpful, especially with this type of program where the functions run on listeners and activity events. As a programmer, you can't be 100% sure what is beig triggered correctly and what is running. These output statements helped my to see that I was running a class twice because of an activity event. I could also see that some variables were not being populated with what I wanted them to.


- Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

I had to innovate how to have the seperate inventorys for each user dynamically show in a personalized grid for the user. First, each user needed to have their own iventory to show. This was accomplished by using a user associated id to invoke that specific user's inventory. Another challenge was getting an adapter to work correctly so that information could be passed to it and it would populate my gridview with each item in its own grid space. I went through three different adapters to get it working correctly. There is a very specific structure to how these adapters run and the code must adhere to them.


- In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The most successful part of my application is having the personalized inventories showing in a adapter filled grid. The inventory tables being structed with a user id in the function for creating. 
