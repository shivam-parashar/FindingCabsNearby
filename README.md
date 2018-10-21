# FindingCabsNearby

                             *****Finding cabs nearby using Great Circle Distance formula*****

Given GPS co-ordinates(in degrees) of a person who needs a cab and co-ordinates of all the cabs in the city stored in a text
file in JSON format, find the user-id and name of all the cab drivers available in 50 km proximity.

Input : file customers.json which contains GPS co-ordinates of a person who needs a cab in degrees and co-ordinates of all the cabs in the city stored in a text file in JSON format.
Output : file answers.json which contains user-id and Name of all the cab drivers available in 50 km proximity stored in a new file.

Procedure to run the program :
1. Save the code and the file customers.json in a same location.
2. Now, compile the code(using cmd : g++ file_name.cpp) and run it(using cmd : ./a.out /home/gfg/customers.json) with passing file name customers.json along with proper location(e.g. /home/gfg/customers.json).
3. A file named answers.json will be created on the same location where code and customers.json file is existing.

