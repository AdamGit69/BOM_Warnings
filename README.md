I've whipped up (for my own use really) a BOM warning card that I am still working on but thought I'd share anyway cause it works as is now...

It uses HA alerts and just lists the current BOM weather warnings for your area.
It will only show upto 6 warnings but I figured if you're upto 6 then things are  probably pretty full on and you'd know already. lol 

To install you'll need the BOM intergration installed and working at your location and you'll have to edit the YAML linked below to your own location/sensor name. 

Once your home location is set correctly, the BOM integration will make a entity called: "sensor.YOURLOCATION_warnings". You'll need to know this...

Then all you need to do is copy and paste the YAML code from this Github into a new "manual card" (add new card/right down the bottom), editing your location/sensor name to your own. 

In other words, change every instance of "YOURLOCATION" to your location/sensor name.
ie: sensor.melbourne_warnings.
