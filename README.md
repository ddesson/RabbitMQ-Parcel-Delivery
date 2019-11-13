# RabbitMQ-Parcel-Delivery

This is a  RabbitMQ Example Project that creates a Parcel Delivery Broker.
i was working on some tutorials on RabbitMQ and I decided to create my own Project as a learning tool. Initially this Project will use C# but I plan to use other languages such as Python and Java. Also, I can forsee this project to evolve into using various Technologies such as Microservices and the Cloud.

NOTE: This is project exists only as s learning tool; therefore it will not have the the user experience and the reliability one would expect from a Commercial Product.


This Project is an application to determine the best way to send a Parcel. You can send a parcel to anouther City or within the same city.

The user will decide if the delivery is to Maximize speed or to Minimize cost.

Since this Application is a Broker, there will be several Parcel Delivery Companies that will compete, based on delivery time and cost for the delivery of the Parcel between the specified cities. The weight of the Parcel will also be taken into consideration when calculating cost.

There will also have basic Applications to Administer this Application. For example a Parcel Delivery, add or remove Delivery Companies and their supported Deliveries. 

# Design Details
## Data Structures

 Delivery Company Structure for each Source and Destination Cities
 - Company Name
 - Source City
 - Destination City
 - Estimated nymber of days to deliver
 - Cost per Kg of weight
  
Delivery Bid structure used by a Customer to find the best company to deliver their parcel
- Companny Name
- Source City
- Destination City
