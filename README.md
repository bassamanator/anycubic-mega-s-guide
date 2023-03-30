# Anycubic Mega S Beginner's Guide
**Todo List**
1. Level your bed. Plenty of videos out there. Just remember to not touch the bed as you slide the paper between the bed and the nozzle. Instead, pinch the paper between your fingers.
2. Calibrate e-steps. https://youtu.be/ZfqeTzc3NpM
3. Import the settings found on this [site](https://cubprin.com/en/how-to-set-up-cura-free-print-settings/) into Cura. They are an excellent starting point.
4. Get some glue stick, you'll need it sooner or later. Don't spend $20 on something bought from a 3D printing store. Get a $1 glue stick from the dollar store. It will last you many months. Apply 6 coats, and wait a couple of minutes between each application; bed should be cold. Apply in one direction only, don't rub the stick back and forth. Horizontal; vertical; diagonally starting from each corner. You want an even application throughout. After the glue stick is dry, **re-level your bed!**
5. Upgrade your [firmware](https://github.com/knutwurst/Marlin-2-0-x-Anycubic-i3-MEGA-S). Be sure to download the appropriate file.
6. PID autotune your hotend and bed. TT.
7. With every filament reel, figure out the correct flow percentage. TT.
8. Tune retraction settings. TT.
9. Figure out flow rate for every filament you use. TT.

**Absolutely Do This**
1. Get proper bed springs like [these ones](https://s.click.aliexpress.com/e/_9y5hks). OD: 8mm, ID: 4mm, L:20mm. This is not only the cheapest upgrade for your printer but also the most important one! ~$2
2. Go over every bolt on your printer and make sure that it's tight (do not over tighten).
3. Configure [Linear Advance 1.5](https://marlinfw.org/tools/lin_advance/k-factor.html) if you print functional parts. It seems intimidating but it's extremely easy to get going. If you simply print models then this can be ignored I suppose. TT.

**Suggested upgrades**
1. 2 mm lead, lead screws. 330 mm length x 8 mm diameter like [these ones](https://s.click.aliexpress.com/e/_98geZW). ~$12 for both.
2. [Spider couplers](https://s.click.aliexpress.com/e/_9fq93e), size 5x8. ~$8 for both.
3. Stepper motor drivers, 2208s are all you need. Price varies but you can get these for as low as $18 for 5. Note, you will need a multimeter to install these properly and you need to be comfortable taking live readings.
4. V6 Hotend like [these ones](https://s.click.aliexpress.com/e/_9xaSg4). If you're serious about this hobby, buy the kit with the copper heat block. Anywhere from $12-50+. 
5. Install a bigger fan to cool the motherboard.
6. The Titan extruder is very decent. A dual drive extruder is nice to have though, but again, it's not necessary. I would recommend getting a BMG clone, you can get one for as low as $13.

**Other Suggestions**
1. Keep extra heatbreaks, nozzles, heatsinks, heat blocks, thermistors, heater cartridges on hand. 
2. Buy PH2.0mm cable ends like [these](https://s.click.aliexpress.com/e/_AYLJ64). < $5.00
3. Buy a soldering iron, the cheapest one you can find is just fine for occasional use.
4. Buy some 2.0 mm heatshrink. Or a kit with many sizes. You can find this for very cheap on aliexpress, something like $2 for 5 m.
5. Buy some metric bolts and nuts, M3 to M5.
6. Hook your printer up to a computer of some kind and install Octoprint. The Raspberry Pi is good for this purpose because it's small, but any computer will do.
7. Buy a few extra [pneumatic connectors](https://s.click.aliexpress.com/e/_9HIA9W). PC4-01. $3 for 5.
8. Buy 2 or 3 extra meters of [PTFE tubing](https://s.click.aliexpress.com/e/_A9WezE), $1.27/m.
9. Doesn't hurt to have some extra [timing belt](https://s.click.aliexpress.com/e/_9JFgDm). Don't buy the $2 belt, buy the $5 belt.
10. Having an extra 3010, 4010, 5010, and 6010 fan doesn't hurt. You can get each for ~$2 on aliexpress. When you have a failure and you need to print, you'll be spending $15 on each buying from amazon.

**Suggested prints**
1. [hotbed cable cover](https://www.thingiverse.com/thing:3363489)
2. [Bed Levelling Knob](https://www.thingiverse.com/thing:3145976)
3. [garbage box](https://www.thingiverse.com/thing:2835257) this one is a must!
4. [hotbed handle](https://www.thingiverse.com/thing:3217199)
5. [Y axis belt tensioner](https://www.thingiverse.com/thing:4309212)
6. [My mounting-things-onto-the-Mega-S system](https://www.thingiverse.com/thing:4865663)
7. [Anycubic i3 Mega Tool Rig](https://www.thingiverse.com/thing:2793693) another must print!
8. [MK4 Direct Drive](https://www.thingiverse.com/thing:4469339) *for advanced users only*
9. [Screw-less Raspberry Pi 4 Case](https://www.thingiverse.com/thing:3723561) It's the best case out there and I've tried several.
10. [Filament Cutter 45° ](https://www.printables.com/model/67509-filament-cutter-45deg)
11. [Filament Clip](https://www.printables.com/model/3458-filament-clip-v8) | [Grandma's Favorite Filament Clip](https://www.printables.com/model/24371-grandmas-favorite-filament-clip)

**Perhaps Useful**
1. A bed levelling sensor of some kind. This is not a necessary at all!

**Recommend Against**
1. Using hair spray. Unless you can control precisely where the hair spray particles go, do not use hair spray for bed adhesion. I shutter to think what the printer and the surrounding area will look and feel like after a couple of weeks of hair spray use.
2. Getting frustrated. There is always a solution out there, it's simply a matter of finding it.
3. Upgrading to external mosfets of questionable quality. It's seems that the mosfets on the motherboard of this printer are adequate and don't even get hot, according to knutwurst (someone far more knowledgeable than I am when it comes to 3D printing). Read about it [here](https://github.com/knutwurst/Marlin-2-0-x-Anycubic-i3-MEGA-S).

**Useful Links**  
[Bed levelling and z endstop screw adjustment](https://youtu.be/6QhUgq4C008)
[Teaching Tech Calibration Site](https://teachingtechyt.github.io/)  
[My designs](https://www.thingiverse.com/bassamanator/designs)  
[/r/AnycubicMegaS/](https://www.reddit.com/r/AnycubicMegaS/)  
[/r/Anycubic/](https://www.reddit.com/r/Anycubic/)  

Always remember, when it comes to 3D printing, **everything affects everything** --GregValiant [Ultimaker Forums].

*Prices in Canadian dollars.*  
*Note, most links are affiliate links.*  
*TT = Teaching Tech Link*
