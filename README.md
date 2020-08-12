# Flask-Rest-API-Example
 ### create and read stores, write and read items in stores
 
 #### 1. GET all the stores
 ``GET http://127.0.0.1:5000/store``
 #### 2. GET a specific store
 ``GET http://127.0.0.1:5000/store/<name>``
 #### 3. GET all items of specific store
 ``GET http://127.0.0.1:5000/store/<name>/item``
 #### 4. Create a store with name
 ```
 http://127.0.0.1:5000/store
 header: {Content-Type: application/json}
 body: {"name": "foods"}
 ```
 #### 5. Write items in store
 ```
 http://127.0.0.1:5000/store/<name>/item
 header: {Content-Type: application/json}
 body: {"name": "milk", "price": 5}
 ```
