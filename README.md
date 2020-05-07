# Health Monitor Application
  - [UI](#UI)
  - [Features](#Features)
## UI
  + MainForm
  
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/1.png)
    + Menu/Taskbar/Status bar/TreeView/GridView.
    
  + SubForm
  
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/2.PNG)
    + Called up by Add/Search options in MainForm.

## Features
1. Load and Save
    + Load and save data interacting with .csv files
   
2. Add new record
    + Call up SubForm for entering new record
    + User can apply add option with toolbar/menubar.

3. Search by Gin
    + Search in the lower left text box with valid Gin.
    + Message box will pop up with corresponding record in database, then SubForm is called for edit or delete option.
    + Error message will pop up if input is invalid or not found.
    
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/3.PNG)

4. Delete record
    + Search in the lower left text box with valid Gin.
    + Choose delete option in SubForm to delete corresponding record
    
5. Sort display by date/name
    + Grid view is real-time interacting with user.
    + Selecting the radio button on up right corner will sort the grid with corresponding option.
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/4.PNG)
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/5.PNG)
    
6. Filter the grid with TreeView
    + TreeView nodes are showing real-time database.
    + Selecting the nodes will filter the grid with exact records.
    ![](https://github.com/jzhang182/HealthMonitor/blob/master/6.PNG)
