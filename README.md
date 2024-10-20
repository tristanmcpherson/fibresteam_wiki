# fibresteam_wiki
Wiki for the Fibre Steam toolhead designed for the Monolith Gantry by @Rafi https://github.com/Shamoon78/

## What is it?
Fibre Steam is a robust and high performance CPAP toolhead designed for the Monolith Gantry. Fibre Steam's variants integrate the extruder into the toolhead which allows for accurate CoM balancing for the toolhead. CoM and the overall stiffness of your toolhead is integral to achieving good input shapers for high performance printing. 

Fibre Steam only currently supports Beacon for its Z homing sensor 

Note: With the current carriage design there is some X travel loss, on my particular setup I see about 10mm loss in X travel

## Where do I get it?
Fibre Steam's original CAD files are located at https://github.com/Shamoon78/Angry_Tool_Head/ however this repo aims to add some STLs and help while Rafi is away.

## What can I print?
Fibre Steam comes in several variants, here are them sorted by the gearset you will be using:
- HGX
  - Goliath (MGN12, MGN9, 18mm CPAP)
  - Rapido HF (MGN9, Unknown CPAP size)
  - Rapido UHF (MGN9, Unknown CPAP size)
  - Rapido UHF (MGN12, 18mm CPAP) (unofficiual support added by @tristanmcpherson)
- RIDGA
  - Goliath (MGN12, MGN9, 18mm CPAP)
  - Rapido UHF (MGN12, 18mm CPAP) (unofficial support added by @tristanmcpherson)
  - Dragon UHF 
- Mellow NF Cannon Worm (semi deprecated)
  - Goliath (MGN12, MGN9, 18mm CPAP + MGN12, MGN9, 22mm CPAP)
- Galileo 2
  - Goliath (MGN9 18mm CPAP + MGN9 22mm CPAP) 




## How to print?
Fibre Steam is not shrinkage adjusted and should be printed in the stiffest filament you have available.
Rafi recommends using filled filaments such as PCCF, ASACF, ABSCF

### Print Settings
I have had good success printing it with:
- Layer Height: 0.2mm
- Layer Width: 0.4mm
- Wall Count: 3
- Top: 5
- Bottom: 5

## Carriage Types
For HGX there are two carriage types:
- Standard Belt Clip carriage (current recommended)
- New Belt Clamp carriage

I have not had good success using the belt clamp carriage in it's current phase as it is difficult to keep pretension the way the clamps grab onto the belt and then slide into the carriage, reducing the tension on the belt 
