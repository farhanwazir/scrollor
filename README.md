<h1 id="pagetop">Scrollor</h1>
<p>JQuery plugin for scroll page and/or element(s) by one line of code.</p>
<div class="developer">
<pre>
Plugin Name:		Scrollor
Author:			Farhan Wazir
Email:			seejee1@gmail.com
Plugin URL:		<a href="http://cideator.com/jquery/scrollor">http://cideator.com/jquery/scrollor</a>

<strong>Company Info</strong>
			<a href="http://cideator.com"><img src="http://cideator.com/external_use_logos/onecolor-small-100x46.png" /></a>
Email:			cideator@gmail.com
Website:		http://cideator.com
</pre>
</div>
<h3>Features:</h3>
<ol>
	<li>Scrollor, find target automatically and element get in focus. Plugin just need target id, i.e <code>$(target_id).scrollor()</code></li>
	<li>You can scroll single or both (x or y or xy and/or yx) axis</li>
    <li>You can set your duration.</li>
    <li>You can set animation easing, defaults are "swing" and "linear". If you want more then use <a href="http://api.jqueryui.com/easings/">jquery UI</a></li>
    <li>You can adjust your scrolling layout by offsetTop and offsetLeft</li>
    <!--<li>If you don't want scrollor only scroll your element, not parents elements then set "parents" to false. i.e <code>$(target_id).scrollor({parents:false})</code></li>-->
    <li>3 different triggers you can use, onStart, onAfterEach and onAfter</li>
</ol>
<h3>Usage</h3>
<ul>
	<li><code>$(target_id).scrollor({options here})</code></li>
</ul>
<h3>Options</h3>
<ul class="options">
	<li><span class="type"><strong>duration:</strong> (Number), default:500</span> in miliseconds, example: 1000 = 1 second</li>
    <li><span class="type"><strong>durationMode:</strong> (Boolean), default:true</span> true/false</li>
    <li><span class="type"><strong>easing:</strong> (String), default:"swing"</span> available "swing" and "linear", for more use <a href="http://api.jqueryui.com/easings/">jquery UI</a></li>
    <li><span class="type"><strong>offsetTop:</strong> (Number, default:0)</span> it is margin-top of target element/object</li>
    <li><span class="type"><strong>offsetLeft:</strong> (Number), default:0</span> it is margin-left of target element/object</li>
    <li><span class="type"><strong>animateBoth:</strong> (Boolean), default:true</span> if false then animate first axis and then another axis, example: if axis: 'yx' so first scroll y and then x</li>
    <li><span class="type"><strong>axis:</strong> (String), default:'xy'</span> 4 different variation you can use 'x' or 'y' or 'xy' or 'yx', if animateBoth: true then 'xy' and 'yx' both equals to 'xy' and it is false then scrollor scroll first letter of axis and then other</li>
    <li><span class="type"><strong>onStart</strong> (Function), default:none</span> this is event, it triggered before scrollor start scrolling</li>
    <li><span class="type"><strong>onAfter</strong> (Function), default:none</span> this is event, it triggered after scrollor complete scrolling</li>
    <li><span class="type"><strong>onAfterEach</strong> (Function), default:none</span> this is event, it triggered after each axis scroll, it works when animateBoth set to false</li> 
</ul>
<h2 id="demo">Demo</h2>
see demo at http://cideator.com/jquery/scrollor#demo
<br />
<br />
<div class="copyrights">Copyrights &copy; 2014, Creative Ideator.</div>
