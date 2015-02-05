Uwezo: Preschool choropleth for Kenya, 2013
=======

29 January 2015. For the IHD conference, generating a choropleth map. 

### Main idea

Preschool averages, by girls and boys, for all 47 Kenyan counties in 2013.


### To Do
1. ~~Giant, transparent colored circle following the cursor around?~~ Stupid idea.
2. ~~`ogr2ogr` the Kenya county shapefiles.~~
3. ~~Merge the shapefile county data with the enrolment data.~~
4. ~~Check the GEOjsoning worked.~~
5. Bounded box scale thing.
6. ~~Redo `csv`, aggregate it up to entire population (boys + girls).~~
7. ~~Set the colors (via [Color Brewer](http://colorbrewer2.org/)).~~ 10 colors, going red to green.
8. ~~Apply color fill to counties, based on enrolment rates.~~
9. ~~Add static text labels for each county.~~
10. ~~Style static text.~~
11. Tooltips: boys, girls, average. Note for missing datasets (if `!d.properties[userSelection]`).
12. ~~Drop-downs for gender, age.~~
13. Format the tooltip number (percentage).
14. ~~Style the drop-downs, update button.~~
15. ~~`update` function.~~
16. ~~Enable/disable age drop-down, based on whether `!everyone` is selected.~~
17. ~~Merge all the options of csv to json.~~
18. ~~Transition the colors.~~
19. ~~Add a `reset` button?~~ 
20. ~~Add `title`, and informative `subtitle`. `align right`?~~
21. Color? What do people prefer?
22. Add a color scale/legend.
23. ~~Replace drop-downs with always-on buttons. (BOY, GIRL, 3, 4, 5.) Add these _to_ the `svg`, so no scrolling is needed.~~
24. ~~Add functionality to buttons (via `class`, `.on(click)`, `hover`, etc...).~~ 
25. ~~Style the buttons - prettier, milder colors; design for clarity. Rounded corners? Sleeker?~~
26. ~~Add text to the buttons.~~
27. ~~Awesome-fy the button font.~~
28. ~~Make a new `reset` button (point it to `firstViz()`).~~
29. ~~Error message if `userSubset` or `userAge` (?) is missing.~~
30. ~~Move all the `width`, `height` styles to `<style>` for `buttons`.~~ No.
31. ~~Tiny text label thingie, under the buttons, about what was selected. e.g. `Selected: boys, 3 years`.~~
32. Add `boy` and `girl` averages (over all three years) to `.csv`. 
33. ~~Yellow highlights for selected buttons.~~ Very barely functional. Might remove.
34. Convert `title` to tooltip?
35. ~~`topoJSON`ify the geodata.~~
36. ~~Figure out how to merge `csv` and `topojson` data.~~
  


### Resources

* Tutorial: [Visual.ly - How to make choropleth maps in d3](http://blog.visual.ly/how-to-make-choropleth-maps-in-d3/)
* Tutorial: [Open Health Data Platform - How to//Choropleth map](http://www.cde.org.uk/howto/choropleth-maps/)
* Tutorial: [Safari Books - Building a choropleth map](https://www.safaribooksonline.com/library/view/data-visualization-with/9781782162162/ch12s04.html)
* Tutorial: [Synthesis - Learning D3: Choropleth maps](http://synthesis.sbecker.net/articles/2012/07/18/learning-d3-part-7-choropleth-maps)
* Tutorial: [Visible Dtaa - Responsive legends with d3](https://eyeseast.github.io/visible-data/2013/08/27/responsive-legends-with-d3/)
* Tutorial: [Visible Data - Responsive maps (to resizing)](https://eyeseast.github.io/visible-data/2013/08/26/responsive-d3/)
* Tutorial: [School of Data - How to: Choropleth maps with d3](http://schoolofdata.org/2014/06/06/how-to-choropleth-maps-with-d3/)
* Resource: [LeafLet.js](http://leafletjs.com/reference.html)
* Resource: [Mike Bostock - Choropleth](http://bl.ocks.org/mbostock/4060606)
* Resource: [Mike Bostock - Project to bounding box](http://bl.ocks.org/mbostock/4707858)
* Resource: [Maori Geek - Drawing maps in d3](http://www.maori.geek.nz/post/d3_js_geo_fun)
* Resource: [bl.ocks - Russia choropleth example (to see a color legend)](http://bl.ocks.org/KoGor/5685876)
* Q&A: [StackOverflow - How to make sure border stroke isn't overlapping](https://stackoverflow.com/questions/17917072/choropleth-maps-changing-stroke-color-in-mouseover-shows-overlapping-boundari)


