# NearbyCabFinder
ANY UI RELATED CONTRIBUTIONS FOR THIS WILL BE WELCOME LIKE MAKING A WEBSITE AND SEEING THE CODE WORKING VISUALLY.

HELLO GUYS;

SO THIS SMALL PROJECT IS CODED IN <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>  AND HEAVILY RELIES ON MATHEMATICS OF GREAT DISTANCE FORMULA.
I WOULD NOT SUGEEST JUST COPYING THE CODE PLEASE SEE https://github.com/suhailopensource/NearbyCabFinder/blob/master/websitesthathelpedmeunderstand.txt
THIS LINK CONTAINS RESOURCES THAT HELPED ME UNDERSTAND AND CODE THIS PROJECT.

THIS CODE IS A SMALL REALLY BASIC EXAMPLE OF HOW COMPANIES LIKE OLA,UBER AND OTHER DELIVERING APPS HELP YOU FIND NEARBY CABS AND FOR FINDING NEARB DELIVERY GUYS TO DELIVER FOOD TO YOUR HOUSE
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/0f/Ola_Cabs_logo.svg/1200px-Ola_Cabs_logo.svg.png" style="height:40px;width:70px">
<img src="https://seeklogo.com/images/U/uber-logo-2BB8EC4342-seeklogo.com.png" style="height:40px;width:70px">
<img src="https://techstory.in/wp-content/uploads/2021/11/Zepto.jpg" style="height:40px;width:70px">


THE QUESTION IS AS FOLLOWS :-

**************************************
Given GPS co-ordinates(in degrees) of a person who needs a cab and co-ordinates of all the cabs in the city stored in a text file
in JSON format, find the user-id and name of all the cab drivers available in 50 km proximity.
WE NEED A FILE AS INPUT OF ALL LATITUDE AND LONGITUDE OF ALL CAB DRIVERS
Input : file customers.json which contains GPS co-ordinates of a person who needs a cab in degrees and co-ordinates of all the cabs in the city stored in a text file in JSON format.
Output : file answers.json which contains user-id and Name of all the cab drivers available in 50 km proximity stored in a new file.
**************************************

Approach Used:
1. Obtain latitude and longitude of each cab in string format along with their
user-id and name from the JSON encoded input file.

2. Convert latitude and longitude of the cab present in string format to double.

3. Convert latitude and longitude of both, the user and the cab present in
degrees to radians.

4. Calculate distance between the user’s location and the cab using Great Circle
Distance formula.

5. If distance is found to be less than or equal to 50 kms then output the user-
id and name of the cab driver to a new file else take no action.
*****************************************************************************

   HOW DO YOU RUN THIS PROGRAM?                                              
   1. Save the code and the file customers.json in a same location.
2. Now, compile the code(using cmd : g++ file_name.cpp) and run it(using cmd : ./a.out /home/gfg/customers.json) 
with passing file name customers.json along with proper location(e.g. /home/gfg/customers.json).
3. A file named answers.json will be created on the same location where code and customers.json file is existing.

*****************************************************************************