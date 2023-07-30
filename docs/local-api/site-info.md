# Site Info

## GET `/api/site_info`

Get solar system site information.

### Response Body

```json
{
    "max_system_energy_kWh": 27,
    "max_system_power_kW": 10,
    "site_name": "Wardenclyffe",
    "timezone": "America/Pacific",
    "max_site_meter_power_kW": 1000000000,
    "min_site_meter_power_kW": -1000000000,
    "nominal_system_energy_kWh": 27,
    "nominal_system_power_kW": 10,
    "grid_code": {
        "grid_code": "60Hz_240V_s_IEEE1547a_2014",
        "grid_voltage_setting": 240,
        "grid_freq_setting": 60,
        "grid_phase_setting": "Split",
        "country": "United States",
        "state": "California",
        "distributor": "*",
        "utility": "Pacific Gas and Electric",
        "retailer": "*",
        "region": "IEEE1234a:2023"
    }
}
```

## GET `/api/site_info/site_name`

Get solar system site name.

### Response Body

```json
{
    "site_name": "Wardenclyffe",
    "timezone": "America/Pacific",
}
```