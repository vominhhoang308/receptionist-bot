## junction2016
#Inspiration
Many companies invest millions to make their buildings more intelligent by adding thousands of sensors. They collect huge amount of data and then can't find way to utilize it. Instead we started from users: building owners, visitors, employees.

#What it does
Platform, that allow to add intelligence to buildings iteratively and controll invesments. It provide visitors enchanced experience with minimal investments. E.g. user come to intelligent building, and he have already app that could connect to that building. App detect and connect to building automatically, based on allowed identity providers (connection part is missing in our project, but diagrams could be found in source code). If building recognize user, it could highlight that he have meetings in 10 minutes, and also notify host employee via chat (slack) channel. Open platform will allow handle cases like (we haven't implemented anything for them):

electronic queues in banks/post, with estimates to wait
register automatically during visit (without scanning id barcode) to hospitals and other systems
detecting new passengers in busses and charging them based on their route

#How we built it
We design platform and implemented few usecases to show that we could plug any data, and use any technologies. We decide to show current temperature in building to user, that is retreived and processed by Java application, another module provide notifications to employee that his guest already in the building.

#Challenges we ran into
We want to make it available to all areas, including development countries. We made it so, that it could work without internet completely (using QR code on wall to initialize connection). But even bigger challenge was to find place for our team. We have moved like 5 times during event! Participated in hunt for table, chairs, and extension cords.

#Built With
java, javascript, d3.js, sprint, gradle, mongodb, ionic, botkit.js