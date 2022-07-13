# FINAL PROJECT KATALON API
## Authors

- Name : Aldiransyah Rizky Putra
- Code :  KSAT006ONL019

## Description

Final Project Katalon API describes how to perform automation testing on API. In this case, the API that will be used is Reqres API Website. This automation test consists of fifteen endpoint which are grouped according to HTTP Method. The Test Case will be entered into the test suite to be able to generate reports.

## Environment

- Katalon Studio
- Reqres API Website

## API Reference

Base URL : https://reqres.in/

## GET Method

### GET List Users

```http
  GET https://reqres.in/api/users?page=2
```
### GET Single Users

```http
  GET https://reqres.in/api/users/2
```
### GET Single User Not Found
```http
  GET https://reqres.in/api/users/23
```

### GET List Resource
```http
  GET https://reqres.in/api/unknown
```
### GET Single Resource
```http
  GET https://reqres.in/api/unknown/2
```

### GET Single Resource Not Found
```http
  GET https://reqres.in/api/unknown/23
```

### GET Delayed Response
```http
  GET https://reqres.in/api/users?delay=3
```

## POST Method

### POST Create
```http
  POST https://reqres.in/api/users
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| name  | String  |
| job  | String  |


### POST Register Successfull
```http
  POST https://reqres.in/api/register
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| email  | String  |
| password  | String  |

### POST Register Unsuccessfull
```http
  POST https://reqres.in/api/register
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| email  | String  |

### POST Login Successfull
```http
  POST https://reqres.in/api/login
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| email  | String  |
| password  | String  |

### POST Login Unsuccessfull
```http
  POST https://reqres.in/api/login
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| email  | String  |

## PUT Method

### PUT Update
```http
  PUT https://reqres.in/api/users/2
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| name  | String  |
| job  | String  |

## PATCH Method

### PATCH Update
```http
  PATCH https://reqres.in/api/users/2
```
Required body :

| Attributes  | Data Type |
| ------------- | ------------- |
| name  | String  |
| job  | String  |

## DELETE Method

### DELETE  delete
```http
  DELETE https://reqres.in/api/users/2
```
