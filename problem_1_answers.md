Problem 1 Questions - Esther Weeks

1. colspan="3" attr of the <th> sets how many columns that th  will span.
	If set to 2, it will only span 2 columns, etc.

2. Styles Applied to th element Rank:
	
	.main-content th { padding: 3px; } 
		- This is from css (bls content.css)
		- Adds 3 px of space (on all sides) between th border and th content
		
	align="center"
		- html in th tag
		- Aligns content in the th element to center
		- css equivalent is text-align: center
		
	body * {line-height: 1.22em; }
		-This is also from css (bls content.css)
		- Sets everything in the body to a line-height of 1.22 em
		
	*{ margin: 0 }
		-This is also from css (bls content.css)
		- Gives all elements a margin of 0, meaning no area around the element
		outside of the border. 
		
	3. DOM inspector shows the page currently, while the source code is drawing from the
		server. The DOM inspector allows you to view the code more interactively, opening 
		and closing elements in the tree, and dynamically updating them to see what the 
		the changes will do. In allows you to see what styles are being applied to which
		elements, and where these styles are coming from. It also gives errors to scripts,
		and allows viewing of the console, also useful in debugging. The DOM inspector 
		can be very usefully for finding errors, and understanding what changes in code
		might do. It also is useful in code scripts as you can see how the elements are
		being manipulated. The source code shows exactly what is on the server. This can
		also be useful in seeing the original state of the page. If error correction is being
		applied by your browser, you may not see some errors in the code in the DOM 
		inspector that will show up in the source code. For example, in looking at the bls
		website, the table is missing a closing tr, which is added in the inspector, but
		is not present the source code. The browser is also adding a tbody to the code, which
		isn't present in the source. 