# Ecommerce_-API
Ecommerce API
 Using the Intermediate API Folder Structure Example:
 . Create an API for CRUD operations for products using the following item structure:
 {
 id: Unique, // MongoDB generated
 name: String,
 description: String,
 category: String,
 price: Number,
 dateCreated: Date // Set default date to Date.now
 }
 . Set up your code using models, controllers, routers, and config
 . How to do this?
 - Create a product Mongoose schema using the structure pattern above in your model folder.
 - Create a controller folder.
 - In your controller folder, create a product.js file and write your product
 endpoints with the router method.
 - Import the router into your index.js and use the app.use() method to set the base route
