# Data Description

We are going to use Foursquare API to get 4 types of venues:

1. Restaurants
2. Hotels
3. Clubs (sport/night) etc
4. Hospitals

Our goal is to use K-means clustering algorithms to find the perfect spots. 
Those spots will be our desired efficient taxi station locations.

# The format
We are going to extract geo coordinates. Use geocoding to find cluster points using Euclidean distance algorithms.
We we'll convert k-means points to geocoordinates for the final results.

# Conditions
Smallest radius should be 5 km (3.1 miles) from each other to avoid having them too close to each other.
