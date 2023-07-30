# Site Info

## GET `api/1/energy_sites/{energy_site_id}/site_info`

Retrieve comprehensive solar system site information, encompassing details on the current configuration, components, software version, geographical location, and address.

### Response Body

```json
{
    "response": {
        "id": "1234567-00-E--TG123456789A5M",
        "site_name": "Wardenclyffe",
        "backup_reserve_percent": 20,
        "default_real_mode": "autonomous",
        "installation_date": "2021-01-01T12:00:00-06:00",
        "user_settings": {
            "storm_mode_enabled": false,
            "powerwall_onboarding_settings_set": true,
            "powerwall_tesla_electric_interested_in": false,
            "sync_grid_alert_enabled": true,
            "breaker_alert_enabled": false
        },
        "components": {
            "solar": true,
            "solar_type": "solarglass",
            "battery": true,
            "grid": true,
            "backup": true,
            "gateway": "teg",
            "load_meter": true,
            "tou_capable": true,
            "storm_mode_capable": true,
            "flex_energy_request_capable": false,
            "car_charging_data_supported": false,
            "off_grid_vehicle_charging_reserve_supported": true,
            "vehicle_charging_performance_view_enabled": false,
            "vehicle_charging_solar_offset_view_enabled": false,
            "battery_solar_offset_view_enabled": true,
            "solar_value_enabled": true,
            "energy_value_header": "Energy Value",
            "energy_value_subheader": "Estimated Value",
            "energy_service_self_scheduling_enabled": true,
            "show_grid_import_battery_source_cards": true,
            "set_islanding_mode_enabled": true,
            "wifi_commissioning_enabled": true,
            "backup_time_remaining_enabled": true,
            "battery_type": "ac_powerwall",
            "configurable": true,
            "grid_services_enabled": false,
            "edit_setting_permission_to_export": true,
            "edit_setting_grid_charging": true,
            "edit_setting_energy_exports": true
        },
        "version": "23.12.10 30f95d0b",
        "battery_count": 2,
        "tou_settings": {
            "optimization_strategy": "economics",
            "schedule": [
                {
                    "target": "off_peak",
                    "week_days": [
                        6,
                        0
                    ],
                    "start_seconds": 0,
                    "end_seconds": 0
                },
                {
                    "target": "off_peak",
                    "week_days": [
                        1,
                        2,
                        3,
                        4,
                        5
                    ],
                    "start_seconds": 72000,
                    "end_seconds": 28800
                },
                {
                    "target": "peak",
                    "week_days": [
                        1,
                        2,
                        3,
                        4,
                        5
                    ],
                    "start_seconds": 54000,
                    "end_seconds": 72000
                }
            ]
        },
        "nameplate_power": 10000,
        "nameplate_energy": 27000,
        "installation_time_zone": "America/Pacific",
        "off_grid_vehicle_charging_reserve_percent": 75,
        "max_site_meter_power_ac": 1000000000,
        "min_site_meter_power_ac": -1000000000,
        "geolocation": {
            "latitude":  37.393782,
            "longitude": -122.150034
        },
        "address": {
            "address_line1": "3500 Deer Creek Rd",
            "city": "Palo Alto",
            "state": "CA",
            "zip": "94304",
            "county": "Santa Clara County",
            "country": "US"
        }
    }
}
```
