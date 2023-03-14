
# GoLang CRUD API with Structs and Slices

CRUD API project using Golang, without a database. I use trucks and slices to store and manipulate data on the server, which allows for faster and more efficient operations. To handle incoming requests and responses, I utilize Gorilla mux to create five different routes: get all, get by id, create, update, and delete.  

I utilised essential Golang concepts, such as structs and slices, and demonstrate how to use them to store and access data. Additionally, I use JSON encoding and decoding to ensure that data is sent and received correctly between the server and client. For testing, PowerShell and Postman is used to make requests and receive responses.  

---

* Structs and slices to store data (Movies, Directors)
* JSON for encoding & Decoding data (through Postman)
* Create router with gorilla mux library, routes & functions for creating, updating, deleting, retrieving movies
* Test with http.ListenAndServe with LOCALHOST:8000

* Slice (Movies) stores different movies of struct type Movie
* Functions to get, create, update, delete JSON data by setting header content type and converting to GoLang struct form
* json.NewEncoder from encoding.json to encode response 
* Use mux package to access params in request
  
* Start with setting JSON content type, get access to params, loop over movies to perform an action  
* Use Postman to create API request
