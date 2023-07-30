# Operation

## GET `/api/operation`

Get the current operation mode and settings.

### Response Body

```json
{
    "real_mode": "autonomous",
    "backup_reserve_percent": 24,
    "freq_shift_load_shed_soe": 75,
    "freq_shift_load_shed_delta_f": -0.32
}
```

### Response Fields

| Field                        | Type    | Example    | Description                                                                 |
| :--------------------------- | :------ | :--------- | :-------------------------------------------------------------------------- |
| real_mode                    | String  | autonomous | The current system mode: self_consumption, backup, autonomous (Time of Use) |
| backup_reserve_percent       | Integer | 24         | Powerwall percent saved for backup.                                         |
| freq_shift_load_shed_soe     | Integer | 75         |                                                                             |
| freq_shift_load_shed_delta_f | Float   | -0.32      |                                                                             |

## POST `/api/operation`

Not yet documented.
