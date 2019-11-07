# Coding Assignment for the EAS Web Application Services Team

* There are several frameworks or tools that could be used to complete this assignment.
The primary languages this position requires is javascript and/or python.

* Currently we are using the node and express framework for javascript and our python developers are using Flask and Django.


## Create Web Services.
1 Create a web service that finds a list all the locations and the name of the people at the location.

For instance a path /location  would return json like

    [  
        {
        location : "treehouse",
        people: ["Ron", "Harry", "Hermione"]
        }, {
          location : "hall",
          people: ["Draco", "Crab"]
        }, {
          location : "train station",
          people: ["Hermione", "Draco"]
         }
    ]
  
2 Create a web service that takes a rest style parameter for place id and returns the place name and the
 people at the location.

For instance a path /location/7712  a would return json like

    [
        {
         "location" :  "train station",
         "people" : ["Hermione", "Draco"]
         }
    ]

## Sample Json Data

    people.location.js
    [
        {
            "place": "1123",
            "people": ["1", "2", "3"]
        },
        {
            "place": "5543",
            "people": ["4", "5"]
        },
        {
            "place": "7712",
            "people": ["2", "4"]
        }
    ]

    places.js
    [
        {
            "id": "1123",
            "name": "treehouse"
        },
        {
            "id": "5543",
            "name": "hall"
        },
        {
            "id": "7712",
            "name": "train station"
        }
    ]

    people.js
    [
        {
            "id": "1",
            "name": "Ron"
        },
        {
            "id": "2",
            "name": "Hermione"
        },
        {
            "id": "3",
            "name": "Harry"
        },
        {
            "id": "4",
            "name": "Draco"
        },
        {
            "id": "5",
            "name": "Crab"
        }
    ]
