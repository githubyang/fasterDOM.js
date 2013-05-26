fasterDOM.js 0.1
============

Basic operations like jquery but much faster.

Operations: .css(), .attr(), .html(), .append(), .prepend(), .show(), .hide() , .get() (return elemens)

Performance
===========
All the tests showed improvements to performance at least 30%.

Performance Tests can be found here: http://jsperf.com/testbndr

You can also run the tests on your own computer with test.html page.

Example
=======
```
var elements = new FastDom(".elements");

elements.append("appendString").append(document.createElement("div"))
        .css({width:"1px"}).attr("class","someclass").html("some html string").hide().show();
```
