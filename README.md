# Makers-Agency-app under the [humanitarian-agpl-license](http://namzezam.wikidot.com/humanitarian-agpl-license)
Makers Agency, the app of the ["makers" people grouped in their "channels" of an "agency"](http://liquid-unions.wikidot.com/liquid-agency), where
* each channel complete some "tasks" satisfying their "clients", as the agency is a registered organization and the makers are referable for the clients as channel@agency,
* the makers in the agency are free to move between the channels or to create a new channel, as one maker may be in more than one channel,
* the app maintain for the agency the negotiations with the clients and the registry of the makers in the channels, 
* the app find for each makers the most economical tasks by calculating the prices of the earn (in get direction) and lost (in spend direction), for each new task, per each of the directions, for one or more cycles and in a range or filter of time and geographic, as the calculation 
   * is triggered when clients issue new task to the agency or directly to the channels forwarded to the makers
   * is made also for completing additional tasks in the spend direction and  
   * is made on the makers' device and/or on their cloud service.

use-case1: 
* makers: 	drivers, which could also be "returning" in car sharing and/orin shared transpor
* clients:	cars agencies, 
* task: 	returning cars agencies, 
* get: 	drive-to,
* spend: 	returning,
* calculation: also made for driving additional cars while returning home.
 
use-case2:  
* makers: 	creative class, intellectuals, scientists, artists, developers etc,
* clients: 	institutes/companies,
* task: 	completing some offers, 
* get:  	creative class values supplied by the makers working team in their channel, eg: producing app,
* spend: 	costs for availability, accommodation, movement, equipment, learning time, spending time and stress. 
<center><a href="" target="_blank"><img src="http://namzezam.wdfiles.com/local--files/start/interface.png"/></a></center>

Converting a 2d map to a 3d map in time, by first rotating x to z and then showing x=time, y=north-south and z=east-west, such that position(r,maxz) = (y*maxz+z)*r and location(position) appear as horizontal line, where “here” is on y=0,z=0) at any time (and with some highlighted locations being shown), Where
*	earning: (price, to, from) 
*	position: has the earnings by their from=position, sorted by their price  and its header =(frequency, direction end density in extreme values, in average and in median of its earnings).
*	Each user has her/his own preferences as for	the prices of lost and and as for where and how the calculation is to be made (locally or remotely with  his/her team or alone).

On new input, adding new earnings (as drives), appearing as diagonals tendering to the right and colorized by their price, by connecting 2 locations per 1 earning in different times.
*	Calculating on the users device and/or (shared) cloud: the best earning, starting from the top earning while excluding some of the bottom lost, by connecting earnings in cheapest and nearest positions, defined by r, (back) directions etc in some near time defined by user preferences.
