#Visualization @ MKThink

brian ho&ensp;//&ensp;works in progress&ensp;//&ensp;summer fellowship 2016

2016.07.18
Note: independent VR; Shahidah - DGG; Jessie+RH1 - 4D. All will be presented soon. instead thought to share behind the scenes: why and how! hopefully get feedback, and  something sticks. Think of these as B-sides, experiments, explorations.


###the Tumblr
![tumblr screengrab](images/tumblr.png)

Find it online at [bit.ly/bho_viz](http://bit.ly/bho_viz)
Note: as an aside, content being kept in a running blog!



<h6>storage</h6>
###How can data make change?
Note: struggled to come up with how to frame. visualization doesn't work: too passive, static, quantitative. I want to  to work between the built environment + data + people. MKthink: architects, data analysts, designers, developers, engineers, planners, strategists (in no order) together. can I make things visual/manifest that unites these disciplines? so some questions.


<h6>map</h6>
###How can strategies and plans become reality?


<h6>business</h6>
###How can architecture expand its scope of practice?


<h6>update</h6>
###How can we design with/for/against the new and the next?


<p><h3 class='fragment'>I don't know.</h3></p>
<p><h3 class='fragment'>Instead, a presentation in three acts ....</h3></p>


<p><h3 class='fragment'>1. Interface</h3></p>
<p><h3 class='fragment'>2. Tool</h3></p>
<p><h3 class='fragment'>3. System</h3></p>
Note: as a framework, I've split this up into 3 parts. each will discuss both the ends and the means to that end.



<h6>devices</h6>
##1. Interface
Note: the front-end.


###User experience design for RoundhouseOne + 4daptive
![UI gif](images/4d ui.gif)

An exercise in imagining an intuitive (as possible) "search" across non-spatial data.
Note: Think of google maps. Define the next "maps."


###Adobe XD
![XD logo](images/xd.jpg)

(N.B. it's currently free)

Note: Great quick prototyping tool for wireframes.


###Horizon chart
![full chart](images/horizon full.png)

Trying to find ways to show lots of time-series data as a meaningful aggregate.
Note: Came out of RH1 work ... I didn't invent the form.


###Horizon chart, closer
![full chart](images/horizon zoom.png)

You can read both the details of individual series, as well as trends across nearby series.
Note: Trends and individuals.


###Horizon chart, even closer
![animation](images/horizon animation.gif)

Preserves the resolution of information, while increasing vertical compression.

There's a [d3.js version](http://bl.ocks.org/mbostock/1483226) waiting to be made ...
Note: Make big data a little smaller.


###Rhino + Grasshopper
<img class='fragment' src='images/rhino.png'></img>
&emsp;&emsp;&emsp;
<img class='fragment' src='images/grasshopper.png'></img>

<p class='fragment'>An imperative/algorithmic visual programming language ... for geometry!</p>
Note: I'm a huge fan!


###What it looks like:
![canvas](images/gh canvas.png)

A mess, basically.
Note: Spaghetti monster.


###What it looks like, closer:
![primitives](images/gh primitives.png)

Data in, data out. Simple! And extensible.
Note: Each component is a little function.



<h6>build</h6>
##2. Tool
Note: making things that help make other things.


###Interactive strategy tool
![strategy resize](images/strategy2d_resize.gif)

Maybe interaction can help a client understand trade-offs?
Note:


###Interactive strategy tool
![strategy red](images/strategy2d_red.gif)

The color changes as the area approaches limits.


###Interactive strategy tool
![strategy 3d](images/strategy2d_3d.gif)

3D, not so good.


###Space planning area tool
![program draw](images/program_draw.gif)

Drawing or editing polyline boundaries adjusts the chart.
Note: (flux)


###Space planning area tool
![program colors](images/program_colors.gif)

Colors are programmatic and can adjust to distinguish categories or sub-categories.
Note: (flux)


###Space planning area tool
![program from Excel](images/program_fromExcel.gif)

Rhino is linked to Excel, so changes to spreadsheet labels or values adjust the chart ...
Note: (flux)


###Space planning area tool
![program to Excel](images/program_toExcel.gif)

... and vice versa.
Note: (flux)


###Flux
<img class='fragment' src='images/flux logo.png'></img>

<img class='fragment' src='images/flux plugins.png'></img>

<p class='fragment'>Puts all your data and geometry in the cloud. Free at [flux.io](flux.io)!</p>



<h6>public</h6>
##3. System
Note: complete assemblies, broader interactions


###DepotGoGo map
![map](images/dgg map.png)

Initial mapping of existing infrastructures.
Note: (galapagos, solving + learning)


###DepotGoGo map, closer
![map](images/dgg map animation.gif)

Layering information.
Note: (galapagos, solving + learning)


###GIS and APIs
<img class='fragment' src='images/gmaps.png'></img>
&emsp;
<img class='fragment' src='images/qgis.png'></img>
&emsp;&emsp;
<img class='fragment' src='images/sfopendata.png'></img>

<p class='fragment'>Pulling GPS coordinates from the Google Places API into Grasshopper + importing GIS shapefiles from [SF OpenData](https://data.sfgov.org).</p>
<p class='fragment'>It's an alphabet soup!</p>
Note: (galapagos, solving + learning)


###DepotGoGo location optimizing
![solver](images/dgg solver.gif)

Evolving a solution, in a full CAD environment.
Note: (galapagos, solving + learning)


###Galapagos
![process](images/process.png)

Survival of the fittest! Diagrams from [David Rutten](http://www.grasshopper3d.com/profiles/blogs/evolutionary-principles).
Note: (galapagos, solving + learning)



##Fin
Thanks for listening! Slides online at [bit.ly/bho_viz_talk](http://bit.ly/bho_viz_talk).
