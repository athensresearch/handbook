# Backups in Athens Research 

At Athens, we fundamentally believe in data ownership and data privacy. It is from this belief that our backup system has been implemented. The primary goal of our backup system is to make it possible to revert your data back to any point in time so that there is  *zero* room for data loss due to corruption and other formatting issues. 
## Restoring from Backups
Backups in Athens are stored in a .bkp format which is easy to restore from.  Look for a .bkp file with a creation time corresponding to the state of the DB you would like to go back to. Once you've identified a bkp file that matches, rename it to index.transit. While restoring from a backup, it is wise to save current index.transit file to another directory before renaming a bkp to prevent losing the data. 

## Frequency of  Backups
You can set your desired backup and auto save frequency in the settings page. By default, Athens saves a copy of your database every 15 seconds into your main folder. 

## Best practices
As Athens currently doesn't automatically delete your old backups, it becomes important to periodically clear out your folder in order to prevent it from taking too much space on your hard drive. The lower your auto save interval, the more freunlty you should likely undertake this. 

Additionally, because the backups are locally stored(for the moment), it makes sense to periodically backup the folder to a cloud service like Dropbox or Google Drive.
