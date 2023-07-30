# Local API Login

## POST `/api/login/Basic`

Login and retrieve a Local Tesla API token. Token will need to be used as a Bearer Token on all Local API requests.

### Fields

| Field    | Type             | Example        | Description                         |
| :------- | :--------------- | :------------- | :---------------------------------- |
| username | String, required | customer       | The login type.                     |
| email    | String, required | elon@tesla.com | The email for the Tesla account.    |
| password | String, required | mySolarSystem  | The password for the Tesla account. |

### Request Body

```json
{
    "username": "customer",
    "email": "elon@tesla.com",
    "password": "mySolarSystem"
}
```

### Response Body

```json
{
    "email": "elon@tesla.com",
    "firstname": "Tesla",
    "lastname": "Energy",
    "roles": [
        "Home_Owner"
    ],
    "token": "ad5_IEbcuDyPoe5QQDduZpaMTUb1pYNMB5epIZ6EjpJyDrQcPeUgT73Iphz3FYoSOVOwz7lFL_Zze5Ke75VfUf==",
    "provider": "Basic",
    "loginTime": "2023-07-30T00:47:07.004997972-06:00"
}
```