# comp210-assignment-9--dijkstra-s-algorithm-solved
**TO GET THIS SOLUTION VISIT:** [Comp210 Assignment 9- Dijkstra’s Algorithm Solved](https://mantutor.com/product/comp210-dijkstras-algorithm-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115102&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp210 Assignment 9- Dijkstra\u0026#039;s Algorithm Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Creating Weights

The excel sheet titled roadtrip is what you need to fill in with numbers that you wanna assign each factor.

link: https://docs.google.com/spreadsheets/d/1mB565mYrsWRLblfatBxrCXQe-3W9pQlL9fs46IYI_pE/edit?usp=sharing

*IMPORTANT* In order to create a graph (in Main.java), you must pass in to the contstructor the path for where your csv file is stored. If you pass in the incorrect path you will get a FileNotFoundException.

How to find your file path:

Mac: Locate the file in your finder and right click on it. Hold down the option key and select

‘Copy “roadtrip.csv” as Pathname’. The absolute path of your file is now copied to your clipboard. Windows: Locate the file in your file explorer, shift + right click on file, then select “Copy as path”

The calculateWeight method is where you create your algorithm using 4 factors to produce a single weight for your edge. However, make sure you are not doing any illegal math operations. For example if you divide a number by traffic, make sure you never pass in 0 for traffic since you cannot divide by 0. You can also choose to emphasize certain factors over others. For instance if your car gets really bad gas mileage, you could give distance more weight as opposed to scenery. Also be sure that your weights are positive. Dijkstra’s algorithm does NOT work with negative values.

Once you have completed this part, Write 1 paragraph explaining your reasoning behind your scores for each category, and how your algorithm works. Write this paragraph in the Explanation.txt file provided.

Implementing Dijkstra’s Algorithm

Part 2 of this project is to implement Dijkstra’s algorithm, using a priorty queue. The package minBinHeap contains the code for a Minimum Binary Heap that you will be using for your algorith (do not edit anything in that folder). The Dijkstra method in Graph.java should return a Map with they key being the name of the city, and the value being the total weight that it takes to reach that city from your starting point. Once you are confident your algorithm works, add to your Explanation.txt file an overview of your roadtrip. Give us 1 paragraph explaining what cities you are going to hit between Chapel Hill and LA, the weight of each path you take and what attractions you’re planning to visit on the way (this doesn’t necessarily have to be the ones list below).

Attractions

Chicago – The Bean – Wrigley Field – Deep Dish Pizza!

Nashville – Country Music Capital – Grand Ole Opry – Centennial PArk

Dallas – Six Flags – Dallas Arboretum and Botanical Garden – Sixth Floor Museum at Dealey Plaza (museum about the JFK assassination)

Las Vegas – Las Vegas Strip – Red Rock Canyon – Bellagio Hotel and Casino

Phoenix – Desert Botanical Garden – Camelback Mountain – Papago Park

Denver – Red Rocks Park and Amphitheatre – Great Skiing Resorts – Denver Art Museum

San Francisco – Golden Gate Bridge – Alcatraz Island – Fisherman’s Wharf

Los Angeles – Potential Celebrity Citings – DisneyLand – Santa Monica Pier

Road Information

CH – Nashville: Scenery: Nice, you drive through the Pisgah National Forest Traffic: No traffic

CH – Chicago Scenery: Mostly highway but a nice drive through the West Virginia mountains Traffic: Low

CH – Dallas Scenery: Pretty drive through hills and forests Traffic: Heavy

Vegas – San Francisco Scenery: Goes through Death Valley National Park Traffic: Average traffic

Dallas – Phoenix Scenery: Mostly farms and fields Traffic: Heavy traffic

Dallas – Denver Scenery: Desert scenery, mainly flat Traffic: Moderate traffic

Denver – Chicago Scenery: Midwestern Scenery Traffic: Low

Denver – Nashville Scenery: Most of drive is through forests and open fields Traffic: No traffic

Chicago – Vegas Scenery: Pass through 4 states with changing scenery, from fields to desert Traffic: Medium traffic

Chicago – San Francisco Scenery: Some national forests on the way Traffic: None

Vegas – Phoenix Scenery: Desert scenery Traffic: High

Phoenix – LA Scenery: Desert scenery Traffic: Low traffic

Phoenix – Denver Scenery: Many national forests Traffic: Moderate

LA – San Francisco Scenery: Incredible ocean views on Pacific Coast Highway Traffic: Light
