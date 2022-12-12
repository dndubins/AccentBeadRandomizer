# AccentBeadRandomizer

My latest hobby is making jewellery, and specifically, beading. But how do you place accent beads along a string to make it look as if they were scattered randomly and haphazardly? You can just arbitrarily add them as you go along, but if you are me - this is a very difficult task. I like a plan, ahead of time.<p>

The "By Number" Microsoft Excel spreadsheet helps to solve this problem. Specifying a bit of dead space at each end, the Visual Basic macro places a desired number of accent beads randomly along the planned length of a bracelet, anklet, or necklace. A to-scale map is generated with a ruler below. For example, here is the output for a 7" bracelet with 1" dead space at each end, and a minimum distance between beads of 0.2":<p>

  <b>Number of Accent Beads:</b>	6	beads<br>
  <b>Length of Bracelet:</b>	7	inches<br>
  <b>Restricted Space at Ends:</b>	0.5	inches<br>				
  <b>Minimum Distance Between Beads:</b>	0.2	inches (set to 0.1 to allow adjacent accent beads)<p>

```
-----------O------------------O--O-----O----------------O--O-----------
|----+----|----+----|----+----|----+----|----+----|----+----|----+----|	
0         1         2         3         4         5         6         7 inches
```

The precision of the ruler is 0.1".<p>
Enter the parameters that you would like, and click "Randomize!". If you don't like the pattern that is generated, just click the "Randomize!" button again. 

The "By Wandering" spreadsheet starts each accent bead off at its theoretically evenly-spaced location, and then moves the bead along by a random length, resulting in a more evenly-distributed look. For example, here is the output for a 17" necklace with 1" dead space at each end, and a maximum wandering distance of 0.6":<p>

<b>Number of Accent Beads:</b>	16	beads	
<b>Length of Strand:</b>	17	inches	
<b>Restricted Space at Ends:</b>	1	inches	
<b>Max wandering distance:</b>	0.6	inches (<0.44")	

```
----------------------OO---------------O-------O---O---------O-----O----------O---------O-----------OO------------------O---O------O--------------O------------------------
|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|----+----|
0         1         2         3         4         5         6         7         8         9        10        11        12        13        14        15        16        17 inches
```

Enjoy!
