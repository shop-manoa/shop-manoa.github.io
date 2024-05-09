# Shop-Manoa
[Shop Manoa's Team Contract](https://docs.google.com/document/d/1cJpwAVo2HtDnGPQh8G5f4IqFMvtsIkIU4RTED5MFBb0/edit?usp=sharing)

## Table of contents
* [Overview](#overview)
* [Features](#features)
* [Team](#team)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)

## Overview
The project, tentatively named "Shop-Manoa", aims to address the rapid turnover of goods and services among students at the University of Hawaii at Manoa (UHM). The primary goal is to create an effective marketplace for campus-specific items, facilitating their recycling and reuse.

Shop-Manoa allows UHM students, faculty, and staff to buy and sell student-related goods and services. This platform is similar to Craigslist, with key differences including the requirement for UH credentials for all users, no anonymity, and the expectation of on-campus transactions.

## Features
* **Roles** (users, admin): users can buy or sell goods and services, while administrators monitor user behavior and manage categories and other functionalities.
* **Categories**: feature broad categories for goods and services.
* **Notifications**: users can opt to receive information via text message.
* **Alerts**: users can set up alerts for specific items they are looking for and will be automatically notified when such items are listed for sale.
* **Photos**: supports upload of photos.
* **Complaints**: users can report inappropriate content or users.

## Team
Shop-Manoa is designed, implemented, and maintained by [Javin Solmirin](https://javinsol.github.io), [Isaac Segawa](https://imths.github.io), [LaToya Gonzales](https://latoyagonzales.github.io), [Ayumu Yamagishi](https://000Aym612.github.io), [Jayrell Allen Ballesteros](https://Kyj1n.github.io), and [Xiaokang Chen](https://XiaoKChenEDU.github.io).

## User Guide
  * [Landing page](#landing-page)
  * [User Profile page](#user-profile-page)
  * [Create item page](#create-item-page)
  * [Items page](#items-page)
  * [List Profile page](#list-profile-page)
  * [Categories page](#categories-page)
  * [Report page](#report-page)
  * [Admin home page](#admin-home-page)

### Landing page
The Landing page is presented to users when they visit the top-level URL to the site, and includes a brief description of Shop Manoa, as well as featuring a random item that someone has listed on the site. Once logged in, users will have access to the pages: ["My Profile"](#user-profile-page), ["Create Item"](#create-item-page), ["Items"](#list-items-page), ["List Profile"](#list-profile-page), and ["Categories"](#categories-page). Admins will have access to an additional page, ["Admin Home"](#admin-home-page).
![Screenshot 2024-04-23 at 7.30.19 PM.png](doc%2FScreenshot%202024-04-23%20at%207.30.19%20PM.png)

### User Profile page
The User Profile page displays user's information (profile picture, full name, and bio) and the items that they have listed on the Shop Manoa site. Users have an option to edit their profile by changing their profile picture and bio. Users also have the option on each of their listed items to edit their description and price, as well as remove/take down their listings. Admins are able to access items through this page and are given authority to remove/take down any item that they feel is inappropriate or that has been reported by other users.
![Screenshot 2024-04-23 at 7.33.57 PM.png](doc%2FScreenshot%202024-04-23%20at%207.33.57%20PM.png)

### Create item page
The Create item page is a form where users can create an item or service to be put up for sell. Required information includes a(n): title/name, image, description, category, condition, and desired price for the product being listed. The form handles file uploads in order for users to be able to upload an image of their item.
![Screenshot 2024-04-23 at 7.36.54 PM.png](doc%2FScreenshot%202024-04-23%20at%207.36.54%20PM.png)

### Items page
The Items page displays all currently available items that any user has put up on the Shop Manoa site as a listing. Each item has the options to view a popup of an overview of the item, favorite the item, view the profile of the owner, and make a report of a posting. Favorited items stay at the top of the Items page and remain there until un-favorited or removed from the site. The view profile button attached to each item takes the user to the owner of the item's profile page, where they can see the rest of that other user's listings.

### List Profile page
The List Profile page displays the profiles of all registered users on Shop-Manoa, and gives the option to view each person's profile page. Additionally, it provides the functionality to view and rate these profiles, as well as report the user themselves. The users' overall rating is displayed as an average located directly underneath their name.
![Screenshot 2024-04-23 at 7.34.20 PM.png](doc%2FScreenshot%202024-04-23%20at%207.34.20%20PM.png)
![Screenshot 2024-04-23 at 7.34.58 PM.png](doc%2FScreenshot%202024-04-23%20at%207.34.58%20PM.png)
![Screenshot 2024-04-23 at 7.35.21 PM.png](doc%2FScreenshot%202024-04-23%20at%207.35.21%20PM.png)

### Categories page
The Categories page provides a list of the different categories of items and services that Shop Manoa currently supports. By clicking on a specific category on the page, a user is redirected to the page corresponding with the category clicked that displays all the listings that fall under said category.
![CategoriesPageUpdated.png](doc%2FCategoriesPageUpdated.png)
![image.png](doc%2Fimage.png)

### Report page
The Report page provides users the opportunity to send a report of any content or user that one deems inappropriate to the admins of Shop Manoa. The option to access the form is provided on each item listing and the user profiles displayed on the List Profile page. The form asks for: the first and last name of the user or owner being reported, the name/title of the item/user that is being reported, the type of report it is for (post/user), the category of the misconduct, and any other details that one might want to add into the report. Once submitted, admins are able to see a full list of reports on their respective home page, where they can then decide whether or not to remove an item from the Shop-Manoa site.
![Screenshot 2024-04-23 at 7.37.49 PM.png](doc%2FScreenshot%202024-04-23%20at%207.37.49%20PM.png)
![Screenshot 2024-04-23 at 7.38.12 PM.png](doc%2FScreenshot%202024-04-23%20at%207.38.12%20PM.png)

### Admin home page
Once logged in, the Admin home page allows admins to view another list of all the registered users of Shop-Manoa, to give them easier access to an individual's profile page. Admins are also able to see the full list of open reports that have been submitted. The report list includes all of the information submitted in the report form that was filled out, as well as the user that submitted the report.
![Screenshot 2024-05-08 at 10.22.38 PM.png](doc%2FScreenshot%202024-05-08%20at%2010.22.38%20PM.png)

## Community Feedback
Yuta Shimoe:
I used making a profile, editing a profile, creating an item, and reporting functions.
making a profile, editing a profile: I thought it was good, but I felt if it has sections to describe your major, expected graduate year, etc. That would look nicer. 
creating an item: creating an item section is really nice, once I submit a creating item form, it shows in the Items page with brief descriptions of items. That would help me understand the info of product easily.
reporting functions: My friend told me if I report a user, he can see the result on an administrated page, but I am not sure how that actually works since I cannot see anything from non-administrated user. But, the functions and appearance were really cool. If the name(or title) of a reported user (or post) are automatically fulfilled, that would be more cool.

Aaron Kim:
I was able to sign up and make an account using my UH email, create an item listing for others to see, and see other users' items and profiles.
Making a profile and editing: It was functional and I was fully able to add and change everything that I would normally want to.
Creating an item: Very functional and nice that all the pages would automatically update with all the data that we just put into the site. Every part of submitted data was able to populate their corresponding areas.

Paul Ho: 
I created a profile and edited my information, and created an item to sell on the website.
Making a profile and editing: Registering and creating a profile to log in was very easy, but I couldn't edit my profile picture because of some browser problems.
Creating an item: I was able to easily create an item on the website and then view my profile in order to delete it. It was nice that the page updated without having to refresh to get rid of my deleted items.

Daniel Chong:
I used this website to create an account/profile and upload an item to sell to other Manoa students.
Creating a profile and editing profile: It was very easy for me to make an account; in fact, it took less than a minute! Upon creating my account, it gave me an option to edit my profile which was very helpful.
Creating an item:
It was a really simple process to create an item to sell on the website. The prompt was very easy to understand and follow. I decided on selling my funny dog. The website created the listing instantly, with no unnecessary delays which I am thankful for since I want to get rid of this dog ASAP. Just kidding of course. Anyways, the site was easy to use as it seemed very user-friendly.

Caleb Chang: I was fully able to sign up and create an account using my name and UH email, and create an item to be listed and for others to see, as well as see all of the data on the site.
Making a profile and editing: It was easy to register and make a profile to log into the site and neat how the site supported file uploads of images for both profiles and items. Also nice how a popup appeared to edit my own profile and change my profile picture and bio.
Creating an item: It was easy to fill out the form to create a listing and nice how there were dropdowns for categories and condition, as well as only accepting number values for price. It was cool to see the page refresh automatically when removing one of the items I put up as well.

## Developer Guide
### Downloading, Installing, & Running the Project
1. Navigate to [our GitHub repository](https://github.com/shop-manoa/shop-manoa)
2. Clone our repository to your local machine, through GitHub Desktop or your preferred method
3. Install Meteor
4. Open up a terminal
5. Navigate to the cloned project app/ directory on your machine via 'cd'
6. Run 'meteor npm install' to install all dependencies
7. Run 'meteor npm run start' to start up the project
8. Open up a browser and navigate to http://localhost:3000/ (or click on the provided link in the terminal)

### Modifying
1. Use 'git checkout main' to get onto the main branch on your machine
2. Use 'git pull' to make sure your main is up to date with the project
3. Use 'git checkout -b issue-XX' where XX is replaced with the issue number you are working on to create a new branch from main that you can work on
4. Make any changes needed and make sure everything still runs and passes any tests before pushing
5. Use 'git add .' to add all changed files to git
6. Use 'git commit -m "..."' replacing ... with a short message of what your commit is doing
   a. Can also do this through GitHub Desktop
7. Publish your branch through GitHub Desktop
8. Create a new Pull Request on GitHub to check everything and manage merge conflicts
9. Once everything is confirmed and passes, confirm merge onto main

## Development History
<h4>Deployment</h4>
Shop-Manoa is deployed to [Digital Ocean](https://shop-manoa.com/)
<h4>Milestone 1: Mock up Development</h4>
Milestone 1 was managed using [Shop-Manoa GitHub Project Board M1](https://github.com/orgs/shop-manoa/projects/1)
<h4>Milestone 2: Deployment</h4>
Milestone 2 was managed using [Shop-Manoa GitHub Project Board M2](https://github.com/orgs/shop-manoa/projects/2)
<h4>Milestone 3: </h4>
Milestone 3 is managed using [Shop-Manoa GitHub Project Board M3](https://github.com/orgs/shop-manoa/projects/4)

[![ci-shop-manoa](https://github.com/shop-manoa/shop-manoa/actions/workflows/ci.yml/badge.svg)](https://github.com/shop-manoa/shop-manoa/actions/workflows/ci.yml)
