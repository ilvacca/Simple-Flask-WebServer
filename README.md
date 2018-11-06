# Simple Flask API Web Server
### *From Plain text to JSON*

---

## 1. Info
This is a simple project from my Data Science course made by graduate students.

## 2. The Task
Create an API Web Server by using the Flask micro framework to display data from a Plain Text file in JSON format.
After receiving a request the server will respond with a JSON.

## 3. Routes (Endpoints)
These are the main Routes of the Web Server.

### Index
```
https://127.0.0.1/
```
This shows the main page with an "Hello world!" text.

### Name
```
https://127.0.0.1/name?name=Alessio&surname=Vaccaro
```
This shows a page with an your name and surname.

### ReadFile
```
https://127.0.0.1/readFile
```
This shows a JSON obtained through the *"my_model.py"* and its functions and the *"my_file.txt"* file.


## 4. Endpoint: "ReadFile"
The output of the ReadFile endpoint is:
```
[
	{
		"id":"1",
		"temperature":"12"
	},{
		"id":"2",
		"temperature":"42"
	},{
		"id":"3",
		"temperature":"15"
	},{
		"id":"4",
		"temperature":"23"
	}
	...
]
```
