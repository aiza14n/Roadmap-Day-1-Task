## Roadmap-Day-1-Task

# (HTTP 1.1) and (HTTP/2)


## What Is Meant By (HTTP 1.1) and (HTTP/2) ?


> HTTP/1.1:
Sequential Processing: Requests and responses are processed sequentially, meaning that the browser can only handle one request at a time. If a resource is requested, the browser has to wait until the server responds before it can request another resource.

> HTTP/2:
Multiplexing: HTTP/2 allows multiple requests and responses to be multiplexed over a single connection. This means that multiple resources can be requested and delivered simultaneously, improving the overall efficiency and speed of data transfer.



## What Is The Different Between (HTTP 1.1) And (HTTP/2) :

>> HTTP/1.1:
>- Sequential Processing: Requests and responses are processed sequentially, one at a time.
>- Header Inefficiency: Each request and response carries a set of headers, which can be large and redundant, leading to increased overhead.
>- No Built-in Compression: Content needs to be compressed separately, and without compression, data transfer may be slower.
>- No Server Push: The server cannot proactively send additional resources to the client without a specific request.


>> HTTP/2:
>- Multiplexing: Supports multiple requests and responses concurrently, improving data transfer efficiency.
>- Header Compression: Headers are compressed, reducing redundancy and lowering overhead.
>- Built-in Compression: Data can be compressed within the protocol, enhancing transfer speed.
>- Server Push: Allows the server to push resources to the client without explicit requests, reducing latency.



>Find the Blog link :link:=> https://medium.com/@ahizaan2005/title-the-internet-adventures-slow-postman-http-1-1-vs-quick-superhero-http-2-27204c07577b 
>>The above blog will be easier to understand about (HTTP 1.1) vs (HTTP/2). So, this is all about (HTTP 1.1) and (HTTP/2).

# OBJECTS AND ITS INTERNAL REPRESENTATION IN JAVASCRIPT

## What Is Meant by Object In JavaScrpit ?
 In JavaScript, objects are a fundamental data type that allows you to store and organize data. They are used to represent and manipulate real-world entities by bundling related properties and methods together.

## The internal representation of objects in JavaScript is based on key-value pairs.
> Here's a very simple explanation:
>> Key-Value Pairs:
 >- Objects consist of key-value pairs. Each key is a string or a symbol, and it is associated with a corresponding value.
 >- Values can be of various types: strings, numbers, booleans, other objects, functions, and more.
 ```javascript
// Example of an object with key-value pairs
let person = {
  name: "John",
  age: 25,
  isStudent: true
};
```
>> Accessing Values:
>- You can access the values of an object using the corresponding keys.
 ```javascript
 console.log(person.name);      // Output: "John"
console.log(person.age);       // Output: 25
console.log(person.isStudent); // Output: true
```
>> Adding and Modifying Properties:
>- You can add new properties or modify existing ones easily.
```javascript
person.city = "New York";
person.age = 26;

console.log(person.city); // Output: "New York"
console.log(person.age);  // Output: 26
```
>> Object Methods:
>- Objects can also have methods, which are functions associated with the object
```javascript
let car = {
  brand: "Toyota",
  model: "Camry",
  start: function() {
    console.log("Engine started!");
  }
};

car.start(); // Output: "Engine started!"
```
## In summary, objects in JavaScript provide a way to structure and organize data using key-value pairs. This simple key-value structure makes it versatile for representing a wide range of entities and their attributes in your code.

>Find the Blog link :link:=> https://medium.com/@ahizaan2005/understanding-objects-and-their-internal-representation-in-javascript-ce6180bd7a34
>>The above blog will be easier to understand about Objects And Its INternal Representation In Javascript  














