[SDS page](https://www.superdatascience.com/pages/tableau-advanced) for the datasets

*19/9-xx/yy/19 : Completed to §xLy ("xxx"). ("x of y items complete")*


### §1 Introduction...[DONE]

* [01](https://www.udemy.com/tableau-2018-advanced/learn/lecture/11157778) Welcome to the Tableau Advanced course
* ~[02](https://www.udemy.com/tableau-2018-advanced/learn/lecture/14750398) BONUS: Learning Paths~
* [03]() Some Additional Resources!! ...[*SDS YouTube "[Tableau Custom Charts](https://www.youtube.com/playlist?list=PLE50-dh6JzC450Hn6EjPM238yZUPs-RQ1)" series*]


### §2 Groups and Sets ...[*Done previously in 'Tableau9Advanced' course*]

* [04](https://www.udemy.com/tableau-2018-advanced/learn/lecture/11157784) Section Intro
* ~[05](https://www.udemy.com/tableau-2018-advanced/learn/lecture/12498322) Updates on Udemy Reviews~
* [06](https://www.udemy.com/tableau-2018-advanced/learn/lecture/11157788) Project Brief: 1000 Startups
* [07]() Working with Groups
* [08]() Creating Static Set
* [09]() Creating Dynamic Set
* [10]() Combining Sets
* [11]() Controlling Sets with Parameters
* [12]() Dashboard: The Startup Quadrant
* [13]() Dashboard Tricks ...[*Reference lines, Droplines, Tooltips*]
* [14]() Section Recap


### §3 Advanced Table Calculations ...[*Done in 'T9Adv'*]


### §4 Advanced Data Prep + Analytics in Tableau ...[*Done in 'T9Adv'*]


### §5 Creating Animations in Tableau ...[*Done in 'T9Adv'*]


### §6 Level of Detail Calculations (LOD)

* [50](https://www.udemy.com/tableau-2018-advanced/learn/lecture/11157940) Project Brief: Regional Profit Analysis
* [51](https://www.udemy.com/tableau-2018-advanced/learn/lecture/11157942) Preparing the workbook
* [52](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157944) Aggregation and Granularity (refresher)
* [53](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157946) LOD Calculations Intuition
* [54](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157948) LOD Type 1: INCLUDE ...[*eg. `{INCLUDE [City] : SUM([Profit])}`*]
* [55](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157950) Understanding ATTR() in Tableau ...[*[Definition](https://help.tableau.com/current/pro/desktop/en-us/calculations_calculatedfields_aggregate_create.htm): "Returns the value of the expression if it has a single value for all rows. Otherwise returns an asterisk"*]
* [56](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157952) LOD Type 2: EXCLUDE (Pt1) ...[*eg. `{EXCLUDE [City] : SUM(Profit)}`*] [*And `ATTR()`*]
* [57](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157954) LOD Type 2: EXCLUDE (Pt2) ...[*eg. `ABS(SUM([Profit])/ATTR([LOD EXCLUDE - State Profit]))`*] [*From Q&A: "When an aggregated measure (eg. `SUM([Profit])`) is placed on a shelf or card in the worksheet, its name is changed to (eg) `AGG(SUM([Profit]))`, which indicates that it is an aggregate calculation and cannot be aggregated any further"*]
* [58](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157956) Multiple fields in an LOD Calculation ...[*eg. `{EXCLUDE [City], [Postal Code] : SUM([Profit])}`*] [*"If it doesn't find this Dimension, it'll simply ignore this command to `EXCLUDE` that Dimension"*]
* [59](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157958) LOD Type 3: FIXED ...[*begins with a recap of `INCLUDE`, `EXCLUDE`, `ATTR`*] [`{FIXED [Country], [State], [City] : SUM([Profit])}` ...cf. L54] [`{FIXED [Country], [State] : SUM(Profit)}` ...cf. L56]
* [60](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11157962) Finalizing the Visualization ...[*@1'45 for selection of 'Dual Axis' to combine RHS chart on top of LHS chart*] [**s6 Challenge: [Solution on TableauPublic](https://public.tableau.com/profile/mbeveridge#!/vizhome/SDS_Tableau2018Advanced_s06/Combinedvisualization)**]


### §7 Advanced Mapping Techniques [Jean-Pierre Labuschagne]

* [61](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11191308) Section intro ...[*"We will be focusing on creating ... so everything [in this Section] will be custom made"*]
* [62](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11191314) Getting into shape with Polygons ...[*@2'19 "3 things that we require in order to draw polygons in Tableau" :* **Points** *(x&y coords);* **Direction** *(path or order to connect);* **UniqueIdentifier** *(if multiple shapes. ShapeID)*]
* [63](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/11191318) Background maps
* [64]() Solving business challenge
* [65]() Drawing tool for Tableau
* [66]() Custom images on maps
* [67]() Distance calculations
* [68]() Customizing maps with Mapbox
* [69]() Section Recap
* ~[70](https://www.udemy.com/course/tableau-2018-advanced/learn/lecture/14403768) THANK YOU bonus video~


### §8 Bonus Lectures

* ~[71](https://www.udemy.com/tableau-2018-advanced/learn/lecture/15420306) YOUR SPECIAL BONUS~ ...[*Discount code for "[Data Science A-Z](https://www.udemy.com/datascience/)" course, that I'd already done*]



