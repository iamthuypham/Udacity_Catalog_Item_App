# Catalog Item App

Catalog Item App is one of student projects of Full Stack Nanodegree program at Udacity. This application provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

### What Student Learns
- Developing a RESTful web application using Python framework Flask
- Implementing third-party OAuth authentication
- Using the various HTTP methods and CRUD (create, read, update and delete) operations.

### Features
- Users can log in and log out with Google or Facebook accounts
- Users can read any catalogs and items
- Registered users can create, update, and delete their own catalogs and items
- Unregistered users are redirect to log in page if they try to create, update, or delete any catalogs and items
- Registered users are warned if they try to update, or delete catalogs or items that they do not own.

### Requirement

1. Oracle VM Virtual Box

Version 5.1.22 r115126 (Qt5.6.2) was used for this application.

2. Vagrant

Version 1.8.5 was used for this application.

3. Git Bash

### Install

1. Install Oracle VM Virtual Box

2. Install Vagrant

3. Download the zip folder

4. Unzip

### Start the application
1. Open Git Bash

2. Change directory to the vagrant folder location

3. Run vagrant using 

```
vagrant_up
```
**Note:** This step will take approx. 5 min
4. Log in vagrant

```
vagrant ssh
```
5. Change directory to vagrant folder

```
cd /vagrant
```

6. Change directory to the catalog folder

```
cd catalog
```

7. Run the app

```
python run.py
```

8. Go to localhost:5000/catalogs

### URL
- View all catalogs: root/catalogs
- Create a new catalog: root/catalogs/new

**Note:** These url below requires catalog id and/or item id

- Delete a catalog: root/catalogs/[catalog_id]/delete 
- Edit a catalog: root/catalogs/[catalog_id]/edit 
- View all items of one catalog: root/catalogs/[catalog_id]/items/[item_id]
- Create a new item of one catalog: root/catalogs/[catalog_id]/items/new
- Delete an item of one catalog: root/catalogs/[catalog_id]/items/[item_id]/delete
- Edit an item of one catalog: root/catalogs/[catalog_id]/items/[item_id]/edit
- View an item: root/catalogs/[catalog_id]/items/[item_id]
