//page1
> list of city
* http://localhost:1000/location

> restaurant with respect to city
* http://localhost:1000/restaurants?stateId=3

> list of quick search
* http://localhost:1000/mealType

//page2
> restaurants with respect to mealtype
* http://localhost:1000/restaurants?mealId=4
* http://localhost:1000/restaurants?stateId=2&mealId=4

> restaurants with respect to mealtype + cuisine
* http://localhost:1000/filter/1?cuisineId=2

> restaurants with respect to mealtype + cost
* http://localhost:1000/filter/1?lcost=400&hcost=800

//page3
> details of restaurant
* http://localhost:1000/details/1

> menu of restaurant
* http://localhost:1000/menu/2

//page4
> details of menu selected
* http://localhost:1000/menuDetails
{"id":[4,8,21]}

> place order
* http://localhost:1000/placeOrder

//page5
> list of all the orders
* http://localhost:1000/orders

> update orders details
* http://localhost:1000/updateOrder

> Delete orders
* http://localhost:1000/orders

C > Create (Post)
R > Read (Get)
U > update (Put)
D > Delete (Delete)