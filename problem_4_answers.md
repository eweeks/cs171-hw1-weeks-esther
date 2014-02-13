Problem 4 Questions - Esther Weeks

1. d3.selectAll("tbody tr")[0].length-1 
	This is ultimately sets the value for the max value for the domain. 
	This call finds out how many rows are in the table, it creates an
	array of the first column tr's, takes the length of that, 
	minus 1 to accommodate the zero indexing, this gives the total number of
	rows in the tbody, which in this table is 50.  
	
2. 0 is going to be the red-orange color, 50 is going to be silver, 150 
	is cyan. So we've set our domain to 0, and range to orange, domain to 50 
	and range to silver, so 0 is now orange and 50 is silver.
	
3. Orange would be set at 2.6, silver at 9, this is a smaller span of numbers than we
  originally had, and would have a more direct transition from orange to silver instead
  of the more gradual one. This also gives a visual effect of the change from the min to
  the max. This works when there is a gradual enough change between the min and max, and 
  you're wanting to highlight that change. 
	