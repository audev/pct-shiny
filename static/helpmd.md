---
title: "Help File"
author: "AA"
date: "Wednesday, September 30th, 2015"
output: html_document
---

The tool should be used interactively. By switching between different scenarios,
for example, one can see how the distribution of cycling can be expected to change
as cycling grows. By switching between line types, you can see whether or not
'desire lines' of high demand are supplied with quiet and direct routes.

By experimenting with the 'Freeze lines' option and zooming into specific
areas of interest, the level of cycling at more local levels can be explored.
And by setting the basemap to 'Satellite' when zoomed into specific parts of the
road network, the space available to create new
cycle paths and car-free zones can be explored.

Overall, there are many ways that the tool can be used to improve cycling
provision. It is likely that more features will be added in future versions
(if you have any suggestions, please [get in touch](mailto:npct@npct.org.uk)).
The table below explains the various options in the interactive
map.

<table class="table table-hover table-responsive">

<tbody>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Scenario:</span>  
<ol>
<li> Census 2011 Reported Cycle Commuting </li>
<li> Government Target: this scenario is based on the UK government's proposed target (as set out in its draft <a href="https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/364791/141015_Cycling_Delivery_Plan.pdf" target="_blank">Cycling Delivery Plan</a>) to double cycling in England. Taking population increases and trip rate decreases into account, the target implies doubling the proportion of trips made by cycling nationwide. Trips that have a large distances or that already have a high rate of cycling will see cycling increase less than two-fold; trips with a below average current rate of cycling but high potential (based on the distance) will see cycling increase more than two-fold. </li>
<li> Gender equality: Women have the same cycling rate as men </li>
<li> Go Dutch: Cycling propensity at the levels seen in the Netherlands </li>
<li> Electric bicycles: Willingness to cycle longer trips increases with widespread use of electric bicycles </li>
</ol>
</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 314px; height: 180px;" alt="Scenario Selection"
src="./assets/help/scenario-selection.png"><br>
</td>


<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Zone Attribute</span>  
<ol>
<li> Scenario Level of Cycling is the model predicted rate of cycling in the given area for the chosen scenario  </li>

<li> Scenario Increase in Cycling is the corresponding number of additional cycle commuters over and above Census 2011 </li>

<li> None: No zone attribute is displayed  </li>
</ol>

</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 177px; height: 285px;" alt="Zone Attribute"
src="./assets/help/zone-attribute.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Cycling Flows</span>  
<ol>
<li> Straight Lines between the population weighted centroids of Census Medium Super Output Areas  </li>

<li> 'Fastest' Route using <a href="http://www.cyclestreets.net/journey/help/howitworks/" target="_blank">Cycle Streets Routing</a></li>

<li> 'Fastest' and 'Quietest' Routes using Cycle Streets Routing </li>
</ol>
</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 326px; height: 197px;" alt="Cycling Flows"
src="./assets/help/cycling-flows.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Freeze Lines</span>  

<ol>
<li> Ticked: The top cycling flows shown remain those calculated based on the visible map area when the box was ticked  </li>

<li> Unticked: If the visible map area changes, flows are recalculated accordingly </li>
</ol>

</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 283px; height: 44px;" alt="Fixed Lines"
src="./assets/help/freeze-lines.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Line Attribute</span>

<ol>
<li> Scenario Level of Cycling is the model predicted rate of cycling between an origin destination pair for the chosen scenario </li>
<li> Scenario Increase in Cycling is the corresponding number of additional cycle commuters that can be expected between the origin destination pair </li>
</ol>
</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 179px; height: 257px;" alt="Line Attribute"
src="./assets/help/line-attribute.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Flows to Show</span>  
When viewing flows, this slider selects how many of the of the top 50 are shown</td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 381px; height: 127px;" alt="Number of Lines to Show"
src="./assets/help/number-of-lines.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top; width: 1054px;"><span style="font-weight: bold; text-decoration: underline;">Fastest Route</span> The purple line represents the 'Fastest' cycling route calculated by CycleStreets between the population weighted centroid of two zones. Once selected the following information is displayed:

<ol>
<li> Total commutes 2011: The total number of commuting trips between these two zones </li>
<li> Cycling 2011: Reported cycle commutes between these two zones </li>
<li> Scenario Cycling: The model predicted rate of cycling between an origin destination pair for the chosen scenario </li>
<li> Scenario Increase: The difference between the Census 2011 Cycling and the Scenario  </li>
<li> Route Distance: The route distance in km between the centre of the zones</li>
</ol>

<span style="font-weight: bold; text-decoration: underline;"></span></td>

<td style="vertical-align: top; width: 535px;">
<img style="width: 416px; height: 227px;" alt="Direct Route"
src="./assets/help/direct-route.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top;"><span style="font-weight: bold; text-decoration: underline;">Quiet Route</span> The light blue line represents the 'Quitest' cycling route calculated by CycleStreets between the population weighted centroid of two zones. Once selected the following information is displayed:

<ol>
<li> Total commutes 2011: The total number of commuting trips between these two zones </li>
<li> Cycling 2011: Reported cycle commutes between these two zones </li>
<li> Scenario Cycling: The model predicted rate of cycling between an origin destination pair for the chosen scenario</li>
<li> Scenario Increase: The difference between the Census 2011 Cycling and the Scenario</li>
<li> Route Distance: The route distance in km between the centre of the zones</li>
</ol>
</td>

<td style="vertical-align: top;">
<img style="width: 418px; height: 249px;" alt="Quiet Route"
src="./assets/help/quiet-route.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top;"><span style="font-weight: bold; text-decoration: underline;">Straight Lines</span> The red line represents a straight line between the population weighted centroid of two zones. Once selected the following information is displayed:

<ol>
<li> Total commutes 2011: The total number of commuting trips between these two zones</li> 
<li> Cycling 2011: Reported cycle commutes between these two zones</li> 
<li> Scenario Cycling: The model predicted rate of cycling between an origin destination pair for the chosen scenario</li> 
<li> Scenario Increase: The difference between the Census 2011 Cycling and the Scenario</li> 
<li> Route Distance: The route distance in km between the centre of the zones</li> 
</ol>

</td>

<td style="vertical-align: top;"><img style="width: 415px; height: 313px;" alt="Straight Line" src="./assets/help/straight-line-popup.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top;"><span style="font-weight: bold; text-decoration: underline;">Zone Information</span> Zone information is displayed on clicking on the black circle in the centre of each zone:

<ol>
<li> Zone: Zone name according to the Census</li> 
<li> Scenario Level of Cycling: the model predicted rate of cycling in the given area for the chosen scenario</li> 
<li> Scenario Increase in Cycling: the corresponding number of additional cycle commuters over and above Census 2011</li> 
<li> Hilliness: Shows the average hilliness of the zone from <a href="http://srtm.csi.cgiar.org/" target="_blank">digital elevation model</a> data supplied by NASA.</li> 
</ol>

</td>

<td style="vertical-align: top;">
<img style="width: 415px; height: 195px;" alt="Zone"
src="./assets/help/zone-popup.png"><br>
</td>

</tr>

<tr>

<td style="vertical-align: top;"><span style="font-weight: bold; text-decoration: underline;">Zone Attribute Legend</span> The legend shows quartiles for the displayed zone attribute according to the scenario selected.</td>

<td style="vertical-align: top;">
<img style="width: 279px; height: 340px;" alt="Legend" src="./assets/help/legend.png">
</td>

</tr>

</tr>

</tbody>

</table>
