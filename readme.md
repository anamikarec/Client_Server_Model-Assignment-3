#### Use the following API
#### https://jsonplaceholder.typicode.com/
#### make a get request using the /users endpoint and retrieve the 3rd user
- Request:
```js
    curl  https://jsonplaceholder.typicode.com/users/3
```
- Response:
```js
   {
    "id": 3,
    "name": "Clementine Bauch",
    "username": "Samantha",
    "email": "Nathan@yesenia.net",
    "address": {
        "street": "Douglas Extension",
        "suite": "Suite 847",
        "city": "McKenziehaven",
        "zipcode": "59590-4157",
        "geo": {
        "lat": "-68.6102",
        "lng": "-47.0653"
        }
    },
    "phone": "1-463-123-4447",
    "website": "ramiro.info",
    "company": {
        "name": "Romaguera-Jacobson",
        "catchPhrase": "Face to face bifurcated interface",
        "bs": "e-enable strategic applications"
    }
    } 
```
#### store into a file called 3.txt
- Request:
```js
    curl -O https://jsonplaceholder.typicode.com/users/3
```
- Response: ```response in another file named 3```