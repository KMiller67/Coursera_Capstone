# Coursera Capstone
Repository for the capstone project of the Applied Data Science Capstone course offered by Coursera

### 1.	Introduction/Business Problem – Best Pizza in Town
I started a new job in Rochester, MN at the beginning of this year and recently moved to the area. My wife and I love to try new restaurants and foods, but there’s one food that never seems to get old for us: Pizza. In every area I’ve ever lived, people seem to be on a search for the best pizza in town, however everyone has a different opinion. Since I’m living in a new area and haven’t tried many pizza places here yet, I thought it would be interesting to use user ratings from pizza restaurants to try and determine objectively where the coveted ‘best pizza in town’ can be found based on the subjective responses of Foursquare users.

I imagine I’m not the only one who finds myself in this situation. Searching for the ‘Best of (insert food of choice here)’ is something that nearly every consumer does, and this information could be leveraged by businesses for marketing or to better their product. For example, this could be used in a smartphone app where you enter the food you’re looking for and it produces a restaurant recommendation for you. With that in mind, the target audience could be anyone from a normal consumer to various kinds of businesses, including restaurants, tech businesses focused on providing recommendations tailored to their users.

### 2.	Data
I will be using data from the Foursquare API exclusively to help solve this problem. The Foursquare API has a multitude of location related data, but I’ll be primarily using the following:
*	Latitude and Longitude data for Rochester, MN and venues
*	Venue Name
*	Venue Category
*	Venue Rating
*	Venue Likes

I plan to use this data by using the latitude and longitude values of Rochester, MN and pizza venues to determine the venues within Rochester's city limits, and then use the venue category to filter down to pizza places in particular. I then will use the rating and number of likes for each venue to determine the best pizza place, where the higher the rating and number of likes for a given venue the better the pizza they serve is. Given the lack of available daily pulls allowed for my Foursquare Developer account, I’m limiting my analysis to include the data listed above. If I had more time and a better account tier, I’d consider looking into the number of dislikes and possibly tips provided by users to paint a better picture of what users think of the different pizza places. I plan to use the venue rating as my first determinant of the best pizza and town, and number of likes as a tiebreaker if necessary.
