# Week 1

## Assignment

### Reading

#### Code Academy

* Sign up for [Code Academy](https://www.codecademy.com/)
* Complete Units in the Course Academy [Javascript coursework](https://www.codecademy.com/learn/javascript)
  - Introduction to JavaScript (section 1, all)
  - Functions                  (section 2, all)
  - 'For' Loops in JavaScript  (section 3, all)
  - Control flow; if/else      (section 5.1 only)

### Project

#### Task 1: Open Seed Project

The Seed Project is in the `/assignment` directory of the Week 1 repo. Open the `index.html` file. Take a look at the text between the second set of `<script>` tags—this is the Javascript code we will be editing for this assignment.

#### Task 2: Change the marker location to your favorite place to eat food in Philadelphia

The part of the code that adds a marker looks like this: `L.marker([50.5, 30.5]).addTo(map);`. The `50.5, 30.5` part refers to a set of coordinates: latitude and longitude (lat, lng).

In our class, we'll learn a number of ways to find coordinates for a location that we want to map. An easy way to do this for a single address is to use Google Maps. Check out these instructions to [Get the coordinates of a place](https://support.google.com/maps/answer/18539?hl=en).

#### Task 3: Add two more markers

Add two additional markers to your map. These two markers should be two additional places where you like to eat food.

To add an additional marker, copy the code you used to create the first marker onto the next line. Change the coordinates for your new markers. When you are finished, save your file and reload the browser. You should see three markers.

#### Extra

In this class, we are using a Javascript library called [Leaflet](http://leafletjs.com/) to handle mapping in the browser. You can check out the [Leaflet Docs](http://leafletjs.com/reference.html) to get an idea of what it can do.
