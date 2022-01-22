# delivery-app-sprint


Note: check the sprint planning project on [Jira](https://delivery-app-gfs.atlassian.net/jira/software/projects/DEL/boards/1/roadmap?shared=&atlOrigin=eyJpIjoiNmU3OWRhNTk0NTRhNDE0MDhhNmUyNWNiNjk1ZWY0ZWQiLCJwIjoiaiJ9) "open it using your @gazaskygeeks account"
### Scope

A restaurant wants to set up an online ordering and delivery service, so people do not have to ring up to order food.

-----

### User Stories:

#### As a user, I can :
- Browse all available meals on the menu page.
- Filter meals by their ingredients,[vegan/vegetarian/meatatarian], price, offers.
- Search on a meal by its name.
- See the ingredients of a specific meal.
- Specify the quantity of my order.
- Specify any additional options over the main order; extra fried potato/cheese/Coke.
- See national daily promotional/specials or local daily promotional/specials if exists.
- Cancel my order or any extra options.
- After placing my order; fill in my contact information such as; address, phone, name
- Fill in my address automatically via GPS or manually.
- Select either to get the order in person or to be delivered to my address.
- For in-person collection, I can see meal pick up time after placing my order.
- For in-person collection, I can see the directions to the shop on a map. 
- Select a payment method to be online or in/person.
- Rate & review the order and delivery service.


#### As a user with a vision disability, I can :
- Search on meals by voice
- Go to the shop via real-time voice navigation on the map 


#### As an admin, I can :
- Access the admin page and see all meals filtered in the dashboard based on their rate as default.
- Add or remove any meal.
- Add details about each new meal such as its ingredients
- See the number of orders for each meal.
- offer national daily promotionals/specials & local daily promotionls/specials.
- Read users reviews
- see the number of requested delivery service

------

### User Journey

**User who want to order**:
  - I can see a landing page guiding me to the menu page containing a list of available meals.
  - I can filter the meals based on their ingredients such as [vegan/vegetarian/meatatarian], their prices and the ones that have offers on.
  - I can see the top-rated meals at the top of the meals list.
  - If there are any promotional/specials I can see it like a flag on each meal card.
  - Each meal card has a photo with two buttons; order & read more.
    - By clicking on "read more" button, I can see a popup containing an info about its ingredients.
    - By Clicking on "order" button, I will be redirected to the order page.
  - In order page:
    -  I will be able to specify the quantity of my order.
    -  I can choose between picking up my order in person or via delivery service.
    -  I can enter my address, phone number. the address can be entered manually or automatically via permission to get your location. 
     - For in-person pickup, after hitting confirm button:
        - I can see the time to pick up my food and a map with directions from my current location to the shop.
        - Underneath it, I can choose my payment method; online payment or in-person. 
     - For delivery service, after hitting confirm button :
       - I can see an estimation time based on my location to deliver the food.
       - Underneath it, I can choose my payment method; online-payment or in-person.
  - once I pick up my order, I can rate and review the meal & service in general.  
  - For more help, there is a button at the footer to chat with an employee.

**User who is an admin**:
- There is a table that presents all meals, their prices, the number of orders for each meal, their ratings.
- By clicking on each meal; the admin will be able to delete it, change its price and read all the reviews related to this meal.
- In his/her dashboard; there will be a button to create a new meal with its details and another one to specify any new offers.
