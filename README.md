manipulation-of-directories-C
=============================

manipulation of directories C
 	

 Management directory in C 

  	5 	

+The structure is a one-way linked list representing the structure of directories and files in a secondary memory (hard disk, flash disk ...). Each element of the list describes a directory and its contents direct.Le contents of a directory fear be one or more directories ( sub- directory ) and / or one or more fichiers.Dans our case, we consider that the number of sub -directory shall not exceed two .

  	6 	

+Functions that meet the following queries are implemented:

  	7 	

+1- Building structure above parir data seized clavier.Pour each directory , we donnerale name, the name of the sub- directories and file names ( for each file , it saves the name, size and date creation )

  	8 	

+2 - Display the contents of a directory given R ( FACN showing of the tree) .

  	9 	

+3 - Show entire tree .

  	10 	

+4 - Find a file ( or directory ) and display its properties.

  	11 	

+5 Add - f file given a directory A.

  	12 	

+6 - Delete a file f given a directory A.

  	13 	

+7 - Rennomer ( rename ) a given file f .

  	14 	

+8 - R Add a directory as a subdirectory of a given (if it does not exist) R1 directory.

  	15 	

+9 - R Delete directory (and all its contents) if it exists.
