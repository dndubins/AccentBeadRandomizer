# AccentBeadRandomizer

My latest hobby is making jewellery, and specifically, beading. But how do you place accent beads along a string to make it look as if they were scattered randomly and haphazardly? You can just arbitrarily add them as you go along, but if you are me - this is a very difficult task. I like a plan, ahead of time.<p>

This Microsoft Excel spreadsheet helps to solve this problem. Specifying a bit of dead space at each end, the Visual Basic macro places a desired number of accent beads randomly along the planned length of a bracelet, anklet, or necklace. A to-scale map is generated with a ruler below. For example, here is the output for a 7" bracelet with 1" dead space at each end, and a minimum distance between beads of 0.2":<p>

Number of Accent Beads:	5	beads<br>
Length of Bracelet:	7	inches<br>
Restricted Space at Ends:	1	inches<br>				
Minimum Distance Between Beads:	0.2	inches (set to 0.1 to allow adjacent accent beads)<p>

```
-------------O---------O----------O--------------O--------O------------	
|----+----|----+----|----+----|----+----|----+----|----+----|----+----|	
0         1         2         3         4         5         6         7
```

The ruler on the bottom is in inches, and the smallest division is 0.1".<p>
Enter the parameters that you would like, and click "Randomize!". If you don't like the pattern that is generated, just click the "Randomize!" button again. Enjoy!
