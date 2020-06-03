# My-JSON-Data
This repo is being used for testing Dijkstra's Algorithm.
## Raw Map Links (Copy these links for using)
- Map 1 - https://raw.githubusercontent.com/dipamsen/My-JSON-Data/master/map1.json
- Map 2 - https://raw.githubusercontent.com/dipamsen/My-JSON-Data/master/map2.json
- Map 3 - https://raw.githubusercontent.com/dipamsen/My-JSON-Data/master/map3.json
___
## Usage
Currently Compatiable with [Dijkstra's Algorithm Project](https://github.com/dipamsen/Dijkstra-s-algorithm).
Read `README.md` file of that repo.
___
## For Creating own maps
Follow this format for creating your `map.json`.
(Currently only supports 6 cities and 10 roads)
```
{
  "cities":{
    "A":
    "B": ....
  }
  "roads":{
    "A":
    "B": ....
  }
}
```
**Parameter for cities**  
`"x", "y"`      
> Note that these parameters dont affect the calculations at all. It is only cosmetic purpose.  

**Parameters for roads**  
`"c1", "c2", "d"`  
> c1 and c2 i.e. cities should be represented by index number. (cityA --> 0, cityB --> 1, cityC --> 2 .... )
