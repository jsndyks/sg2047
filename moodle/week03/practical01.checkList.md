### Tableau Tutorial - Getting Started with Tableau

<!--link rel="stylesheet" href="https://staff.city.ac.uk/~jad7/epm948/epm948.css"-->
<link rel="stylesheet" href="https://jsndyks.github.io/sg2047/css/sg2047.css">

<style type="text/css">
  blockquote {margin:0.5em; margin-left:2em; padding:0.5em; padding-left:2em;
    background-color:#f0f0f0; border-left:solid #d0d0d0 2px; }
  ul {margin:0.5em; margin-left:2em; padding:0.5em; padding-left:2em;}
  .task-list-item-checkbox {
  background-color: #f00; color:#0f0;
  cursor: default;
  appearance: checkbox;
  box-sizing: border-box;
  }
  .task-list-item-checkbox {
  background-color: #f00; color:#0f0;
  cursor: default;
  appearance: checkbox;
  box-sizing: border-box;
  }

</style>

#### Checklist of Concepts

Having watched the video and worked through the examples you should **understand** the following concepts and **be able to use them** in Tableau Desktop.

We'd like you to make a copy of this list and cross each item off as you have addressed it.

These are all **essential concepts** that you will need to be able to use in _Tableau Desktop_ to succeed in the module.

Once you have tried them out by following the video, check the box or cross it off!

<style>
    .checkList {padding-left:4em; padding:2em;}
    .checkItem {padding:0.5em;}
    .checkNum  {font-weight:bold; font-size:140%}
</style>

<div class="checkList" markdown="1">

<div class="checkItem" markdown="1"><span class="checkNum">1.</span>
<input type="checkbox" id="to1"><label markdown="1" for="to1">
&nbsp;&nbsp; load an **Excel** file into Tableau - to 'connect' a data set
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">2.</span>
<input type="checkbox" id="to2"><label markdown="1" for="to2">
&nbsp;&nbsp; **extract** the data - know the difference between _live_ and _extract_
<br/></label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _(we will normally want to extract)_ <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">3.</span>
<input type="checkbox" id="to3"><label markdown="1" for="to3">
&nbsp;&nbsp; know and understand the difference between **dimensions** and **measures**
<br/></label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - **measures** - **green** pills - these are _quantities_, numbers
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - **dimensions** - **blue** pills - these are _qualities_, categories (usually names) <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">4.</span>
<input type="checkbox" id="to4"><label markdown="1" for="to4">
&nbsp;&nbsp; create a **hierarchy** of dimensions (categories)
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">5.</span>
<input type="checkbox" id="to5"><label markdown="1" for="to5">
&nbsp;&nbsp; **hide** dimensions and measures
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">6.</span>
<input type="checkbox" id="to6"><label markdown="1" for="to6">
&nbsp;&nbsp; **build** visualizations in the _sheet_ by dragging dimensions and measure fields to the _shelves_ and _cards_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">7.</span>
<input type="checkbox" id="to7"><label markdown="1" for="to7">
&nbsp;&nbsp; **calculate** _new variables (measures) - a _calculated field_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">8.</span>
<input type="checkbox" id="to8"><label markdown="1" for="to8">
&nbsp;&nbsp; use the **back** or **undo** button
<br/></label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _to get back to where you were - before you messed things up!_ <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">9.</span>
<input type="checkbox" id="to9"><label markdown="1" for="to9">
&nbsp;&nbsp; use **SAVE** to save a _TWBX workbook_ (a Tableau workbook with data)
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">10.</span>
<input type="checkbox" id="to10"><label markdown="1" for="to10">
&nbsp;&nbsp; use '**Show Me**' to select possible chart types
<br/></label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _this is the **one click option**, not a comprehensive list of possibilities_ <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">11.</span>
<input type="checkbox" id="to11"><label markdown="1" for="to11">
&nbsp;&nbsp; select a **colour scheme**
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">12.</span>
<input type="checkbox" id="to12"><label markdown="1" for="to12">
&nbsp;&nbsp; **change** the end and centre points of a _diverging colour scheme_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">13.</span>
<input type="checkbox" id="to13"><label markdown="1" for="to13">
&nbsp;&nbsp; show and use a **filter** to select relevant data items _interactively_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">14.</span>
<input type="checkbox" id="to14"><label markdown="1" for="to14">
&nbsp;&nbsp; use the **row** and **column** shelves to split the screen and structure a graphic
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">15.</span>
<input type="checkbox" id="to15"><label markdown="1" for="to15">
&nbsp;&nbsp; use the **marks shelf** to vary a graphic
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">16.</span>
<input type="checkbox" id="to16"><label markdown="1" for="to16">
&nbsp;&nbsp; know the difference between **discrete** and **continuous** fields
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">17.</span>
<input type="checkbox" id="to17"><label markdown="1" for="to17">
&nbsp;&nbsp; understand how Tableau uses **dates** (date parts and date values)
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">18.</span>
<input type="checkbox" id="to18"><label markdown="1" for="to18">
&nbsp;&nbsp; use **dates** to aggregate data by different time periods
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">19.</span>
<input type="checkbox" id="to19"><label markdown="1" for="to19">
&nbsp;&nbsp; use **SUM**, **AVG** and **COUNT** to aggregate rows in the data set
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">20.</span>
<input type="checkbox" id="to20"><label markdown="1" for="to20">
&nbsp;&nbsp; change **axis parameters** - _range, scale, title, tick marks_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">21.</span>
<input type="checkbox" id="to21"><label markdown="1" for="to21">
&nbsp;&nbsp; create **level of detail** (LOD) calculations
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">22.</span>
<input type="checkbox" id="to22"><label markdown="1" for="to22">
&nbsp;&nbsp; change the **ordering** of _categories_ displayed in a graphic and legend
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">23.</span>
<input type="checkbox" id="to23"><label markdown="1" for="to23">
&nbsp;&nbsp; use the _legend_ to **highlight** particular categories
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">24.</span>
<input type="checkbox" id="to24"><label markdown="1" for="to24">
&nbsp;&nbsp; edit **tooltips** to include _dynamic text_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">25.</span>
<input type="checkbox" id="to25"><label markdown="1" for="to25">
&nbsp;&nbsp; **filter** graphics _by date_, _interactively_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">26.</span>
<input type="checkbox" id="to26"><label markdown="1" for="to26">
&nbsp;&nbsp; **rename** worksheets
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">27.</span>
<input type="checkbox" id="to27"><label markdown="1" for="to27">
&nbsp;&nbsp; **duplicate** worksheets - you will need to make copies as you make changes
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">28.</span>
<input type="checkbox" id="to28"><label markdown="1" for="to28">
&nbsp;&nbsp; use _**Measure Names**_ and _**Measure Values**_ to create a _text table_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">29.</span>
<input type="checkbox" id="to29"><label markdown="1" for="to29">
&nbsp;&nbsp; create a **bar chart** and change the _ordering_ used to sort bars
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">30.</span>
<input type="checkbox" id="to30"><label markdown="1" for="to30">
&nbsp;&nbsp; create **graphical tooltips**
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">31.</span>
<input type="checkbox" id="to31"><label markdown="1" for="to31">
&nbsp;&nbsp; arrange worksheets in a composite **dashboard**
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">32.</span>
<input type="checkbox" id="to32"><label markdown="1" for="to32">
&nbsp;&nbsp; **size** a dashboard
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">33.</span>
<input type="checkbox" id="to33"><label markdown="1" for="to33">
&nbsp;&nbsp; use the **item hierarchy** in a dashboard to _select and manage_ dashboard contents
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">34.</span>
<input type="checkbox" id="to34"><label markdown="1" for="to34">
&nbsp;&nbsp; use **filters** to effect _all graphics_ in a dashboard
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">35.</span>
<input type="checkbox" id="to35"><label markdown="1" for="to35">
&nbsp;&nbsp; add **filter actions** to _focus graphics_ in a dashboard on selected items
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">36.</span>
<input type="checkbox" id="to36"><label markdown="1" for="to36">
&nbsp;&nbsp; **hide** header labels
<br/></label>&nbsp;
</div>

</div>

### Tableau Demo

Sometime today, perhaps at the end of the session, maybe at the start, I'll be showing you how to do a few more important things ...

<div class="checkList" markdown="1">

<div class="checkItem" markdown="1"><span class="checkNum">37.</span>
<input type="checkbox" id="sa1"><label markdown="1" for="sa1">
&nbsp;&nbsp; understand the concepts of **aggregation** & **detail** an use them in your graphics
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">38.</span>
<input type="checkbox" id="sa2"><label markdown="1" for="sa2">
&nbsp;&nbsp; add **annotations** to graphics
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">39.</span>
<input type="checkbox" id="sa3"><label markdown="1" for="sa3">
&nbsp;&nbsp; use **entire view** to fit a graphic into the screen space available
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">40.</span>
<input type="checkbox" id="sa4"><label markdown="1" for="sa4">
&nbsp;&nbsp; add and use a **highlighter**
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">41.</span>
<input type="checkbox" id="sa5"><label markdown="1" for="sa5">
&nbsp;&nbsp; change the **colour** and transparency of marks
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">42.</span>
<input type="checkbox" id="sa6"><label markdown="1" for="sa6">
&nbsp;&nbsp; add **trend lines** from the analytics pane
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">43.</span>
<input type="checkbox" id="sa7"><label markdown="1" for="sa7">
&nbsp;&nbsp; create a simple **story** by ordering dashboards and workbooks (and adding titles)
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">44.</span> 
<input type="checkbox" id="sa8"><label markdown="1" for="sa8">
&nbsp;&nbsp; create a **set** and colour items in a graphic according to _set membership_
<br/></label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">45.</span>
<input type="checkbox" id="sa9"><label markdown="1" for="sa9">
&nbsp;&nbsp; _combine data visually_ through a **dual axis**
<br/></label>&nbsp;
</div>

</div>
