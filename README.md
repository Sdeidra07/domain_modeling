# _**Domain Modeling**_

## [Photogram Database Exercise](https://docs.google.com/spreadsheets/d/104IDD206ubqloGZbjtSUAYwfOsFpiC6bQ3C11Re57M4/edit#gid=0)

## Very Best

> ### [Target](http://very-best-demo-pr-3.herokuapp.com/)
>
>### Very Best User Stories
>#### As a user, I should be able to...
>
>#### On the Dishes page
>
> - See the bucket list of dishes
> - See which venue I have bookmarked for each dish, or choose one if I haven't
> - Filter dishes by cuisine
> - Search dishes by name
> - Click a link to add a venue if it doesn't already exist
>
>#### On the Dish Details page
>
> - Bookmark a new venue for that dish
> - See the venues I've bookmarked for that dish in the past
>
>#### On the new venue page
>
> - Add a new venue
>   - Name
>   - Address
>   - Neighborhood (optional)
>
>#### On the Venues page
>
> - See a list of all venues that I've bookmarked
> - Filter venues by neighborhood
> - Search venues by bookmarked dish
>
>#### On the Venue Details page
>
> - See which dishes I've bookmarked at a venue
> - Add a new bookmarked dish to the venue
> - See what others have bookmarked at the venue.
>
>### Notes
>>
> - Initially, users can't add dishes; we, the site admins, will set up the bucket list of dishes.
> - Initially, users will all use the same big list of venues. If and when the dropdown gets too big and unwieldy, we'll figure something else out.


## Yelp Lite User Stories

>This is a simplified version of Yelp. Only worry about user stories described here.
>
>### As a user, I should be able to...
>
>#### On the Restaurants page
>
> - See a list of restaurants
> - Search by name
> - Filter by tag
> - Narrow by average rating
> - See number of reviews
>
>#### On the Restaurant Details page
>
> - See the restaurant's:
>   - description
>   - address
>   - website
>   - cover photo (only one per restaurant)
> - See a list of reviews. For each one:
>   - the user who left it (first name, last initial)
>   - how many stars
>   - content
>   - photos (there could be multiple for each review)
>
>#### On the User Profile page
>
> - number of reviews
> - average rating given
> - list of reviews
>
>### When you've completed the above...
>
>- What if we start selling the ability for restaurant owners to leave responses to reviews? How would that affect our domain model? A single user should be able to "own" multiple restaurants, and a restaurant can have multiple "owners".

## Airbnb Lite User Stories

>This is a simplified version of Airbnb. Only worry about user stories described here. Don't worry about things like payment, etc. Assume for now that this is only a platform that facilitates communication.
>
>### As a host, I should be able to...
>
> - Add a listing
>  - Title
>  - Private room or entire home
>  - Photos (taken by host)
>  - Description
>  - Number of bedrooms
>  - Number of bathrooms
>  - Number of beds
>  - Max occupants
>  - City
>  - Neighborhood
>  - Policies (check-in time, house rules, etc)
>  - Default price per night
> - Specify which nights the unit is available
>  - Price (if different from default)
> - Respond to messages from guests
> - Review and accept requests
>  - See past reviews of the requester (both as guests and of listings where they were host)
>  - See a message history between myself and the requester
> - Leave a review of a guest
>  - Overall rating (1-5)
>  - Which booking this review is for (we'll keep this private, though)
>  - Body (freeform text)
>
>### As a guest, I should be able to...
>
> - Browse listings
>  - See past reviews of the listing, and other listings by the same hosts, and of the host when they were a guest
> - Bookmark listings
> - Send a message to the owner of a listing
> - See the nights a listing is available for
> - Send a request for available nights
>  - Include an introduction of myself
> - Not send a request for unavailable nights
> - Leave a review of a booking
>  - Accuracy (1-5)
>  - Communication (1-5)
>  - Cleanliness (1-5)
>  - Location (1-5)
>  - Check In (1-5)
>  - Value (1-5)
>  - Body (freeform text)
