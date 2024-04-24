# Shop-Manoa
[Shop Manoa's Team Contract](https://docs.google.com/document/d/1cJpwAVo2HtDnGPQh8G5f4IqFMvtsIkIU4RTED5MFBb0/edit?usp=sharing)

## Table of contents
* [Overview](#overview)
* [Features](#features)
* [Team](#team)
* [Mock-up Ideas](#mock-up-ideas)
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

## Mock-up Ideas
  * [Landing page](#landing-page)
  * [User home page](#user-home-page)
  * [Admin home page](#admin-home-page)
  * [User-Profile page](#user-profile-page)
  * [List-Profile page](#list-profile-page)
  * [Categories page](#categories-page)
  * [Category page](#category-page)
  * [Create item page](#create-item-page)
  * [Make offer on item page](#make-offer-on-item-page) 
  <!-- * [Notify admin page](#notify-admin-page) -->
  * [User report page](#user-report-page)

### Landing page
The landing page is presented to users when they visit the top-level URL to the site.
![Screenshot 2024-04-23 at 7.30.19 PM.png](doc%2FScreenshot%202024-04-23%20at%207.30.19%20PM.png)

### User home page
Once logged in, the User home page displays an overview of the user's recently viewed items and/or favorite listings, options to create new items, and display of messages/notifications about posted items.
![Screenshot 2024-04-23 at 7.32.48 PM.png](doc%2FScreenshot%202024-04-23%20at%207.32.48%20PM.png)

### Admin home page
Once logged in, the Admin home page allows the admin to manage and moderate user accounts, items and services, and issues.
![Screenshot 2024-04-23 at 7.33.21 PM.png](doc%2FScreenshot%202024-04-23%20at%207.33.21%20PM.png)

### User-Profile page
The User-Profile page displays user's information (username, profile picture, and bio) and posted item buy/sell with status.
![Screenshot 2024-04-23 at 7.33.57 PM.png](doc%2FScreenshot%202024-04-23%20at%207.33.57%20PM.png)

### List-Profile page
The List-Profile page displays the profiles of all registered users on Shop-Manoa. Additionally, it provides the functionality to view and rate these profiles.
![Screenshot 2024-04-23 at 7.34.20 PM.png](doc%2FScreenshot%202024-04-23%20at%207.34.20%20PM.png)
![Screenshot 2024-04-23 at 7.34.58 PM.png](doc%2FScreenshot%202024-04-23%20at%207.34.58%20PM.png)
![Screenshot 2024-04-23 at 7.35.21 PM.png](doc%2FScreenshot%202024-04-23%20at%207.35.21%20PM.png)

TODO: Develop a search feature that allows users to easily find other users.


TODO: Implement a ‘View Profile’ button for each listed profile, which will direct users to the respective User-Profile Page.

### Categories page
The Categories page provides a list of categories of items and services for users to select from.
![Screenshot 2024-04-23 at 7.36.06 PM.png](doc%2FScreenshot%202024-04-23%20at%207.36.06%20PM.png)

### Create item page
The Create item page is a form where users can create an item or service to be put up for sell.
![Screenshot 2024-04-23 at 7.36.54 PM.png](doc%2FScreenshot%202024-04-23%20at%207.36.54%20PM.png)


<!-- ### Notify admin page
The Notify admin page is a form for users to report any suspicious or inappropriate activities. -->

### User report page

![Screenshot 2024-04-23 at 7.37.49 PM.png](doc%2FScreenshot%202024-04-23%20at%207.37.49%20PM.png)
![Screenshot 2024-04-23 at 7.38.12 PM.png](doc%2FScreenshot%202024-04-23%20at%207.38.12%20PM.png)

- Users can report inappropriate content or users.
- On each post or user account page, a button for reporting will be displayed.
- Once you click the button, you are directed to the report form page.
- What the form asks you? 
  - What content or user you felt inappropriate.
  - How do you categorize the content or user? (e.g. spam, scam, harassment, etc.)
- Once you submit the form, the data is stored into the database to be checked by admin user.

## Extra TO-DOs

- Implement a chat system:
  - Instead of an "offer" system, users will be given the chance to direct message other sellers, giving users the opportunity to try and haggle to a lower price, determine how the payment style, or even ask more questions about the item/service that is being sold
  

- More appealing site:
  - As of right now we are much more focused on getting the basics laid out for our site. Though we have much more to do when it comes down to make our site look much more "beautiful".

## Developer Guide
WIP

## Development History
<h4>Deployment</h4>
Shop-Manoa is deployed to [Digital Ocean](https://shop-manoa.com/)
<h4>Milestone 1: Mock up Development</h4>
Milestone 1 is managed using [Shop-Manoa GitHub Project Board M1](https://github.com/orgs/shop-manoa/projects/1)
<h4>Milestone 2: Deployment</h4>
Milestone 2 is managed using [Shop-Manoa GitHub Project Board M2](https://github.com/orgs/shop-manoa/projects/2)

[![ci-shop-manoa](https://github.com/shop-manoa/shop-manoa/actions/workflows/ci.yml/badge.svg)](https://github.com/shop-manoa/shop-manoa/actions/workflows/ci.yml)
<h4>Milestone 3: </h4>
Milestone 3 is manged using [Shop-Manoa GitHub Project Board M3](https://github.com/orgs/shop-manoa/projects/4)
