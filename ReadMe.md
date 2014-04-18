======= Landscape Responsive Framework
======= www.landscape.gary-wilkerson.com  
======= By: Gary Wilkerson | www.gary-wilkerson.com  
======= Free to use under the MIT license.  
======= http://www.opensource.org/licenses/mit-license.php

Welcome, and thanks for downloading!

Table of Contents:

	*index.html
		-Before you begin
		-Grid Classes
		-The parent "wrap" class
	*style.css
		-Getting started
		-Media Queries
		-@font-face
	*jQuery
		
	
	
============================================================

===== index.html =====

Before you begin your project, ensure that you have either updated your favicons or deleted 
the content under the "<!-- ===== Favicons ===== -->" section within the <head> tag.

Landscape is a 12-column grid system based off of specific classes. Each class name specifies
how many columns your <div> will span across.  Below are the class naming conventions:

	One Column:		col-1
	Two Columns:	col-2
	Three Columns:	col-3
	Four Columns:	col-4
	Five Columns:	col-5
	Six Columns:	col-6
	Seven Columns:	col-7
	Eight Columns:	col-8
	Nine Columns:	col-9
	Ten Columns:	col-10
	Eleven Columns:	col-11
	Twelve Columns:	col-12
	
So, for instance, if you want to create a three column section you would use the following:

	<div class="col-3"> </div>
	<div class="col-3"> </div>
	<div class="col-3"> </div>
	
There are also more general class naming conventions built in if you prefer using these 
instead:

	Full Width:				col-full
	Half Width:				col-half
	One-Third Width:		col-third
	One-Quarter Width:		col-quarter
	Three-Quarters Width:	col-threequarter
	
So, using the same example above for a three column section, this too would work:

	<div class="col-third"> </div>
	<div class="col-third"> </div>
	<div class="col-third"> </div>
	

When building your content you must also ensure that all classes are wrapped in a div with 
the class of "wrap":

	<div class="wrap">
		<div class="col-quarter"> </div>
		<div class="col-threequarter"> </div>
	</div>

This parent element will ensure that the grid system works smoothly by applying clearfix.


============================================================

===== style.css =====

The .css file is pretty straightforward and created with immediate development in mind.  As 
stated above clearfix is already in place for elements with the class of "wrap".  Also, box-sizing 
is already in place for all elements, and the Landscape grid system is already imported into the 
styles.css file.

The media queries are pretty general for desktop to laptop, tablet, and mobile. Generic media 
queries are also in place with a reference to www.howbigismybrowser.com to help create your 
own custom breakpoints if needed.  Just uncomment the section, or copy and paste into the existing
media queries.

The @font-face rules at the bottom are in place as well and pointing to an empty "fonts" folder 
which ships with this framework.  Go to www.fontsquirrel.com to get your hands on some great 
typekits and drop them into this folder.  Then just uncomment and insert your font's name.  Or 
if you prefer something like Google Fonts, there is a section specified in the index.html file's 
<head> to insert this information.  


============================================================

===== jQuery =====

To be on the fast side, jQuery is pulled from Google API.  To be on the safe side, there is also 
a local backup copy that ships with this framework.  If you prefer one over the other completely 
this can be altered towards the bottom of the index.html file.  Otherwise, you are good to go.


============================================================

Thanks again for downloading.  Visit my blog and portfolio at www.gary-wilkerson.com and follow 
me on Twitter: @wilkerson_gary. 