# Customer

## GET `/api/customer`

Get if the customer is registered.

### Response Body

```json
{
    "registered": true
}
```

## GET `/api/customer/registration`

Get additional customer registration information.

### Response Body

```json
{
    "privacy_notice": null,
    "limited_warranty": null,
    "grid_services": null,
    "marketing": null,
    "registered": true,
    "timed_out_registration": false
}
```
