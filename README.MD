# MultiProcessBrowser

	Browser is a simple multi-process web browser that allows simple webpage browsing. Users can easily open different webpages in different tabs.

## COMPILE:

	You need GCC 4.7.2 to compile this program. To change your GCC version, run
		setenv PATH /soft/gcc-4.7.2/ubuntuamd2010/bin/:$PATH
	
	With GCC 4.7.2, run
		make
	to compile the program.
	
## HOW TO OPEN:
	
	After the compilation, run
		./browser
		
## NOTICE:

	The program will choose the first unused tab index to open the tab. It will not choose tab index per user input.
	
## ERROR HANDLING:

	Any potential error, for example, pipe creating error, or users trying to open more tabs than allowed, will trigger a error message that specifies the error.
