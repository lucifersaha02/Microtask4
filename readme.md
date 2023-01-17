
# First Microtask
## It is an API which returns some dummy repository details and accepts a token for authentication.



## API Reference

#### Get all repos forecast/status

```http
  GET https://pom935.deta.dev/api/repos
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `header` | `token` | **Required**. [eg: akaza, pragyash, p0mp0m]|

#### Get particular repo

```http
  GET https://pom935.deta.dev/api/repos/:name
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `header` | `token` | **Required**. [eg: akaza, pragyash, p0mp0m]|







![App Screenshot](https://i.imgur.com/jefBxP9.png)

![App Screenshot](https://i.imgur.com/Hx1IMYD.png)
## Author

- [@akaza21](https://www.github.com/akaza21)


## Installation

```bash
    git clone https://github.com/akaza21/Microtask1

```
### `Navigation`
```bash
    cd Microtask1
```
### `Installation`



```bash
  npm i
```



### `Runserver`

```bash
  npm start
```






# Second Microtask
## It is a microservice which accumulates three different microservice APIs : ErrorHandler,Authentication and Visitor counter


## Installation

```bash
    git clone https://github.com/akaza21/MicroTask2

```
### `Navigation`
```bash
    cd Microtask2
```
```bash
    cd AuthAPI or cd ErrorHandler or cd ViewCounter
```
### `Installation`



```bash
  npm i
```



### `Runserver`

```bash
  npm start
```


## API Reference
### ErrorHandler

#### Get a random error message which is handled by a dummy ErrorHandler middleware

```http
  GET http://localhost:3000/api/error
```



### Authentication

#### Sign-up(Returns token )

```http
  POST http://localhost:3000/api/sign-up
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|


#### Log In(Returns token)

```http
  GET http://localhost:3000/api/sign-in
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | **Required**|
| `body` | `password` | **Required**|

#### Restricted route

```http
  GET http://localhost:3000/api/all-users
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `header` | `token` | **Required**|



### Visitor counter


```http
  POST http://localhost:3000/api/get-views
```



![App Screenshot](https://i.imgur.com/Q9WAUn5.png)

![App Screenshot](https://i.imgur.com/Hx1IMYD.png)
![App Screenshot](https://i.imgur.com/S1PqbnD.png)
## Author

- [@akaza21](https://www.github.com/akaza21)









# Third Microtask
## It is a microservice that takes the user's Latitude and Longitude as input and returns their  current address. It can also be used to get the Latitude and Longitude of a location by filling out the address.


## Installation

```bash
    git clone https://github.com/akaza21/MicroTask3

```
### `Navigation`
```bash
    cd Microtask3
```

### `Installation`



```bash
  npm i
```



### `Runserver`

```bash
  npm start
```


## API Reference


#### Takes the user's location and returns their address

```http
  GET https://twmkv2.deta.dev/get-address
```








![App Screenshot](https://i.imgur.com/3upQZmH.png)

## Author

- [@akaza21](https://www.github.com/akaza21)







