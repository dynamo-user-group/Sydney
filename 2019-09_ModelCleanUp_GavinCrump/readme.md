# Using Dynamo to prepare Models for Exchange
## 02/09/2019 - Gavin Crump
[Meetup Link](https://www.meetup.com/en-AU/Dynamo-Sydney-User-Group/events/263744738/)

Also, thanks to Gavin for registering his session and sharing on YouTube!
[YouTube Link](https://www.youtube.com/watch?v=jJSHmJnXIdk)

![Cover](\imgs\cover.png)

Revit models can get quite messy – luckily Dynamo is here to do some model cleaning for us!
The script prepared for the workshop uses data shapes to generate a user interface, which then feeds some outputs into script modules which target and clean the following;
*	Remove unused view templates
*	Remove unused filters
*	Remove ‘IMPORT’ patterns (usually from CAD files)
*	Purge all
*	Views with a Type Name that contains ‘working’
*	Remove all Legends
*	Remove all Schedules
Once all the data has been processed, the results are tallied and displayed to the user in a secondary interface.

The merit of this script, is it combines all of these functions into one single script, as well as putting a high level audit for exchange in the hands of any capable Dynamo user (as opposed to Model/BIM Managers only).

Find in this folder:
* Revit model used during the lab
* Dynamo graphs used during the lab
* List of packages used in the Dynamo graph
* Pdf presentation
* Images folders with screenshots and relevant pictures
