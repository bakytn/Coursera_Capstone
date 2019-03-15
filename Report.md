# Report

## Introduction where you discuss the business problem and who would be interested in this project.
Usually gas cars fueled in varies of places around the city(ies). When it comes to electric cars
the infrastructure is often not ready. Another problem is duration of charging. Unlike gas cars which can be fueled
within a few minutes. Electric cars can take hours to fully charge.

It's important that cars don't travel too much and can be ready anymoment to go and serve the clients.

**Business owners** who are looking to open Taxi stations the most efficient places - can benefit of this study to find best places to have
such stations for faster charging and reaching the clients faster from those stations.

## Data where you describe the data that will be used to solve the problem and the source of the data.
We receive geolocations from Foursquare. We're interested in certain places such as: Restaurants, Hotels, Clubs, Hospitals etc)
as people getting out of those places use taxis most often.

## Methodology
The methodology is to:
1. Normalize data
2. Display objects on the map
3. Cluster them.


K-means algorithm was used as it's the simplest and actually most appropriate
since we are not interested in arbitrary shaped clustering systems.

## Results section where you discuss the results.
We are able to find best spots. Adjustemtns had to be made as it's a real city and it's not possible to simply 
place those stations

## Discussion
This project was only for demonstration of skills for this course and must be treated as such.
Simple eucleudean distance algo was used which is not appropriate when finding distances in geo coordinates.

## Conclusion section where you conclude the report.
New technologies help us using machine learning to solve real world problems. 
