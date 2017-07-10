# Final exam requirements

The student, on their own, is able to:

 -  Use the command line:
     -  Traversing directories
     -  Moving, copying, creating, deleting files
     -  Passing command line arguments to commands
 -  Use g0it:
     -  Commit, add, push, pull
     -  Resolving a simple merge conflict
     -  Creating a pull request
     -  Review other's code
 -  Follow indentation and coding styleguides in their code
 -  Create variables, instance methods, objects in Java based on a given specification  
   [**ex:** from the RPG Game project](https://github.com/greenfox-academy/seed0forever/blob/master/week-05/RPGgame/src/TileMap.java)  
   [**ex:** from project Reddit](https://github.com/greenfox-academy/seed0forever/tree/master/week-08/day-05/project/reddit/src/main/java/com/greenfox/seed0forever/reddit/model)
 -  Use conditions and loops:
     -  Filtering
     -  Finding elements or index
     -  Generating lists
     -  Checking mutiple values and counting
     -  Maping values
 -  Determine the output of expressions
 -  Explain their own code
 -  Write unit tests for functions and methods
 -  Basic understanding of Gradle build system
 -  Use libraries as dependencies
 -  Include and call 3rd party libraries in their code  
   [**ex:** WeatherChecker build.gradle](https://github.com/greenfox-academy/seed0forever/blob/master/week-06/day-03/workshop/weatherchecker/build.gradle)  
   [**ex:** WeatherChecker service class](https://github.com/greenfox-academy/seed0forever/blob/master/week-06/day-03/workshop/weatherchecker/src/main/java/weatherchecker/datasource/WeatherChecker.java)  
   [**ex:** WeatherChecker instantiating an instance](https://github.com/greenfox-academy/seed0forever/blob/master/week-06/day-03/workshop/weatherchecker/src/main/java/weatherchecker/controller/Controller.java#L29)  
 -  Use databases:
     -  Implement database calls with Java
     -  Write a simple SQL query for a single table:
         -  Listing, Deleting, Updating, Creating rows with specific values
     -  Understand ORM concepts
 -  Understand REST services
     -  create or consume different endpoints
         -  GET, POST, PUT, PATCH, DELETE  
           [**ex:** GET, POST, PUT, DELETE in a RestController](https://github.com/greenfox-academy/seed0forever/blob/bc0197b259402337a65b2500df5f132845342c13/week-08/day-05/project/reddit/src/main/java/com/greenfox/seed0forever/reddit/controller/PostController.java#L28)
     -  handle JSON mapping of body and parameters  
       [**ex:** `@RequestBody`](https://github.com/greenfox-academy/serpentine-tribes-backend/blob/6e08b1fcb50e34fec3539a53639870d5345fccf5/src/main/java/com/greenfox/tribesoflagopus/backend/controller/RegistrationController.java#L41)
     -  handle headers  
       [**ex:** header: `X-tribes-token`](https://github.com/greenfox-academy/serpentine-tribes-backend/blob/2eaabe562da054cc8d1e2f25a004cb5068552729/src/main/java/com/greenfox/tribesoflagopus/backend/controller/TroopController.java#L41)
     -  understand requests and responses
     -  understand API documentation
 -  Either
     -  Spring Backend
         -  write endpoint
         -  test endpoint
         -  complex data structure  
           [**ex:** Location model](https://github.com/greenfox-academy/serpentine-tribes-backend/blob/e27cf2b52ca8a7934674fb39fee4ec3d0b63ab56/src/main/java/com/greenfox/tribesoflagopus/backend/model/entity/Location.java)  
           [**ex:** Kingdom model](https://github.com/greenfox-academy/serpentine-tribes-backend/blob/0230be530eff9b305d40f2f350f08779c68bc245/src/main/java/com/greenfox/tribesoflagopus/backend/model/entity/Kingdom.java)  
         -  heavy usage of Spring components
         -  deploy application to hosting service (with CI)
     - Android Client
         -  write activity / fragment
         -  test activity / fragment
         -  heavy usage of Android components
         -  deploy application apk (with CI)
     - Differentiate between backend and frontend (client) functionality
 -  Refactor code:
     -  Create meaningful names for methods, classes and variables
     -  Split bigger functions to smaller ones
     -  Separate functionalities to different files
     -  Point out code smells  
       (**ex:** very long method bodies, bad naming, code repetition)

## Optional

 -  Use async structures:
     -  Writing functions that are taking and calling callbacks
     -  Determining the calling order in nested callbacks
 -  Authentication:
     -  handle authentication
     -  token based authorization

