---
published: true
title: Agency Staff and Client Ratio
author: kartik
layout: post
categories: 
  - policy
tags: Welfare Survey
---

This interactive visualization provides a comparative analysis of state agencies in terms of their number staff and their number of clients. Agencies are divided into, 'general', 'blind' and 'combined' categories.
**The X-axis shows the number of counselors and the Y-axis shows the number of clients.**


***The X-axis shows the number of counselors and the Y-axis shows the number of clients they serve.***

  <iframe seamless="seamless" scrolling="no" src="/coun_coun.html" width="960" height="400"></iframe>
  
Click on the colored dots along side the categories in the legend to select different types of agencies. You also have an option to magnify certain portion of the graph to further examine relative position of different agencies. To magnify, click on the circle alongside 'magnify' and then move on to the chart area. To hold the magnified view, click on the chart area and click again to restart the magnification upon hovering the mouse pointer. Deselect the 'magnify' circle to stop magnification altogether.

<script type="text/javascript">
 
// jsData 
function gvisDataTableID34b62862450 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Alabama",
"Combined",
0,
199 
],
[
 "Alaska",
"Combined",
1537,
39 
],
[
 "American Samoa",
"Combined",
205,
4 
],
[
 "Arizona",
"Combined",
12780,
187 
],
[
 "Arkansas",
"Blind",
489,
37 
],
[
 "California",
"Combined",
44869,
724 
],
[
 "Colorado",
"Combined",
10907,
111 
],
[
 "Connecticut",
"Blind",
191,
17 
],
[
 "Connecticut",
"General",
4443,
77 
],
[
 "Delaware",
"Blind",
156,
7 
],
[
 "Delaware",
"General",
6982,
34 
],
[
 "District of Columbia",
"Combined",
0,
54 
],
[
 "Florida",
"Blind",
0,
54 
],
[
 "Florida",
"General",
26667,
439 
],
[
 "Georgia",
"Combined",
15339,
262 
],
[
 "Guam",
"Combined",
2,
8 
],
[
 "Hawaii",
"Combined",
1319,
34 
],
[
 "Idaho",
"Blind",
0,
11 
],
[
 "Idaho",
"General",
7136,
69 
],
[
 "Illinois",
"Combined",
23174,
365 
],
[
 "Indiana",
"Combined",
11472,
186 
],
[
 "Iowa",
"Blind",
239,
20 
],
[
 "Iowa",
"General",
28689,
107 
],
[
 "Kansas",
"Combined",
4186,
83 
],
[
 "Kentucky",
"General",
22660,
144 
],
[
 "Kentucky",
"Blind",
765,
16 
],
[
 "Louisiana",
"Combined",
19263,
104 
],
[
 "Maine",
"General",
5074,
89 
],
[
 "Maine",
"Blind",
304,
24 
],
[
 "Maryland",
"Combined",
14005,
170 
],
[
 "Massachusetts",
"Blind",
1002,
48 
],
[
 "Massachusetts",
"General",
11195,
256 
],
[
 "Michigan",
"Blind",
1040,
36 
],
[
 "Michigan",
"General",
22068,
269 
],
[
 "Minnesota",
"General",
6782,
154 
],
[
 "Minnesota",
"Blind",
0,
20 
],
[
 "Mississippi",
"Combined",
13356,
135 
],
[
 "Missouri",
"General",
15865,
147 
],
[
 "Missouri",
"Blind",
839,
17 
],
[
 "Montana",
"Combined",
2743,
39 
],
[
 "Nebraska",
"Blind",
491,
22 
],
[
 "Nebraska",
"General",
2180,
77 
],
[
 "Nevada",
"Combined",
1537,
49 
],
[
 "New Hampshire",
"Combined",
0,
51 
],
[
 "New Jersey",
"Blind",
500,
42 
],
[
 "New Jersey",
"General",
16241,
116 
],
[
 "New Mexico",
"Blind",
197,
8 
],
[
 "New Mexico",
"General",
6031,
80 
],
[
 "New York",
"Blind",
74,
65 
],
[
 "New York",
"General",
47336,
436 
],
[
 "North Carolina",
"Blind",
1563,
35 
],
[
 "North Carolina",
"General",
34788,
344 
],
[
 "North Dakota",
"Combined",
3159,
54 
],
[
 "Northern Marianas",
"Combined",
97,
3 
],
[
 "Ohio",
"Combined",
0,
259 
],
[
 "Oklahoma",
"Combined",
12860,
204 
],
[
 "Oregon",
"Blind",
264,
16 
],
[
 "Oregon",
"General",
4837,
121 
],
[
 "Pennsylvania",
"Combined",
18469,
416 
],
[
 "Puerto Rico",
"Combined",
22413,
295 
],
[
 "Rhode Island",
"Combined",
4702,
48 
],
[
 "South Carolina",
"Blind",
387,
28 
],
[
 "South Carolina",
"General",
5105,
235 
],
[
 "South Dakota",
"Blind",
169,
9 
],
[
 "South Dakota",
"General",
2162,
43 
],
[
 "Tennessee",
"Combined",
9350,
252 
],
[
 "Texas",
"Blind",
3914,
134 
],
[
 "Texas",
"General",
18953,
548 
],
[
 "Utah",
"Combined",
467,
129 
],
[
 "Vermont",
"Blind",
144,
4 
],
[
 "Vermont",
"General",
4850,
70 
],
[
 "Virgin Islands",
"Combined",
121,
10 
],
[
 "Virginia",
"Blind",
714,
17 
],
[
 "Virginia",
"General",
20253,
273 
],
[
 "Washington",
"Blind",
259,
16 
],
[
 "Washington",
"General",
4539,
119 
],
[
 "West Virginia",
"Combined",
0,
110 
],
[
 "Wisconsin",
"Combined",
22490,
166 
],
[
 "Wyoming",
"Combined",
1721,
29 
] 
];
data.addColumn('string','State Name');
data.addColumn('string','Agency Type');
data.addColumn('number','Number of Clients');
data.addColumn('number','Number of Staff');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartTableID34b62862450() {
  var data = gvisDataTableID34b62862450();
  var options = {};
options["allowHtml"] = true;
options["height"] =    400;

     var chart = new google.visualization.Table(
       document.getElementById('TableID34b62862450')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "table";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartTableID34b62862450);
})();
function displayChartTableID34b62862450() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID34b62862450"></script>
 
<!-- divChart -->
  
<div id="TableID34b62862450"
  style="width: 600px; height: 400px;">
</div>
 <div><span>Data: cc &#8226; Chart ID: <a href="Chart_TableID34b62862450.html">TableID34b62862450</a></span><br /> 

<span> 
R version 3.0.0 (2013-04-03) &#8226; <a href="http://code.google.com/p/google-motion-charts-with-r/">googleVis-0.4.3</a>
&#8226; <a href="https://developers.google.com/terms/">Google Terms of Use</a> &#8226; <a href="https://google-developers.appspot.com/chart/interactive/docs/gallery/table.html#Data_Policy">Data Policy</a>
</span></div>