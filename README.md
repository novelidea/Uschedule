# Uschedule

## App Description
Uschedule is an App designed for university students and faculties. It can provide users with latest time-related information about university facilities, such as library, restaurant, swimming pool and gym etc. It's very common for students to ask friends or search online in order to know whether restaurant is open today or when is library open tomorrow which is time consuming. Or sometimes finding gym closed when standing in front of gym's gate. By using Uschedule, students can subscribe categories that they are interested in and check the latest time-related information in a convenient way. 

**Screenshot**
![image](./img/Uschedule_Overview.png)

## Data Source
Due to the large amount data that Uschedule needs to use, it's unwise to check all related websites and input all data into database manually. Therefore, there are many network spiders writing in Python running on server. All these spiders can crawl data from corresponding website everyday and then the crawled data will be transformed into standard format so that it can be inserted into database directly.
<<<<<<< HEAD

**Welcome Contributors**
Uschedule is an app based on network spiders. Usually, one website needs one particular spider to generate data which brings lots of work to website analysis and coding. Therefore, I welcome programmers all over the world join this program and write network spiders to crawl time-related data from websites. All contributors' GitHub account will be presented in the App in the following way. Database API will be released in the following weeks.

**How to Join
Developers can either submit a crawler written in Python or own server url. All data should be in the following formate.

```javascript
{
	schedule_id: String,
    schedule_name : String,
    schedule_details : [
    	{
        	item_title : String,
           	item_data : String
        }
    ]
}
```
Take USC Libraries' schedule data as an example:

```javascript
{
	'schedule_id' : 'USC_LIBRARY', 
	'schedule_name' : 'USC Library', 
	'schedule_details' : [
		{
			'item_title' : 'Accounting Library', 
			'item_data' : 'Sunday(Aug 21): 12pm - 8pm\nMonday(Aug 22): 7:30am - 10:30pm\nTuesday(Aug 23): 7:30am - 10:30pm\nWednesday(Aug 24): 7:30am - 10:30pm\nThursday(Aug 25): 7:30am - 10:30pm\nFriday(Aug 26): 7:30am - 5pm\nSaturday(Aug 27): 9am - 5pm\n'
			},
		{
			'item_title' : 'Architecture and Fine Arts Library', 
			'item_data' : 'Sunday(Aug 21): Closed\nMonday(Aug 22): 9am - 10pm\nTuesday(Aug 23): 9am - 10pm\nWednesday(Aug 24): 9am - 10pm\nThursday(Aug 25): 9am - 10pm\nFriday(Aug 26): 9am - 5pm\nSaturday(Aug 27): Closed\n'
		}
}
```


=======

## Welcome Contributors
Uschedule is an app based on network spiders. Usually, one website needs one particular spider to generate data which brings lots of work to website analysis and coding. Therefore, I welcome programmers all over the world join this program and write network spiders to crawl time-related data from websites. All contributors' GitHub account will be presented in the App in the following way. Database API will be released in the following weeks.

>>>>>>> c444d4f52c7cdc6fa637faac8c05e51b1d671096
