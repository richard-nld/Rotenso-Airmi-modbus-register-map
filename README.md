
# Rotenso Airmi modbus register map


$~$


Please see attached modbus.yaml example file for Home Assistant.

$~$

| Register | Map | Description |
|:--------:|--------|----------|
| `0` | ||
| `40` | Room temp Tro| Room temperature measured by the room/remote sensor |
| | ||
| `42` | In water temp TA | Water temperature entering the heat-pump unit |
| `43` | Out water temp TB | Water temperature leaving the heat-pump unit |
| | ||
| `46` | Tank temp | Temperature measured by the DHW tank temperature sensor. This is the actual tank temperature reported to the heat pump—not the DHW setpoint |
| | ||
| `48` | Solar temp Tso | Solar-system temperature | 
| `49` | Coil temp T3 | Outdoor heat-exchanger coil temperature |
| | ||
| `50` | Ambient temp T4 | Outdoor/ambient air temperature measured by sensor T4 |
| `51` | Liquid temp T5 | Refrigerant liquid-line temperature measured by T5 |
| `52` | Discharge temp TP | Refrigerant/gas temperature at compressor discharge |
| `53` | Suction temp TH | Refrigerant suction temperature entering the compressor |
| | ||
| `61` | Out water pre | Water pressure on the outlet side, bar |
| `62` |  I-pump output | Inverter/internal circulation-pump output, % |
| `63`| Water flow PWM | PWM command to the circulation pump, % |
| `64` | Water flow | Calculated water flow rate, m³/h |
||||
| `66` | C-A curve temp | Temperature associated with point A of the cooling weather-compensation curve |
| `67` | H-A curve temp | Temperature associated with point A of the heating weather-compensation curve |
| `68` | C-B curve temp | Temperature associated with point B of the cooling weather-compensation curve |
| `69` | H-B curve temp | Temperature associated with point B of the heating weather-compensation curve |
| `70` | EEV-1 open | Opening of electronic expansion valve 1, in steps. Higher number = valve opened further |
| `71` | EEV-2 open | Opening of electronic expansion valve 2, in steps |
| `72` | DC fan speed 1 | Speed of DC outdoor fan 1, RPM |
| | ||
| `74` | Input voltage | AC supply voltage measured by the unit, V |
| `75` | AC current | Current drawn from the AC supply by the unit, A |
| `76` | Bus voltage | DC inverter-bus voltage, VDC |
| `77` | Comp. current | Current being supplied to the compressor/inverter compressor circuit |
| `78` | Comp. frequency | Actual compressor inverter frequency, in Hz |
| | ||
| `80` | PWM pump | PWM-controlled water-pump status/control signal |
| | ||
| `87` | Suc. pressure |




<br/><br/>
<br/><br/>
## Missing
<br/>

| Register | Map | Description |
|:--------:|--------|----------|
|| 4-Way valve | Typically OFF in heating and ON when reversing for cooling/defrost |
|| AC fan | Outdoor fan status |
|| SV1 status | Solenoid valve 1 status |
|| SV2 status | Solenoid valve 2 status |
|| IPH heater | Electric heater associated with IPH/frost protection of the hydraulic section |
|| Tank heater | Domestic-hot-water tank electric heater status |
|| Oil return | Oil-return function/status |
|| HP2 | High-pressure protection/switch circuit 2 status |
|| Chassis heater | Bottom/chassis heater status. Used to prevent ice accumulation in the outdoor unit |
|| PFC temp | Temperature of the PFC power-electronics section |
|| IPM tank | Temperature of the Intelligent Power Module driving the compressor |
|| DC fan speed 2 | Speed of DC outdoor fan 2, RPM |
|| Eco in temp | Temperature at the inlet of the economizer circuit/heat exchanger |
|| Eco out temp | Temperature at the outlet of the economizer circuit/heat exchanger |
|| Low sat temp | Calculated/measured low-side saturated refrigerant temperature |
|| Crankcase heater | Compressor crankcase heater status |
|| Plate heater | Plate/heat-exchanger heater status |
|| In water pre | Water pressure on the inlet side, bar |
|| Unit model | Nominal model/capacity identification reported by the controller |
|| SV3 | Solenoid valve 3 status |
|| Final temp TC | Final/terminal water temperature sensor TC |
|| Buffer temp TE1 | Buffer-tank temperature sensor 1 |
|| Buffer temp TE2 | Buffer-tank temperature sensor 2 |
|| Mix in temp TZ2 | Temperature entering mixing circuit/second heating zone |
|| AHS | Additional/Auxiliary Heat Source status |
|| P_d | DHW-related pump/output status |
|| P_o | Primary/other circulation-pump output/status |
|| B zone P_c | Pump for heating/cooling Zone B |
|| P_s | Solar-system pump/status |
|| SG | Smart Grid input/status |
|| Gas leakage rate ||



