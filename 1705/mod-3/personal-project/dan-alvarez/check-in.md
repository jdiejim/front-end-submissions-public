## Project Name:

FoodGrader/FoodFacebook

#### Check In: 1
#### Status-
* Set up create react app, set up redux, with containers, reducers, actions and store.
* Was not able to understand the API fetch. It is using a curl. I tried to read up on it and I haven't understood what they need me to do just o make the fetch cal work.
* Tried to hook up store, however it is hard to know if it is working since I am not making an API call yet.


#### Project Pitch

* -Set up a database for a user login.
* -Fetch API of resturants based on name/cuisine search or by location.
* -Display grades/ratings, location/directions (or link to googlemaps with that address already inputed)
* -Implement router, to route to faves page, to go to page, individual profile pages, individual resturaunts card page.
* -Add a favorites array that is saved in the database, sort that array based on rating, display on a profile page in order of best to worst.


*Add ons
* -Get grades from yelp and health department
* -Can friend other users.
* -Friends can see which places you liked on your profile page.
* -Invite friends to eat (via instant messenger?)

#### Stack:
* Redux
* React-router-redux
* Express


#### APIs:

[zomato](https://developers.zomato.com/api)
[fda](https://www.data.gov/consumer/introducing-openfda-food-drug-administration)

#### Wireframes

[wire frame pages](https://app.moqups.com/danalvarez5280@gmail.com/0Nnqb5gJTp/edit/page/a344298be)

#### Waffle & Github

[waffle](https://waffle.io/danalvarez5280/foodgrader)

#### Order Of Attack

* Get initial API call working.
* Map over info and diplay cards for each information


#### MVP

* App can find restaurant in area, can dive directiosn to said restaurants, and shows grades of restaurants.
* User can sign in and see favorites list, can see to do list, can see profile.
* User can search for friends, can find friends and see their favorites and to dos.


#### Nice To Haves

* Profile page is interactive witn add friend buttons.

#### Biggest Challenges

* Hosting backend that will support user information.

#### Instructor Notes

#### Deliverables for next checkin:



# Teacher Notes:

Dan A:

Name: Food Grabber

Description:
* An app that lets people search restaurants, save favorites, save to-dos, find friends and message friends about restaurants

MVP:
* Ability to search with a map
* Find restaurants and save to favorites
* To-Do - opens calendar event or adds ability to track date/notes
* Login/Profile functionality
* Data storage via firebase
* Restaurant scorecard showing data from multiple sources
    * E.g. FDA, yelp, user-submitted

Backend:
* Firebase

Auth:
* Yes

API:
* Open FDA
    * Get scores of restaurants
* Google map API
* Zomato
    * Search for restaurants
    * Ratings, location, quisine type, hours

Extensions:
* Ability to search users and create direct message
* Adding friends to friend list


Meeting 2:
* Has access to API
    * Can’t make requests with API key, documentation is shitty
* Can’t get ConnectedRouter working, says it is undefined
