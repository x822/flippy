The index.html file has a script to initialize the flipbook.


Easy peasy 3 steps to create a new flipbook:

1. Duplicate the folder
2. Change the pdf link in var pdf = (if using pdf) OR Change links to images in var jpg = (if using jpgs for pages)
3. Change the page title and meta data to something more suitable to the book / offer


Use the following js to add hotspots to pages.

		    //PAGE *NUMBER*
		    //first two parameters are width and height of page
		    //other are array of hotspots with their attributes
		    options.links[*NUMBER*] = [
		      500, //width of page
		      500, //height of page
		      //[x-start-position,y-start-position,width,height,destination]
		      [50, 50, 300, 300, "https://www.hdfcbank.com"], //destination as link
		    ];

Insert the corresponding page number in place of *NUMBER*

Created with ❤︎