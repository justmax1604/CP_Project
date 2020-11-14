Original App Design Project
===

# Locally

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
The app serves as an access point to users to post their offered products and services and see what products and services are offered within their local community. Local comunity is identified using the location permission and a set radius. People can exchange goods and services (either paid or free) between themselves. The app provides a more transparent and trustworthy service and the speed of execution, as the users are located within one community.

### App Evaluation

- **Category: Productivity, Social**
- **Mobile: The app is mobile oriented as it would utilize maps, location, camera, push notifications (at least). Additionally, people spend more time on their mobile devices then on laptops etc.**
- **Story: The value of the app is that users are able to exchange goods and services in their communities effectively and efficiently.**
- **Market: Any person of legal age can become a user, as it can serve different needs of different people. Would like to target the US communities at first.**
- **Habit: The app will likely be accessed daily to keep up with the exchange of goods and services in the community and for the users to post their own.**
- **Scope: The MVP that we would like to build should be enough to assess the potential of the app. It might be challenging to implement all functionality by the end of the program.**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can sign up using social account (Facebook, Mircosoft etc.)
* User can log in to access the timeline and profile
* User can post the product or a service to the timeline
* Users can chat about a product or service with a chat window
* Users are able to see the timeline in their local community only
* Users are able to remove/mark gone products or services offered
* There is a navigation bar with My Community and My Stuff
* Users are able to see details about product or service on click

**Optional Nice-to-have Stories**

* Enhanced profile editing options
* Push notifications about what is happening in the community etc.
* History of user's items/ services
* Expiration dates on posts
* Posts that support claiming by multiple users (e.g. someone needs more than one person)

### 2. Screen Archetypes

* Login
* Sign up
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information to be properly matched with another person.
* Messaging Screen - Chat for users to communicate (direct 1-on-1)
   * Upon selecting product or service, users are matched and message screen opens
* Make a post for product and service screen
* Profile Screen
* Community Timeline Screen
* Settings screen
* Post details screen

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Community timeline
* My stuff
* Profile

**Flow Navigation** (Screen to Screen)

* Forced Log-in -> Account creation if no log in is available
* My Stuff/Timeline -> Add a product or service
* Timeline -> Post Details -> Reply to post -> Message user
* Profile -> Text field to be modified.
* Settings -> Toggle settings


## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
