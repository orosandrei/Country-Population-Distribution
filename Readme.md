# Country Population Distribution

Code that generates the population distribution map for a specified country and outputs it as an image:


```
GeoGraphics[{CountryData["Romania"],Opacity[0.042, Red],Disk[Reverse[CityData[#, "Coordinates"]],Log[10.^18, QuantityMagnitude[CityData[#, "Population"]]]] & /@ CityData[{All, "Romania"}]}]
```

The sample is written with **[Wolfram Language](http://www.wolfram.com/language)**, a very powerfull symbolic language with built-in algorithms and knowledge base.


![Alt text](https://github.com/orosandrei/Country-Population-Distribution/raw/master/Screenshot.png?raw=true "Wolfram Language - Population Distribution of a Country")


## Links

 * [Wolfram Programming Cloud](http://www.wolfram.com/programming-cloud)
 * [Stephen Wolfram - Blog](http://blog.stephenwolfram.com) 
 * [Frontiers of Computational Thinking: A SXSW Report](http://blog.stephenwolfram.com/2015/03/frontiers-of-computational-thinking-a-sxsw-report) 
