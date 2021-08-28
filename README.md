<strong>Horiseon Refactor</strong>
I have been tasked with refactoring Horiseon's website. My primary objections are to ensure all elements follow a logical structure independent of styling and positioning, check for missing alt attributes, and ensure the title is concise and descriptive. 

https://mike-lane.github.io/Refactor-Horiseon/

<img src="https://mike-lane.github.io/Refactor-Horiseon/assets/images/Screenshot.png" alt="Horiseon website, post refactor" width=" 600px" height="800px"/>

Changes are as follows: 

HTML changes
<ol>
    <li>line 7: Updated title to be more descriptive.</li>
    <li>line 11 and 26: Changed div selector to header selector.</li>
    <li>line 11: Removed class </li>
    <li>line 13: Changed "div" tag to "nav" tag.</li>
    <li>line 27, 28, and 51: Changed "div" selector to "section" selector.</li>
    <li>lines 30, 37, 44, 54, 61, 68: Added "alt" tags to each image.</li>
    <li>line 74 and 79: Changed "div" tag to "footer" tag</li>
    <li>line 74: removed class</li>
</ol>

CSS changes
<ol>
    <li>lines 20, 27, 32, 36, 44, and 48: Changed ".header" selector to "header" selector</li>
    <li>line 11: Moved "a" tag to top of file</li>
    <li>line 16: Moved "p" tag to top of file</li>
    <li>lines 36, 44. 48: Changed "header div" to "nav"</li>
    <li>lines 77, 86, 90: Moved content</li>
    <li>line 77: Combined ".search-engine-optimization", ".online-reputation-management", ".social-media-marketing" as all three had the same attributes.</li>
    <li>line 86: Combined ".search-engine-optimization img", ".online-reputation-management img", ".social-media-marketing img" as all three had the same attributes.</li>
    <li>line 90: Combined ".search-engine-optimization h2", ".online-reputation-management h2", ".social-media-marketing h2" as all three had the same attributes.</li>
    <li>line 110: Combined ".benefit-lead", "benefit-brand", and "benefit-cost" as all three had the same attributes.</li>
    <li>line 115: Combined ".benefit-lead h3", "benefit-brand h3", and "benefit-cost h3" as all three had the same attributes.</li>
    <li>line 120: Combined ".benefit-lead img", "benefit-brand img", and "benefit-cost img" as all three had the same attributes.</li>
    <li>lines 123 and 130: Changed ".footer" to "footer"</li>
    <li></li>
</ol>

