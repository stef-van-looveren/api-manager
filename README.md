# Api manager (coming soon)
A drupal 8 api management module. Turns API's in nodes and terms easily.

### What does it do?
The module lets you set up multiple api connections via the drupal interface. Map the fields with your key|destination_field pairs and you are good to go.

A typical result after importing is: **Sync done at 2019-06-18 16:56:53: total: 210, new: 10, updated: 0, errors: 1, skipped: 199, deleted: 0**. 

### Why? 
When setting up multiple API's in one site or module, the code gets a bit unclear quickly. Furthermore, only the developer has insight on what is imported and which fields are paired from the API to the destination content type.
The API manager handles everything in the interface.

### Installation
Just enable the module. Under 'Structure' you will find a new menu item called 'Api manager'. To there and add your first API. In the main list view, there is a button 'Run import' to directly test your settings. 

### Types of API?
At this moment, only JSON is available as a type. Also, for the time being without authentication. It is meant for use on small to medium sized websites.