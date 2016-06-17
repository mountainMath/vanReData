# Questions

# Home much land do Single Detached Homes take up in Vancouver? ([Issue request](https://github.com/mountainMath/vanReData/issues/1))
There are fundamentally two answers to this question, depending on the purpose. One could be interested in how much land
is currently zoned to only allow single family homes to be built on, or one can be interested in how much land is currently
used for single detached homes.

## Single Family Zoned Land
There are several further issues with this question. First we need to decided what zones only allow single family houses.
RS zone first comes to mind, but there are schools and institutional buildings also allowed on RS land. And single family
homes cannot be built on parks, which are also RS zoned. Next is First Shaughnessy. There are also properties that are
not single detached homes in the First Shaughnessy zone, but very few. Next is the question if one should include roads
in the calculation, or just the area of all the property parcels.

It's a bit of a mess, there are lots of choices to be made here. And maybe that explains the range of answers people have
come up with for this question, ranging from [70%](http://www.vancourier.com/opinion/we-need-to-talk-about-nimbys-1.2279173)
or [here](http://news.nationalpost.com/news/canada/radical-proposal-to-fix-vancouvers-real-estate-crisis-build-high-really-really-high) to
[57%](https://www.youtube.com/watch?v=PPAjnEHwBO0) or 
[56% (timestamp 3:50)](http://www.cknw.com/2016/06/02/the-lynda-steele-show-bob-rennie-on-supply-and-demand/).

## Single Family Land Use
The question how much land is used by single family homes is much simpler. It's about 33%. To get this number we need
to merge the Metro Vancouver Land Use dataset with the City of Vancouver Property and Tax Assessment datasets. The Land Use
dataset helps identify single family homes and duplexes and the property and tax dataset allows narrowing it down to
the non-stratified single detached houses. This counts only single family properties, including the 15% that are outside
of current RS zoning, but does not count the roads around them. If one is only interested in single family homes within
RS zoning the number goes down to 28%. If one wants to also throw in single family homes in Shaughnessy we get 29%.