# HTTP Parser Code Kata
Write a program that parses an http response packet and:
- Returns the string representation of the response body
- Determines if the response was successful

## Test Data 1
```c
"HTTP/1.1 200 OK\nContent-Type: application/json\nContent-Length: 13\nConnection: close\n\n{\"foo\":\"bar\"}"
```
## Test Data 2
```c
"HTTP/1.1 200 OK\nContent-Type: application/json\nContent-Length: 15\nConnection: close\n\n{\"fizz\":\"buzz\"}" 
```
## Test Data 3
```c
"HTTP/1.1 400 Bad Request\nContent-Type: application/json\nContent-Length: 23\nConnection: close\n\n{\"error\":\"bad request\"}" 
```