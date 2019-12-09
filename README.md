![ga_cog_large_red_rgb](https://cloud.githubusercontent.com/assets/40461/8183776/469f976e-1432-11e5-8199-6ac91363302b.png)

# Software Engineering Immersive: Project 2

The second project for the GEneral Aasembly Software Engineering Immersive course. This was a pair programed React based website, created within a 48hr timeframe.

---

# Scran & Screen

Using  React along with 2 public APIs, we set out to create a website with which the user could search for restaurant in any given area. Once a restaurat was selected we would also present the user with the listings for the geographically closest cinema on the day in question.

## Built With	

		* HTML5
		* CSS3
		* React
		* Axios

## Deployment

The site was deployed using Heroku and can be found here:

https://scran.herokuapp.com/

## Getting Started

Use the clone button to download the website source code. From the root directory type 'npm run serve' in the terminal. The project wil run on localhost:8000, and wil be viewable on any web browser.

## Website Structure

The site is comprised of three main screens; the home screen, the restaurant index, and then the restaurant/cinema show screen.

Upon entering the site the user the Home screen will prompt the user to enter a destination in which they would like to find a restaurant. Once entered ths will trigger a drop down menu of matches to the search term, for the user to select from. The search functionality is all handled by the Zomato API, which will return a specified number of matches based on a search term passed back to it. 

Once a selction has been made the user wil be taken through to restaurant index page. This page shows the top 10 rated restaurants for the location selected by the user, along with some basic information (rating out of five, location and contact details).

When one of these is selected the user will be taken to the final screen of the site, which shows the detailed restaurant information along with the listings for the nearest cinema. This is ascertained by using the longitude and lattitude information that is returned by the Zomato API and passing it over to the Cinelist API.


## Challenges and future improvements

The main issue we came across when creating the app was that half way through the project the cinema API we were using shut down, and removed all of their information. This was particularly frustrating as without it a major part of the sites functionality was removed. As it was only a 48 hour project weren't left with any time to source a new API that would work in the same way, so we decided to push on with what we had and substitute in dummy data in order to illustrate how the app would have worked.

Given more time, we would have also finnessed the layout and styling of the site and added in error handling for the forms.

## Author

Matt Wilkie- First Project
Link to portfolio here: matthewwilkie.com