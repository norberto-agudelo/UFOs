# UFOs. Module 11
## Overview 
Dana is a data journalist who was born in McMinnville Oregon a city famous for UFOs sightings and for an annual gathering of UFO fans. She has the opportunity to write about her hometown and about UFOs a topic she is interested in since she was a child.

She wants to write an article about it but she wants to support it with some data. She has a Java Script file with UFOs sightings information such as countries, cities, states, type of sighting so she is planning to use Java Script to display the data as a table and put all the data in a HTML page.

However, because there are a lot of information, she wants to allow user, besides to read her article, to filter data for multiple criteria like city, state, country, and shape.
 
To reach this goal, is necessary to explore Java Script (JS)and learn about its use on data visualization by inserting JS code into a HTML code to build a dynamic webpage where users request their information based on some filters. CSS and Bootstrap are tools that is going to be used to build the webpage and to refine the search.

## Results

This webpage allows you to read Dana’s article as well as see some data about sighting around all the world into a table like the one showed below. Although you can see, on the left side of the page, some boxes with filter options, at first, this table shows all the data without any.

![image](https://user-images.githubusercontent.com/107591542/187308436-4f434a64-4ffb-40c9-8289-514c27deecd8.png)

 

The filter option boxes include all the fields on the table but “Duration” field. Text strings into boxes are only user reference information.

 ![image](https://user-images.githubusercontent.com/107591542/187308559-7ca1c5a7-5e3a-48f5-8961-f12fcc69ded7.png)

 
However, you can modify this searching by using some criteria such as date as it is showed below (date 1/1/2010)

 ![image](https://user-images.githubusercontent.com/107591542/187308605-2efd1fbf-992b-44db-93dd-d8ceff9a73da.png)


Then you can refine it by using an additional filter like state (“ca” as an example)

 ![image](https://user-images.githubusercontent.com/107591542/187308783-7f734d6d-abc4-447f-a209-bc3dfbdf58b0.png)


An extra filter could be UFO shape as it is showed bellow (light as a “shape”)

![image](https://user-images.githubusercontent.com/107591542/187308822-43b86e02-d2f9-49be-b70f-14c91303f0f7.png)
 

Finally, you can go until the lowest level (date, state, shape and city) by filtering all these fields with this result. (Country has not been considered in this guide).

 ![image](https://user-images.githubusercontent.com/107591542/187308868-439d7bb7-a8fe-46d9-af1d-0b11bff5ba2d.png)


This way, webpage user could search all the information they are interested in according to their topic of their curiosity or their research area. 

## Summary
 
The main weakness of this design is that you have to refine your searching one field at a time so you can get the result of several filters in only one step. The first time the table is showed it has a lot of data which could be very heavy for this solution.

Further development must consider a searching that includes more than one filter at a time. It could include a button that trigger the searching. Additionally, a “Country” field filter should be considered in order to query data from a specific country.
