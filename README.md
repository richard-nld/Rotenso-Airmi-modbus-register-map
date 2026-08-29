
# Rotenso Airmi modbus register map


$~$


Please note that modbus 0-based offset is used so you have to extract 1 of the id. Please see attached modbus.yaml example for Home Assistant.

$~$


| Register | map | 
|:--------:|--------|
| `41` | Room temp |
| | |
| `43` | In water temp TA |
| `44` | Out water temp TB |
| | |
| `47` | Tank temp |
| | |
| `50` | Coil temp T3 ? |
| | |
| `51` | Ambient temp T4 |
| `52` | Liquid temp T5 |
| `53` | Suction temp TH |
| `54` | Discharge temp TP | 
| | |
| `#57` | Out water temp TB ? |
| | |
| `62` | Out water pre |
| | |
| `67` | C-A curve temp |
| `68` | H-A curve temp |
| `69` | C-B curve temp |
| `70` | H-B curve temp |
| `71` | EEV-1 open |
| `72` | EEV-2 open |
| | |
| `75` | Input voltage |
| | |
| `77` | Bus voltage |
| | |
| `88` | Suc. pressure |
