# Meters

## GET `/api/meters`

Get meter information.

```json
[
    {
        "serial": "JBL12345Y1F01EsynchrometerY",
        "short_id": "1234567-00-E--TG123456789A5M",
        "type": "synchrometerY",
        "cts": [
            {
                "type": "site",
                "valid": [
                    true,
                    false,
                    false,
                    false
                ],
                "inverted": [
                    false,
                    false,
                    false,
                    false
                ],
                "real_power_scale_factor": 1
            },
            {
                "type": "solar",
                "valid": [
                    false,
                    true,
                    false,
                    false
                ],
                "inverted": [
                    false,
                    false,
                    false,
                    false
                ],
                "real_power_scale_factor": 2
            }
        ]
    },
    {
        "serial": "JBL12345Y1F01EsynchrometerX",
        "short_id": "1234567-00-E--TG123456789A5M",
        "type": "synchrometerX",
        "cts": [
            {
                "type": "site",
                "valid": [
                    true,
                    true,
                    false,
                    false
                ],
                "inverted": [
                    false,
                    false,
                    false,
                    false
                ]
            }
        ]
    }
]
```

## GET `/api/meters/aggregates`

Gets current Solar, Battery, and House information. As well as all time site information.

```json
{
    "site": {
        "last_communication_time": "2023-07-30T04:24:54.355954089-06:00",
        "instant_power": 701,
        "instant_reactive_power": -740,
        "instant_apparent_power": 1019.313984991867,
        "frequency": 0,
        "energy_exported": 54321.8100695894,
        "energy_imported": 12345.032329421,
        "instant_average_voltage": 210.18003537146433,
        "instant_average_current": 8.6045,
        "i_a_current": 0,
        "i_b_current": 0,
        "i_c_current": 0,
        "last_phase_voltage_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_power_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
        "timeout": 1500000000,
        "num_meters_aggregated": 2,
        "instant_total_current": 8.6045
    },
    "battery": {
        "last_communication_time": "2023-07-30T04:24:54.355832971-06:00",
        "instant_power": 0,
        "instant_reactive_power": 650,
        "instant_apparent_power": 650,
        "frequency": 60,
        "energy_exported": 10196160,
        "energy_imported": 11605680,
        "instant_average_voltage": 242.8,
        "instant_average_current": -0.4,
        "i_a_current": 0,
        "i_b_current": 0,
        "i_c_current": 0,
        "last_phase_voltage_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_power_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
        "timeout": 1500000000,
        "num_meters_aggregated": 2,
        "instant_total_current": -0.4
    },
    "load": {
        "last_communication_time": "2023-07-30T04:24:54.355832971-06:00",
        "instant_power": 682.25,
        "instant_reactive_power": -42.75,
        "instant_apparent_power": 683.5880521191107,
        "frequency": 0,
        "energy_exported": 0,
        "energy_imported": 38827769.48582777,
        "instant_average_voltage": 210.18003537146433,
        "instant_average_current": 3.2460266684902632,
        "i_a_current": 0,
        "i_b_current": 0,
        "i_c_current": 0,
        "last_phase_voltage_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_power_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
        "timeout": 1500000000,
        "instant_total_current": 3.2460266684902632
    },
    "solar": {
        "last_communication_time": "2023-07-30T04:24:54.378329056-06:00",
        "instant_power": -4,
        "instant_reactive_power": 40,
        "instant_apparent_power": 40.19950248448356,
        "frequency": 0,
        "energy_exported": 27089270.66581665,
        "energy_imported": 25683.40224871719,
        "instant_average_voltage": 210.4095321034672,
        "instant_average_current": 0.1795,
        "i_a_current": 0,
        "i_b_current": 0,
        "i_c_current": 0,
        "last_phase_voltage_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_power_communication_time": "0001-01-01T00:00:00Z",
        "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
        "timeout": 1500000000,
        "num_meters_aggregated": 1,
        "instant_total_current": 0.1795
    }
}
```

## GET `/api/meters/readings`

Get current meter readings.

```json
{
    "JBL12345Y1F01EsynchrometerX": {
        "error": "run sitemanager flag enabled, sitemanager process is running",
        "data": {
            "firmwareVersion": "",
            "cts": [
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                }
            ]
        }
    },
    "JBL12345Y1F01EsynchrometerY": {
        "error": "sitemanager process is running, run sitemanager flag enabled",
        "data": {
            "firmwareVersion": "",
            "cts": [
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                },
                {
                    "ct": 0,
                    "v_V": 0,
                    "p_W": 0,
                    "q_VAR": 0,
                    "eExp_Ws": 0,
                    "eImp_Ws": 0,
                    "i_A": 0
                }
            ]
        }
    }
}
```

## GET `/api/meters/site`

Get meters site information.

```json
[
    {
        "id": 0,
        "location": "site",
        "type": "synchrometerY",
        "cts": [
            true,
            false,
            false,
            false
        ],
        "inverted": [
            false,
            false,
            false,
            false
        ],
        "connection": {
            "short_id": "1234567-00-E--TG123456789A5M",
            "device_serial": "JBL12345Y1F01EsynchrometerY",
            "https_conf": {}
        },
        "real_power_scale_factor": 1,
        "ct_voltage_references": {
            "ct1": "Phase1",
            "ct2": "Phase2",
            "ct3": "Phase1"
        },
        "Cached_readings": {
            "last_communication_time": "2023-07-30T04:29:55.899768284-06:00",
            "instant_power": 0,
            "instant_reactive_power": 0,
            "instant_apparent_power": 0,
            "frequency": 0,
            "energy_exported": 0.000030957669878262095,
            "energy_imported": 0.000014389256648428272,
            "instant_average_voltage": 210.18436549848326,
            "instant_average_current": 0,
            "i_a_current": 0,
            "i_b_current": 0,
            "i_c_current": 0,
            "last_phase_voltage_communication_time": "2023-07-30T04:29:55.765667088-06:00",
            "v_l1n": 121.35000000000001,
            "last_phase_power_communication_time": "2023-07-30T04:29:55.899768284-06:00",
            "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
            "serial_number": "JBL12345Y1F01E",
            "timeout": 1500000000,
            "instant_total_current": 0
        }
    },
    {
        "id": 1,
        "location": "site",
        "type": "synchrometerX",
        "cts": [
            true,
            true,
            false,
            false
        ],
        "inverted": [
            false,
            false,
            false,
            false
        ],
        "connection": {
            "short_id": "1234567-00-E--TG123456789A5M",
            "device_serial": "JBL12345Y1F01EsynchrometerY",
            "https_conf": {}
        },
        "Cached_readings": {
            "last_communication_time": "2023-07-30T04:29:55.900000396-06:00",
            "instant_power": 735,
            "instant_reactive_power": -733,
            "instant_apparent_power": 1038.033718142142,
            "frequency": 0,
            "energy_exported": 3456789.44263701,
            "energy_imported": 16789012.68004938,
            "instant_average_voltage": 210.1757052444454,
            "instant_average_current": 8.9345,
            "i_a_current": 3.729,
            "i_b_current": 5.2055,
            "i_c_current": 0,
            "last_phase_voltage_communication_time": "2023-07-30T04:29:55.900057268-06:00",
            "v_l1n": 121.35000000000001,
            "v_l2n": 121.34,
            "last_phase_power_communication_time": "2023-07-30T04:29:55.900000396-06:00",
            "real_power_a": 267,
            "real_power_b": 468,
            "reactive_power_a": -330,
            "reactive_power_b": -403,
            "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
            "serial_number": "JBL12345Y1F01E",
            "timeout": 1500000000,
            "instant_total_current": 8.9345
        }
    }
]
```

## GET `/api/meters/solar`

Get meters solar information.

```json
[
    {
        "id": 0,
        "location": "solar",
        "type": "synchrometerY",
        "cts": [
            false,
            true,
            false,
            false
        ],
        "inverted": [
            false,
            false,
            false,
            false
        ],
        "connection": {
            "short_id": "1234567-00-E--TG123456789A5M",
            "device_serial": "JBL12345Y1F01EsynchrometerY",
            "https_conf": {}
        },
        "real_power_scale_factor": 2,
        "ct_voltage_references": {
            "ct1": "Phase1",
            "ct2": "Phase2",
            "ct3": "Phase1"
        },
        "Cached_readings": {
            "last_communication_time": "2023-07-30T04:33:20.643832928-06:00",
            "instant_power": -4,
            "instant_reactive_power": 40,
            "instant_apparent_power": 40.19950248448356,
            "frequency": 0,
            "energy_exported": 25678.800893156236,
            "energy_imported": 27890123.537190706,
            "instant_average_voltage": 210.21900651463463,
            "instant_average_current": 0.1785,
            "i_a_current": 0,
            "i_b_current": 0.1785,
            "i_c_current": 0,
            "last_phase_voltage_communication_time": "2023-07-30T04:33:20.541647678-06:00",
            "v_l2n": 121.38,
            "last_phase_power_communication_time": "2023-07-30T04:33:20.643832928-06:00",
            "real_power_b": -4,
            "reactive_power_b": 40,
            "last_phase_energy_communication_time": "0001-01-01T00:00:00Z",
            "serial_number": "JBL12345Y1F01E",
            "timeout": 1500000000,
            "instant_total_current": 0.1785
        }
    }
]
```