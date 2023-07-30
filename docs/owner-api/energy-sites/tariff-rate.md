# Tarrif Rate

## GET `api/1/energy_sites/{energy_site_id}/tariff_rate`

Get the current tariff rate of the solar system.

### Response Body

```json
{
    "response": {
        "name": "Custom Time of Use",
        "utility": "Clean Power Alliance",
        "daily_charges": [
            {
                "amount": 0,
                "name": "Charge"
            }
        ],
        "demand_charges": {
            "ALL": {
                "ALL": 0
            },
            "Summer": {},
            "Winter": {}
        },
        "energy_charges": {
            "ALL": {
                "ALL": 0
            },
            "Season3": {
                "OFF_PEAK": 0.05,
                "ON_PEAK": 0.25
            },
            "Summer": {
                "OFF_PEAK": 0.05,
                "ON_PEAK": 0.25
            },
            "Winter": {
                "OFF_PEAK": 0.05,
                "ON_PEAK": 0.25
            }
        },
        "seasons": {
            "Season3": {
                "fromDay": 1,
                "toDay": 30,
                "fromMonth": 6,
                "toMonth": 9,
                "tou_periods": {
                    "OFF_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 20,
                            "fromMinute": 0,
                            "toHour": 15,
                            "toMinute": 0
                        },
                        {
                            "fromDayOfWeek": 5,
                            "toDayOfWeek": 6,
                            "fromHour": 0,
                            "fromMinute": 0,
                            "toHour": 0,
                            "toMinute": 0
                        }
                    ],
                    "ON_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 15,
                            "fromMinute": 0,
                            "toHour": 20,
                            "toMinute": 0
                        }
                    ]
                }
            },
            "Summer": {
                "fromDay": 1,
                "toDay": 30,
                "fromMonth": 10,
                "toMonth": 4,
                "tou_periods": {
                    "OFF_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 10,
                            "fromMinute": 0,
                            "toHour": 15,
                            "toMinute": 0
                        },
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 20,
                            "fromMinute": 0,
                            "toHour": 8,
                            "toMinute": 0
                        },
                        {
                            "fromDayOfWeek": 5,
                            "toDayOfWeek": 6,
                            "fromHour": 0,
                            "fromMinute": 0,
                            "toHour": 0,
                            "toMinute": 0
                        }
                    ],
                    "ON_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 8,
                            "fromMinute": 0,
                            "toHour": 10,
                            "toMinute": 0
                        },
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 15,
                            "fromMinute": 0,
                            "toHour": 20,
                            "toMinute": 0
                        }
                    ]
                }
            },
            "Winter": {
                "fromDay": 1,
                "toDay": 31,
                "fromMonth": 5,
                "toMonth": 5,
                "tou_periods": {
                    "OFF_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 20,
                            "fromMinute": 0,
                            "toHour": 15,
                            "toMinute": 0
                        },
                        {
                            "fromDayOfWeek": 5,
                            "toDayOfWeek": 6,
                            "fromHour": 0,
                            "fromMinute": 0,
                            "toHour": 0,
                            "toMinute": 0
                        }
                    ],
                    "ON_PEAK": [
                        {
                            "fromDayOfWeek": 0,
                            "toDayOfWeek": 4,
                            "fromHour": 15,
                            "fromMinute": 0,
                            "toHour": 20,
                            "toMinute": 0
                        }
                    ]
                }
            }
        },
        "sell_tariff": {
            "name": "Custom Time of Use",
            "utility": "Clean Power Alliance",
            "daily_charges": [
                {
                    "amount": 0,
                    "name": "Charge"
                }
            ],
            "demand_charges": {
                "ALL": {
                    "ALL": 0
                },
                "Summer": {},
                "Winter": {}
            },
            "energy_charges": {
                "ALL": {
                    "ALL": 0
                },
                "Season3": {
                    "OFF_PEAK": 0.06,
                    "ON_PEAK": 0.06
                },
                "Summer": {
                    "OFF_PEAK": 0.04,
                    "ON_PEAK": 0.04
                },
                "Winter": {
                    "OFF_PEAK": 0.04,
                    "ON_PEAK": 0.04
                }
            },
            "seasons": {
                "Season3": {
                    "fromDay": 1,
                    "toDay": 30,
                    "fromMonth": 6,
                    "toMonth": 9,
                    "tou_periods": {
                        "OFF_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 20,
                                "fromMinute": 0,
                                "toHour": 15,
                                "toMinute": 0
                            },
                            {
                                "fromDayOfWeek": 5,
                                "toDayOfWeek": 6,
                                "fromHour": 0,
                                "fromMinute": 0,
                                "toHour": 0,
                                "toMinute": 0
                            }
                        ],
                        "ON_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 15,
                                "fromMinute": 0,
                                "toHour": 20,
                                "toMinute": 0
                            }
                        ]
                    }
                },
                "Summer": {
                    "fromDay": 1,
                    "toDay": 30,
                    "fromMonth": 10,
                    "toMonth": 4,
                    "tou_periods": {
                        "OFF_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 10,
                                "fromMinute": 0,
                                "toHour": 15,
                                "toMinute": 0
                            },
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 20,
                                "fromMinute": 0,
                                "toHour": 8,
                                "toMinute": 0
                            },
                            {
                                "fromDayOfWeek": 5,
                                "toDayOfWeek": 6,
                                "fromHour": 0,
                                "fromMinute": 0,
                                "toHour": 0,
                                "toMinute": 0
                            }
                        ],
                        "ON_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 8,
                                "fromMinute": 0,
                                "toHour": 10,
                                "toMinute": 0
                            },
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 15,
                                "fromMinute": 0,
                                "toHour": 20,
                                "toMinute": 0
                            }
                        ]
                    }
                },
                "Winter": {
                    "fromDay": 1,
                    "toDay": 31,
                    "fromMonth": 5,
                    "toMonth": 5,
                    "tou_periods": {
                        "OFF_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 20,
                                "fromMinute": 0,
                                "toHour": 15,
                                "toMinute": 0
                            },
                            {
                                "fromDayOfWeek": 5,
                                "toDayOfWeek": 6,
                                "fromHour": 0,
                                "fromMinute": 0,
                                "toHour": 0,
                                "toMinute": 0
                            }
                        ],
                        "ON_PEAK": [
                            {
                                "fromDayOfWeek": 0,
                                "toDayOfWeek": 4,
                                "fromHour": 15,
                                "fromMinute": 0,
                                "toHour": 20,
                                "toMinute": 0
                            }
                        ]
                    }
                }
            }
        }
    }
}
```
