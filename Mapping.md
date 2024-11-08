# Mapping internal data / REST endpoints
This table helps to define which Solis REST API endpoints provide which information used for monitoring.

| fieldKey                 | fieldType | REST endpoint  | API                          |
|--------------------------|-----------|----------------|------------------------------|
| AC_Current               | float     | inverterDetail | (iAc1+iAc2+iAc3)/3           |                         
| AC_Frequency             | float     | inverterDetail | fac                          |
| AC_Power                 | float     | inverterDetail | pac                          |
| AC_Voltage               | float     | inverterDetail | (uAc1+uAc2+uAc3)/3           |                         
| Annual_Energy_Used       | float     | inverterYear   | energy - gridSellEnergy      |                         
| Annual_Generation        | float     | inverterYear   | energy                       |
| Battery_Charge_Percent   | float     |                |                              |                         
| Consumption_Energy       | float     | inverterDetail | homeLoadTotalEnergy          |                         
| Consumption_Power        | float     | inverterDetail | familyLoadPower              |                         
| DC_Current1              | float     | inverterDetail | iPv1                         |
| DC_Current2              | float     | inverterDetail | iPv2                         |
| DC_Current3              | float     | inverterDetail | iPv3                         |
| DC_Current4              | float     | inverterDetail | iPv4                         |
| DC_Power_PV1             | float     | inverterDetail | pow1                         |
| DC_Power_PV2             | float     | inverterDetail | pow2                         |
| DC_Power_PV3             | float     | inverterDetail | pow3                         |
| DC_Power_PV4             | float     | inverterDetail | pow4                         |
| DC_Voltage_PV1           | float     | inverterDetail | uPv1                         |
| DC_Voltage_PV2           | float     | inverterDetail | uPv2                         |
| DC_Voltage_PV3           | float     | inverterDetail | uPv3                         |
| DC_Voltage_PV4           | float     | inverterDetail | uPv4                         |
| Daily_Energy_Used        | float     | inverterDetail | eToday - gridSellTodayEnergy |                         
| Daily_Generation         | float     | inverterDetail | eToday                       |
| Generation_Last_Month    | float     | inverterMonth  | energy                       |                         
| Inverter_Temperature     | float     | inverterDetail | inverterTemperature          |
| Monthly_Energy_Used      | float     | inverterMonth  | energy - gridSellEnergy      |                         
| Monthly_Generation       | float     | inverterDetail | eMonth                       |
| Power_Grid_Total_Power   | float     | inverterDetail | pSum                         |                         
| Total_Energy_Purchased   | float     | inverterDetail | gridPurchasedTotalEnergy     | 
| Total_Generation         | float     | inverterDetail | eTotal                       |     
| Total_On_grid_Generation | float     | inverterDetail | gridSellTotalEnergy          |      
| updateDate               | integer   | inverterDetail | dataTimestamp                |            
