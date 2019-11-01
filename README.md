You will create a RESTful API for an online recipe app using Express, Node, and MongoDB.  Your Express app will be served up by a Node server running on port 3000, and it will be connected to a MongoDB Atlas cluster.  You will be implementing the following endpoints:

GET  /api/recipes  — returns all recipes in database
GET  /api/recipes/:id  — returns the recipe with the provided ID from the database
POST  /api/recipes  — adds a new recipe to the database
PUT  /api/recipes/:id  — modifies the recipe with the provided ID
DELETE  /api/recipes/:id  — deletes the recipe with the provided ID

Deliverables
You will provide the URL to a Git repo containing your project.  Your project will contain at least:

a server.js file containing your Node server
an app.js file containing your Express app
a package.json file containing all necessary dependencies
a models folder, containing a Recipe model (Mongoose)
