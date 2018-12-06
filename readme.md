# NYC dog weight map

There's a stereotype of New Yorkers having tiny dogs, a consequence of their tiny apartments.  I specifically think of dog walkers in dense neighborhoods bordering Central Park, who seem to have a disproportionate number of poodles, shih tzus, spaniels and various terriers.  While this  _feels_ true, it could be just confirmation bias on my part.

Well, it turns out New York City publishes their [dog registration records](https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp), so this hunch can be tested empirically.  Since the records specify the pet's zip code, you can merge those records with a list of average [dog weights by breeds and gender](http://modernpuppies.com/breedweightchart.aspx).  From there, you can find [NYC shape files by zip code](https://data.cityofnewyork.us/Business/Zip-Code-Boundaries/i8iw-xf4u), making it easy to build a choropleth map of dog weights.

![](https://raw.githubusercontent.com/natesternberg/dog_weights/master/images/map.PNG)

The results didn't turn out quite like I expected. Although the leafy, detached-house regions, like Staten Island, or Breezy Point (the purple western tip of the Rockaway Peninsula), do in fact top the dog-weight charts, the dogs in, for example, the Upper East Side, aren't as tiny as I pictured: 29.3 pounds on average: more Corgi than Yorkie.  This actually puts the Upper East Side in the 64th percentile for NYC dog weight.

But the median NYC dog is only 16 pounds, so where are the Yorkies?  They appear to be concentrated in dense, often low-income neighborhoods.  The lightest-dog zip code is 11239, most of which is Starrett City, a 46-building housing development in East New York, where 60% of the area's 188 dogs are Yorkshire Terriers, Shih Tzus or Chihuahuas.  Similarly, the number two spot is 10475, the home Co-Op City in the Bronx (a 35-building co-op).  Spots 3, 4, and 5 are all in the South Bronx or East Harlem, and all have regions of dense apartments.  So I suppose there's some truth to the small-dog stereotype, just not the way I expected.

