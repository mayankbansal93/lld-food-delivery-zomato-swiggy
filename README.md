# lld-food-delivery-zomato-swiggy
Low Level Design of Food delivery app - Zomato, Swiggy, UberEats

# Requirements
1. Restaurant can register themselves.
2. User can create, update, delete, get their profiles.
3. User can search for the restaurant using restaurant name, city name.
4. Restaurant can add, update foodmenu.
5. User can see the foodmenu. User can get the food items based on Meal type or Cuisine type.
6. User can add/remove items to/from the cart. User can get all the items of the cart.
7. User can place or cancel the order. User can get all the orders ordered by him/her.
8. User can apply the coupons. User can get the detailed bill containing tax details.
9. User can made a payment using different modes of payment - credit card, wallet, etc.
10. Delivery boy can get all the deliveries made by him using his Id.
11. User can get the order status anytime. Success, Out for Delivery, Delivered, etc.

# Services
* RestaurantService
* UserService
* FoodMenuService
* CartService
* OrderService
* PricingService
* PaymentService
* DeliveryService
