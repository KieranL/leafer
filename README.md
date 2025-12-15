[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y718VEOP)

# Leafer

 A 3D printed RC snowmobile styled after machines from the 70s

Currently a work in progress and there is a very good chance files and BOM will change

[Download all files](https://github.com/KieranL/leafer/archive/refs/heads/main.zip)

![PXL_20241206_215935408](https://github.com/user-attachments/assets/bb789e8b-1dca-483b-8c07-043e192e1087)
![PXL_20241206_220219765](https://github.com/user-attachments/assets/a0b37f3f-0062-4779-826e-ac0373ebff43)


##

Join the discord group https://discord.gg/C744rbBbvj

## BOM 

Electronics have been tested to work in this config unless noted

Note: some of these are affiliate links

- Motor (with matching esc)
  - 380 size brushless motor, 19mm hole spacing (max 28mm diameter) ~3100kv
    - Expensive, nicer option [Rocket Supersonic sensored 380 3300kv](https://s.click.aliexpress.com/e/_DdVOuNJ)
    - Cheap option with servo [Rocket 2845 3100kv](https://www.aliexpress.com/item/1005001562382697.html)
  - 540/36xx size motors should work with a different frame (included)
- 2-3s LiPo 1000-2200mah
  - 2200mah 2s gives around 25-30 minute run time in low snow/icy conditions with a 3300kv sensored 380 motor 
    - I run CNHL Black Series 1300-1500mah 2-3s batteries that fit well in the front. There is also room under the seat but I don't recommend putting the battery there
- Battery strap
- 6+ MR83 3x8x3 bearings (4 for rear idlers, 2 for front idler wheels and some for a belt tensioner if needed)    
- 8x MR128 8x12x3.5 Bearings
- 1/10 scale servo or 9g/TR4 servo
- 70-80mm shock
  - I use 70mm but if you want it to sit a littler higher 80mm works
- 48mm Mini E-Revo shocks for skis (Optional)
- 150g 85a TPU for track and hood hinge/straps
  - 95a may work but the track will not be nearly as flexible and take more power to turn
- 1kg rigid filament
  - PLA+/Tough PLA works well but most components it does not matter
- M2 Screws
  - 6-8mm long for the spindle covers and front bumper
- M2.5 Screws (if using ski shocks)
  -  2 10mm, 2 16mm
- M3 screws
  - Mostly 6mm, 8mm, 12mm, and 16mm
- M3 Threaded rod
  - skid rear axle and steering links
- Motor drive pulley
  - 12t 2GT 3.175mm bore (or 5mm bore with shaft adapter) pulley for 380 motor
  - 16-20t 2GT 4-5mm bore pulley for 36XX
- Driven pulley (printable options will be included)
  - 58-64t for 380
  - 56-60t for 36XX
- 188mm 2GT Closed loop belt
- short piece of gt2 belt for front limiter strap
- 8mm aluminum/steel driveshaft if not using the printed one
  - slightly shorter overall but the bolt spacing is the same as skeeride 2 shaft which will also fit

- Lights (optional)
  - https://s.click.aliexpress.com/e/_c3cogIUp these injora 17mm lights, take them out of the housing. headlight uses a pair, and the tail light plus dash light (wip) will each use a single pcb of the pair. So in total 2 sets of lights for the whole sled

## Printing

- Print the track, hood straps, hood hinges, snow flap, and spindle covers in TPU
- The spindles need to have really good layer adhesion so make sure to use a strong material and maybe bump up the hotend temp a bit
- Material choice for most other parts does not matter but the springs I would suggest PC-ABS or PLA+
- Some parts will need supports
  - the tunnel has integrated supports included

Note: The rear axle cross shaft and front cross brace look the same, but the rear one has a larger hole so you can slide a threaded rod through, where as the front is smaller so you can thread a bolt into it

## The build

### Skid

Glue the gt2 belt limiter strap into the tensioner, and wrap the other end around the front skid brace and lock it down with a zip tie

![PXL_20241223_175957527](https://github.com/user-attachments/assets/99850070-65d1-4aec-a939-e34f1e5f7539)
![PXL_20241223_180003280](https://github.com/user-attachments/assets/6b03c6c3-afd8-4b56-a8d1-8a88836e8a91)

### Steering

There are 2 servo size options, both will work with option A

#### Option A

Printed steering link between each spindle, with a link made with m3 rod and ends from the servo horn to the printed link

![PXL_20241223_175840209](https://github.com/user-attachments/assets/adfa3e9c-3db2-49a9-887d-46188f749122)
![PXL_20241223_175848588](https://github.com/user-attachments/assets/edec7c17-9feb-42ed-aeb9-10a6b9ed398e)

#### Option B 

Only works with the smaller 9g/TR4 servo

Link between spindles with m3 rod and link from the servo to the right spindle

![PXL_20241223_180355037](https://github.com/user-attachments/assets/cfa1ff2d-653f-4696-b7fa-20e2778d969c)
![PXL_20241223_180345975](https://github.com/user-attachments/assets/7c215921-1879-4ea2-8750-dd8d424733ac)

### Bellypan

The little tabs on the bellypan are to help align the hood, which requires carefully heating and bending the tabs upward so they stick out from the edges

https://github.com/user-attachments/assets/de6299b1-76f1-442c-9996-66a0bb9452ee


## Remaining work

- Handlebars
- Windsheild
- Tail light for seat
- clean up CAD and release newest CAD

