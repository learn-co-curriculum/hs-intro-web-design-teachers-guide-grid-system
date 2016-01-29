### SWABTS 
***Students will be able to understand the fundamentals of the grid system and incorporate them into their project***


### Motivation
The grid system is a tool for establishing spatial hierarchy in your website. Grids can provide an important guideline in creating the layout of your website.


### Lesson Plan 
+ The human brain is good at identifying patterns and one way that patterns are reflected in design is through the use of grids.
+ A grid is a tool that can be used to establish a spacial hierarchy of the content. It can be fixed or fluid, horizontal or vertical, uniform or responsive. Grids should be viewed as guides, not boundaries; good designers know how to use grids, great designers know how and when to break them.
+ The rules of threes or four 
	+ Dividing a page up into threes or fours tends to be pleasing to the eye - and to take advantage of both these ratios web design tends to split up a page into a 12 column grid (12 = 3 * 4)
	+ This way you can easily split the page in half, thirds or fourths

+ Here are some examples of how you can split up the 12-grid:

<img src="https://s3.amazonaws.com/after-school-assets/grid-system.png">

+ It’s easy to do this with css by setting a standard width for a column and then creating divs that are exactly 6 columns wide, 3 columns wide, 2 columns wide etc.
+ One way to do this is to decide on a maximum width for the layout of your site.
+ Let’s say you are designing for an average sized screen with a max width of 960 pixels. To get the width of one column we do 960/12 = 80.
+ So a one column wide div might have a class of .col-1 and css that looks like this:
	```css
	.col-1 {
		 max-width: 80px;
	 }
	```
+ two columns wide:
	```css
	 .col-2 {
		 max-width: 160px;
	 }
	```
+ three columns wide (like what we have in the right most example):
	```css
	 .col-3 {
		 max-width: 240px;
	 }
	```
+ four columns wide (like what we have in the middle example):
	```css
	.col-4 {
		 max-width: 320px;
	 }
	```
+ and a six column wide div (like what we have in the left most example) might have a class of .col-6 and css that looks like this:
	```css
	.col-6 {
		 max-width: 480px;
	}
	```

+ Not toooooo tricky, right? 
+ You wouldn’t necessarily need to use pixel widths either. If you prefer to determine your widths with percentages you can also take 100/12 = 8.33333%.
+ So `.col-1 {width: 8.3333%}`, `.col-2 {width: 16.66666%}`, `.col-3 {width: 25%}`, etc.
+ The last thing to think about when you are setting up a grid system is how much space you might want between columns - or the gutter between columns. 
+ You can standardize this with a little bit of math too. It might actually be easiest to just decide on a standard padding between columns and apply that to each column style like so:
+ one column
	```css
	.col-1 {
		 max-width: 70px;
		 margin-left: 5px;
		 margin-right: 5px;
	 }
	```
+ two columns wide:
```css
	 .col-2 {
		 max-width: 150px;
		 margin-left: 5px;
		 margin-right: 5px;
	 }
```

+ Don’t forget to think about which box model you are using and how your padding (within the columns) and border widths will affect the spacing.


### Conclusion
Because columns are pleasing to the eye, people respond better to a website with a grid system layout.

### Hints and Hurdles 

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-intro-web-design-teachers-guide-grid-system' title='SWABTS'>SWABTS</a> on Learn.co and start learning to code for free.</p>
