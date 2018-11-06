# Project-3--Prolog
This is Prolog Project 3

### Quick Start 
**Make sure you have an apporpriate IDE that implements Prolog. For example,GNU-Prolog
````bash 
# Learn Prolog using provided links
# Get proper materials through canvas 
````
# Table of Contents 

* [Description](#description)
* [API](#api)

___

## Description

 A Prolog program that  tells  us  how  to  get  from  one room of a one-story building, to any other room in that building (if it’s possible), by telling us all of the rooms we must go through to get to the destination room. There will be phones ringing in one or more of the rooms. It only tell us how to get to those rooms. If we attempt to go to a room that does not have a ringing phone, the program does not produce any output.
 
 My computer refused to download the suggested IDEs for this project, not matter what I tried. I looked up other suggested platforms I could code from and I got TextMate. I am unsure how sufficient it will be on the others. 
___

## API

___

#### room(X)

Creates 16 rooms to represent each of the rooms in the diagram. 
___

#### door(X,Y)

Creates the doors that connect each rooms. 

___

#### phone(X) 

Creates the 3 rooms which have phones in them. 

___

#### next_to(Room1,Room2)

Returns yes if the rooms are next to eachother. 

___

#### move_forward(Start,End,A,B)

Moves forward to the room next to it. 

___

#### reverse([A|B],X,Path)

Reverses order of the path.

___

#### path(Start,End,A)

Finds the path from one room to another. 

___

#### return(Start,End)

Finds all paths from start to end. 

___

#### path_to_phone(Start,End)

four different scenarios: when both start and end are given, only start or end is given, and when nothing is given. All give the path to a phone. 

#### License 
  [Auburn University](/LICENSE)
  
___

#### Author
  [Amy Benton](/LICENSE)
