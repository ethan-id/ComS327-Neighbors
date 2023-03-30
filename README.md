
# ComS327-Neighbors
### Author:
Ethan Hancock, ehancock@iastate.edu
### TA Notes: 
> For some reason, travelling east/to the right breaks things, but travelling north, south, and west all work fine, despite identical code. Assuming some minor memory mismanagement issue is the cause but couldn't come up with a solution in time.
> Trainer locations also aren't maintained between maps.

### Description:
#### Major Changes:
 - Ported all code to C++

#### Methods Added
 - No new methods
    - Most change were refactors to old methods.
    - generateTrainers() had a lot of new additions
        - new case in user's turn of switch case statement to handle flying
    - new while loop in main() method to generate or redisplay maps as the user travels around the world.
    - Lots of new properties on the terrainMap class/struct
