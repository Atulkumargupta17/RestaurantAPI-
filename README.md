# RestaurantAPI-
This Service provides api's related to restaurants

1. Create A WebAPi Project
2. Create Model Classes i.e., Restaurants and Reviews
3. Add DbContext Class i.e., ResturantApiContext : DbContext
4. Add ConnectionString in appsetting.json class
5. Add Service for database interactions in ConfigureServices() which is in Startup class
6. Create a SeedData class to fill some dummy data by using the ResturantApiContext class which we have just created above
7. Check the functionality by running your application 
8. Now Create a Controller Named RestaurentController : ControllerBase
9. Decorate this RestaurentController  class by [ApiController] attribute
10. Create a variable named "context" of type ResturantApiContext type
11. Create a parameterized contructor in RestaurentController and pass ResturantApiContext as parameter
12. Create a Method GetRestaurant() to get the list of restaurent
