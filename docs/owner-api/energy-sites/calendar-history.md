# Calendar History

## GET `api/1/energy_sites/{energy_site_id}/calendar_history`

Get a time series history of the solar system by providing an calendar end date.

| Parameter | Example                   | Description                                                          |
| :-------- | :------------------------ | :------------------------------------------------------------------- |
| kind      | power                     | Options available: power, energy                                     |
| period    | day                       | Only use with kind energy. Options available: day, week, month, year |
| end_date  | 2022-01-01T23:59:59-07:00 | End date of your history search.                                     |

Kind power returns 5 minute interval summary of the system.

## GET `api/1/energy_sites/{energy_site_id}/calendar_history?kind=power&end_date=2022-01-01T23:59:59-07:00`

### Power Response Body

```json
{
    "response": {
        "serial_number": "1234567-00-E--TG123456789A5M",
        "installation_time_zone": "America/Pacific",
        "time_series": [
            {
                "timestamp": "2022-01-01T00:00:00-07:00",
                "solar_power": 0,
                "battery_power": 0,
                "grid_power": 1833.5714285714287,
                "grid_services_power": 0,
                "generator_power": 0
            },
            {
                "timestamp": "2022-01-01T00:05:00-07:00",
                "solar_power": 0,
                "battery_power": 0,
                "grid_power": 1816.2142857142858,
                "grid_services_power": 0,
                "generator_power": 0
            }
        ]
    }
}
```

## GET `api/1/energy_sites/{energy_site_id}/calendar_history?kind=energy&period=week&end_date=2023-01-01T23:59:59-07:00`

### Energy Response Body

```json
{
    "response": {
        "serial_number": "1234567-00-E--TG123456789A5M",
        "period": "week",
        "installation_time_zone": "America/Pacific",
        "time_series": [
            {
                "timestamp": "2023-01-01T01:00:00-07:00",
                "solar_energy_exported": 26631.111190378666,
                "generator_energy_exported": 0,
                "grid_energy_imported": 19019.33770610951,
                "grid_services_energy_imported": 0,
                "grid_services_energy_exported": 0,
                "grid_energy_exported_from_solar": 14088.266245156992,
                "grid_energy_exported_from_generator": 0,
                "grid_energy_exported_from_battery": 0,
                "battery_energy_exported": 6840,
                "battery_energy_imported_from_grid": 0,
                "battery_energy_imported_from_solar": 6490,
                "battery_energy_imported_from_generator": 0,
                "consumer_energy_imported_from_grid": 19019.33770610951,
                "consumer_energy_imported_from_solar": 6052.844945221674,
                "consumer_energy_imported_from_battery": 6840,
                "consumer_energy_imported_from_generator": 0
            }
        ]
    }
}
```
