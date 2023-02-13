### Tableau Tutorial - Getting Started with Tableau

<link rel="stylesheet" href="https://staff.city.ac.uk/~jad7/epm948/epm948.css">
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
  .listIndent {padding-left:4em}

</style>

#### Checklist of Concepts

Having watched the video and worked through the examples you should <strong>understand</strong> the following concepts and <strong>be able to use them</strong> in Tableau Desktop.

We'd like you to make a copy of this list and cross each item off as you have addressed it.

These are all <strong>essential concepts</strong> that you will need to be able to use in <em>Tableau Desktop</em> to succeed in the module.

Once you have tried each concept out when following the <strong>Getting Started</strong> videos then...
<strong>check the box or cross it off</strong>!

<style>
    .checkList {padding-left:4em; padding:2em;}
    .checkItem {padding:0.5em; padding-top:1.25em}
    .checkNum  {font-weight:bold; font-size:140%}
</style>

<div class="checkList" markdown="1">

<div class="checkItem" markdown="1"><span class="checkNum">1.</span>
<input type="checkbox" id="to1"><label markdown="1" for="to1">
&nbsp;&nbsp; load an <strong>Excel</strong> file into Tableau - to 'connect' a data set
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">2.</span>
<input type="checkbox" id="to2"><label markdown="1" for="to2">
&nbsp;&nbsp; <strong>extract</strong> the data - know the difference between <em>live</em> and <em>extract</em>
</label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>(we will normally want to extract)</em> <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">3.</span>
<input type="checkbox" id="to3"><label markdown="1" for="to3">
&nbsp;&nbsp; know and understand the difference between <strong>dimensions</strong> and <strong>measures</strong>
</label>&nbsp;
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - <strong>measures</strong> - <strong>green</strong> pills - these are <em>quantities</em>, numbers
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - <strong>dimensions</strong> - <strong>blue</strong> pills - these are <em>qualities</em>, categories (usually names) <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">4.</span>
<input type="checkbox" id="to4"><label markdown="1" for="to4">
&nbsp;&nbsp; create a <strong>hierarchy</strong> of dimensions (categories)
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">5.</span>
<input type="checkbox" id="to5"><label markdown="1" for="to5">
&nbsp;&nbsp; <strong>hide</strong> dimensions and measures
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">6.</span>
<input type="checkbox" id="to6"><label markdown="1" for="to6">
&nbsp;&nbsp; <strong>build</strong> visualizations in the <em>sheet</em> by dragging dimensions and measure fields to the <em>shelves</em> and <em>cards</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">7.</span>
<input type="checkbox" id="to7"><label markdown="1" for="to7">
&nbsp;&nbsp; <strong>calculate</strong> <em>new variables (measures)</em> - a <em>calculated field</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">8.</span>
<input type="checkbox" id="to8"><label markdown="1" for="to8">
&nbsp;&nbsp; use the <strong>back</strong> or <strong>undo</strong> button
</label>&nbsp;<br/>
<em class="listIndent">to get back to where you were - before you messed things up!</em> <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">9.</span>
<input type="checkbox" id="to9"><label markdown="1" for="to9">
&nbsp;&nbsp; use <strong>SAVE</strong> to save a <em>TWBX workbook</em> (a Tableau workbook with data)
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">10.</span>
<input type="checkbox" id="to10"><label markdown="1" for="to10">
&nbsp;&nbsp; use '<strong>Show Me</strong>' to select possible chart types
</label>&nbsp;<br/>
<em class="listIndent">this is the <strong>one click option</strong>, not a comprehensive list of possibilities</em> <br/>
</div>

<div class="checkItem" markdown="1"><span class="checkNum">11.</span>
<input type="checkbox" id="to11"><label markdown="1" for="to11">
&nbsp;&nbsp; select a <strong>colour scheme</strong>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">12.</span>
<input type="checkbox" id="to12"><label markdown="1" for="to12">
&nbsp;&nbsp; <strong>change</strong> the end and centre points of a <em>diverging colour scheme</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">13.</span>
<input type="checkbox" id="to13"><label markdown="1" for="to13">
&nbsp;&nbsp; show and use a <strong>filter</strong> to select relevant data items <em>interactively</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">14.</span>
<input type="checkbox" id="to14"><label markdown="1" for="to14">
&nbsp;&nbsp; use the <strong>row</strong> and <strong>column</strong> shelves to split the screen and structure a graphic
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">15.</span>
<input type="checkbox" id="to15"><label markdown="1" for="to15">
&nbsp;&nbsp; use the <strong>marks shelf</strong> to vary a graphic
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">16.</span>
<input type="checkbox" id="to16"><label markdown="1" for="to16">
&nbsp;&nbsp; know the difference between <strong>discrete</strong> and <strong>continuous</strong> fields
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">17.</span>
<input type="checkbox" id="to17"><label markdown="1" for="to17">
&nbsp;&nbsp; understand how Tableau uses <strong>dates</strong> (date parts and date values)
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">18.</span>
<input type="checkbox" id="to18"><label markdown="1" for="to18">
&nbsp;&nbsp; use <strong>dates</strong> to aggregate data by different time periods
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">19.</span>
<input type="checkbox" id="to19"><label markdown="1" for="to19">
&nbsp;&nbsp; use <strong>SUM</strong>, <strong>AVG</strong> and <strong>COUNT</strong> to aggregate rows in the data set
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">20.</span>
<input type="checkbox" id="to20"><label markdown="1" for="to20">
&nbsp;&nbsp; change <strong>axis parameters</strong> - <em>range, scale, title, tick marks</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">21.</span>
<input type="checkbox" id="to21"><label markdown="1" for="to21">
&nbsp;&nbsp; create <strong>level of detail</strong> (LOD) calculations
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">22.</span>
<input type="checkbox" id="to22"><label markdown="1" for="to22">
&nbsp;&nbsp; change the <strong>ordering</strong> of <em>categories</em> displayed in a graphic and legend
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">23.</span>
<input type="checkbox" id="to23"><label markdown="1" for="to23">
&nbsp;&nbsp; use the <em>legend</em> to <strong>highlight</strong> particular categories
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">24.</span>
<input type="checkbox" id="to24"><label markdown="1" for="to24">
&nbsp;&nbsp; edit <strong>tooltips</strong> to include <em>dynamic text</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">25.</span>
<input type="checkbox" id="to25"><label markdown="1" for="to25">
&nbsp;&nbsp; <strong>filter</strong> graphics <em>by date</em>, <em>interactively</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">26.</span>
<input type="checkbox" id="to26"><label markdown="1" for="to26">
&nbsp;&nbsp; <strong>rename</strong> worksheets
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">27.</span>
<input type="checkbox" id="to27"><label markdown="1" for="to27">
&nbsp;&nbsp; <strong>duplicate</strong> worksheets - you will need to make copies as you make changes
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">28.</span>
<input type="checkbox" id="to28"><label markdown="1" for="to28">
&nbsp;&nbsp; use <em><strong>Measure Names</strong></em> and <em><strong>Measure Values</strong></em> to create a <em>text table</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">29.</span>
<input type="checkbox" id="to29"><label markdown="1" for="to29">
&nbsp;&nbsp; create a <strong>bar chart</strong> and change the <em>ordering</em> used to sort bars
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">30.</span>
<input type="checkbox" id="to30"><label markdown="1" for="to30">
&nbsp;&nbsp; create <strong>graphical tooltips</strong>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">31.</span>
<input type="checkbox" id="to31"><label markdown="1" for="to31">
&nbsp;&nbsp; arrange worksheets in a composite <strong>dashboard</strong>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">32.</span>
<input type="checkbox" id="to32"><label markdown="1" for="to32">
&nbsp;&nbsp; <strong>size</strong> a dashboard
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">33.</span>
<input type="checkbox" id="to33"><label markdown="1" for="to33">
&nbsp;&nbsp; use the <strong>item hierarchy</strong> in a dashboard to <em>select and manage</em> dashboard contents
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">34.</span>
<input type="checkbox" id="to34"><label markdown="1" for="to34">
&nbsp;&nbsp; use <strong>filters</strong> to effect <em>all graphics</em> in a dashboard
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">35.</span>
<input type="checkbox" id="to35"><label markdown="1" for="to35">
&nbsp;&nbsp; add <strong>filter actions</strong> to <em>focus graphics</em> in a dashboard on selected items
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">36.</span>
<input type="checkbox" id="to36"><label markdown="1" for="to36">
&nbsp;&nbsp; <strong>hide</strong> header labels
</label>&nbsp;
</div>

</div>

### Tableau Demo

Sometime soon, perhaps at the end of the session, maybe at the start, maybe next week or later on the course ... or perhaps on video (!) ... I'll be showing you how to do a few more important things.

Make sure you can do them too ...

<div class="checkList" markdown="1">

<div class="checkItem" markdown="1"><span class="checkNum">37.</span>
<input type="checkbox" id="sa1"><label markdown="1" for="sa1">
&nbsp;&nbsp; understand the concepts of <strong>aggregation</strong> & <strong>detail</strong> an use them in your graphics
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">38.</span>
<input type="checkbox" id="sa2"><label markdown="1" for="sa2">
&nbsp;&nbsp; add <strong>annotations</strong> to graphics
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">39.</span>
<input type="checkbox" id="sa3"><label markdown="1" for="sa3">
&nbsp;&nbsp; use <strong>entire view</strong> to fit a graphic into the screen space available
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">40.</span>
<input type="checkbox" id="sa4"><label markdown="1" for="sa4">
&nbsp;&nbsp; add and use a <strong>highlighter</strong>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">41.</span>
<input type="checkbox" id="sa5"><label markdown="1" for="sa5">
&nbsp;&nbsp; change the <strong>colour</strong> and transparency of marks
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">42.</span>
<input type="checkbox" id="sa6"><label markdown="1" for="sa6">
&nbsp;&nbsp; add <strong>trend lines</strong> from the analytics pane
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">43.</span>
<input type="checkbox" id="sa7"><label markdown="1" for="sa7">
&nbsp;&nbsp; create a simple <strong>story</strong> by ordering dashboards and workbooks (and adding titles)
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">44.</span> 
<input type="checkbox" id="sa8"><label markdown="1" for="sa8">
&nbsp;&nbsp; create a <strong>set</strong> and colour items in a graphic according to <em>set membership</em>
</label>&nbsp;
</div>

<div class="checkItem" markdown="1"><span class="checkNum">45.</span>
<input type="checkbox" id="sa9"><label markdown="1" for="sa9">
&nbsp;&nbsp; <em>combine data visually</em> through a <strong>dual axis</strong>
</label>&nbsp;
</div>

</div>
