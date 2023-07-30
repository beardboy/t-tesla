# Power History

## GET `api/1/powerwalls/{battery_id}/powerhistory`

Retrieve the time series of powerwall usage as well as self consumption data.

### Response Body

```json
{
    "response": {
        "serial_number": "1234567-00-E--TG123456789A5M",
        "time_series": [
            {
                "timestamp": "2023-07-29T00:00:00-06:00",
                "solar_power": 0,
                "battery_power": 0,
                "grid_power": 11463.65306122449,
                "grid_services_power": 0,
                "generator_power": 0
            },
            {
                "timestamp": "2023-07-29T00:05:00-06:00",
                "solar_power": 0,
                "battery_power": 0,
                "grid_power": 12482.857142857143,
                "grid_services_power": 0,
                "generator_power": 0
            }
        ],
        "self_consumption_data": [
            {
                "timestamp": "2023-07-29T00:00:00-06:00",
                "solar": 33.192774517066496,
                "battery": 0
            },
            {
                "timestamp": "2023-07-30T00:00:00-06:00",
                "solar": 15.917330844895899,
                "battery": 0
            }
        ]
    }
}
```
