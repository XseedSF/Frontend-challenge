# 🚀 Front end challenge

The purpose of this challenge is to assess your programming skills. 

When your solution is ready, just reply to the email you received with the link to your repo here on Github! We'll then send you feedback and instructions for next steps!

> ⚠️ **It is important that your repo is public, otherwise we will not be able to evaluate your answer**

------------
## 🧠  Context

In this link you'll find the figma with the designs you'll have to follow:

https://www.figma.com/file/dNuO6I2hDGcwoKFA4bjGGh/Challenge?node-id=0%3A1

The challenge is to develop the 3 screens using Star War's public API (https://swapi.dev/)

------------
## 💻 Technologies

 * React js
 * Redux
 * Axios 

------------
## 📱 Screens

1.  ### **Menu**

      You'll need to create a basic hamburger menu, we recommend you to use React Router for the routing.

      The default route should be Characters

2.  ### **Characters**
      In this screen you'll need to render a list with the characters returned  on the /people endpoint showing:
       * Name on first line
       * Gender | birth date
       * Planet (you'll have to make a request to the homeworld returned on the /people endpoint)   
       * A heart icon that will allow the user to add or remove the character as a favorite (save this in Redux)
3.  ### **Favorites**
      * Add a search input to search through saved users in Redux, if there's no search you'll show all the favorites characters.
      * Render a list with the favorites characters saved in Redux, the user needs to be able to remove a character there.

------------


## 📖  API 


https://swapi.dev/api/people

Result:
```
{
    "count": 82,
    "next": "https://swapi.dev/api/people/?page=2",
    "previous": null,
    "results": [
        {
            "name": "Luke Skywalker",
            "height": "172",
            "mass": "77",
            "hair_color": "blond",
            "skin_color": "fair",
            "eye_color": "blue",
            "birth_year": "19BBY",
            "gender": "male",
            "homeworld": "https://swapi.dev/api/planets/1/",
            "films": [
                "https://swapi.dev/api/films/1/",
                "https://swapi.dev/api/films/2/",
                "https://swapi.dev/api/films/3/",
                "https://swapi.dev/api/films/6/"
            ],
            "species": [],
            "vehicles": [
                "https://swapi.dev/api/vehicles/14/",
                "https://swapi.dev/api/vehicles/30/"
            ],
            "starships": [
                "https://swapi.dev/api/starships/12/",
                "https://swapi.dev/api/starships/22/"
            ],
            "created": "2014-12-09T13:50:51.644000Z",
            "edited": "2014-12-20T21:17:56.891000Z",
            "url": "https://swapi.dev/api/people/1/"
        }
    ]
}
```

https://swapi.dev/api/planets/1/

Result:

```
{
    "name": "Tatooine", 
    "rotation_period": "23", 
    "orbital_period": "304", 
    "diameter": "10465", 
    "climate": "arid", 
    "gravity": "1 standard", 
    "terrain": "desert", 
    "surface_water": "1", 
    "population": "200000", 
    "residents": [
        "https://swapi.dev/api/people/1/", 
        "https://swapi.dev/api/people/2/", 
        "https://swapi.dev/api/people/4/", 
        "https://swapi.dev/api/people/6/", 
        "https://swapi.dev/api/people/7/", 
        "https://swapi.dev/api/people/8/", 
        "https://swapi.dev/api/people/9/", 
        "https://swapi.dev/api/people/11/", 
        "https://swapi.dev/api/people/43/", 
        "https://swapi.dev/api/people/62/"
    ], 
    "films": [
        "https://swapi.dev/api/films/1/", 
        "https://swapi.dev/api/films/3/", 
        "https://swapi.dev/api/films/4/", 
        "https://swapi.dev/api/films/5/", 
        "https://swapi.dev/api/films/6/"
    ], 
    "created": "2014-12-09T13:50:49.641000Z", 
    "edited": "2014-12-20T20:58:18.411000Z", 
    "url": "https://swapi.dev/api/planets/1/"
}
```

------------

## ✔️ Evaluation Criteria
- State management
- Componentization
- Responsiveness
- Concern about usability

------------
## 😎 Nice to have
- Commits per component
- Tests

------------

You can use any design library you prefer, we recommend you to use Material UI.