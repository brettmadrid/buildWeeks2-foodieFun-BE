# buildWeeks2-foodieFun-BE
Backend Architect 

MVP for FoodieFun
1. An on-boarding process for a user.
2. Ability to easily create and post a menu item review(restaurant name, restaurant type (italian, mexican, fast food, etc.) menu item name, photo of your order, price, food rating (could use 5 star method or other), other comments, your wait time, date of visit). Hitting submit adds item to the homepage. 
 3. Ability to easily edit / delete a review. Deleting removes from homepage. 
 4. Homepage to see a grid of all your recent menu item reviews.  Can filter by restaurant, price, food type (mexican, italian, dessert, etc.), date visited and your rating. 


Stretch: Add a social aspect. You can friend other users, and see what they order frequently or rate the highest at places new and old. 

Tables Needed for Foodie Fun:

USERS
username: string,
password: string

FOOD_REVIEW
restaurantName: string,
photo: string,
foodName: string,
foodType: string,
comments: string,
rating: number,
price: number,
date: string,
restaurantInfo: string

Database Helpers:
get
delete
post
update
getByFoodType
getByPrice
getByRating

