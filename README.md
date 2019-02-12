# SoftEngProj2019
Project for Software Engineering 2019

# App (Name Pending)

## App Description
Delivery app for on-the-go ordering
- **Category:** Food/Dining 
- **Mobile:** Users can use location services to Locate nearest restauraunt to place their delivery, push-notifications for 30 minutes before restaurant closes in order to make sure deliveriesare made in time, User cancontact restaurant with any question/comment/concerns they might have
- **Story:** Customizable and savable profiles for quick and easy ordering to save time, list of foods to choose from and have delivered to users location
- **Market:** Persons looking to have hot and ready food delivered in a timely manner to their location, most likely busy/working/vehicle lacking persons in urban areas
-very large potential audience
-**Habit:** Users can access app everyday within store's open hours to make purchases and request deliveries
-**Scope:** small app with a login page, food profile page, list of deliverable foods/drinks/accessories, contact us page

---

## 1. User Stories (Required and Optional)

**required Must-have Stories**

* List of foods/drinks/accessories available
* Users can place request/purchase of foods/drinks/accessories

**Optional Nice-to-have Stories**

 * User can receive push-notifications for 30 minutes before the Location will close to ensure that they can come in time
 * Screen with services and information regarding allergies
 * Users can click on a photo of the menu option within its detailed screen for more information (calories, ingredients, etc).
 * User can browse through list of locations 
 * User can see information about the hours and location of each restaurant 
 * User can call the locations if they have any specific questions through the app
 
## 2. Screen Archetypes

 * Register
     * User can make an account to permanently store their information/prefrences
 * Login
     * User can login and use the app on different devices
 * Stream of locations and hours
     * User can see information about the hours and location 
     * User can browse through list of locations
     * User can call the locations if they have any specific questions through the app
 * Map 
     * User can use location services to see which restaurants are closer and place their orders
 * Steam of menu options at the selected dining hall 
     * User can automcatically see what options they have for the current meal at each location 
 * Profile: lists user's allergies and dietary needs/preferences/ prefered orders
     * User can enter their dietary preferences and needs into the app
     * User can quick select common orders they tend to place for time saving
    
## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * locations Feed
 * Profile
 * Meal Options Feed
 * Map 

**Flow Navigation** (Screen to Screen)

 * Register
     * => Profile, location Feed / Stream
 * Login
     * => Profile, location Feed / Stream
 * Dining Hall Feed / Stream
     * => Map, Menu Feed / Stream
 * Map
     * => location Feed, Menu Feed / Stream
 * Menu Feed / Stream
      * => location Feed, Profile to edit any preferences
 * Profile
     * => Login (if user logs out), location Feed
---
