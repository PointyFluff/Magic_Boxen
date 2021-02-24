# Magic_Boxen

## What has your space heater done for you lately? Keep you warm?
## Mine pays me for the privilege. 

It's pretty much exactly as one might imagine using an ASIC to heat your house with.


https://github.com/PointyFluff/Magic_Boxen

NOTE: THIS IS FOR INFORMATION ONLY!!!

I AM NOT AN EXPERT! I AM NOT TELLING YOU TO DO THIS.

I AM NOT RESPONSIBLE FOR ANYTHING YOU DO.

ANYTHING YOU DO, YOU DO SO AT YOUR OWN RISK!
ELECTRICITY AND FIRE ARE REAL AND WILL KILL YOU AND YOUR ENTIRE FAMILY!!!!


The Basic Recipe is This:

    Insulated Large Boxen (A large metal cooler would be best, a wood box also works)

    Metal stands to support miner (brackets from hardware store)

    Hole Saw, 100 - 120 MM

    Tapered Hole bit for wiring

    USED ASIC MINER FROM EBAY (got an S9 for $50)

    Power Supply (mine for about $30)

    3-D Printed Air-Flow Baffles, printed with heat-resistant materials. PLA = sadness

    100 - 120 mm dryer vent ducting. + duct tape and or hoose clamps


OPTIONAL (moar audio isolation)

    Some HD Foam

    Some Paving Slabs


Print Baffles (2)

Affix baffles to each end of miner with screws; they go over the fans, I just used the fan screws as mine were long enough

If you opted for foam & paving, place foam first, paving second; for a stable platform for the ASIC miner, otherwise attach metal stands.

Measure the whole placement for baffled miner.

Cut large holes into each end, run the OUTPUT baffled end out one hole; (pokey-outy ;)

The INPUT baffled end can be recessed into the boxen, you may also wish to affix a desiccant system if you live in a very humid environment. (remember, you gotta keep all the electronics cool)

Attach some vent ducting to the pokey-outy baffle. ( I have aprox 2m so I can easily redirect, with a stand made of cardboard + duct tape + glitter glue ).

*NOTE: YOU DON'T WANT THE INPUT AND OUTPUT TOO CLOSE!

FEEDBACK LOOP OF HOT BLUE SMOKE EXIT

OOK! BAD!

If you plan on drawing air in from the outside, then you are gonna need a desiccant system before the input, because the moisture will destroy the ASIC miner; also a filter, or you get to discover REAL bugs in the system and feel just like Grace Hopper!

And if you do any filtering then you are gonna wanna increase the size of your INPUT or add some extra PPV. (remember, you gotta keep all the electronics cool)

(I just keep the unit in a cool room and vent the heat to the rest of the small house)

Drill holes in lid of boxen for running of power & network cable ( You may choose external or internal power supply ).

Affix wires, plug in and see what smokes.


PRO - MODE!!!

( this is still in the very-hacky-might-burn-down-your-house phase. )

    High - Current Opto-Isolated Relay Board.

    ESP32 or RPI

    DHT 11 or similar

Wire each hash board to the power supply via the relay board

Wire DHT to MCU

Attach MCU to netwrok

Run a script to monitor temp and humidity and you can power up or down each hash board for variable temp output. (3 levels in all, I've not tried partial board power, yet)

Add fancy web interface

And, remember...
THIS IS FOR INFORMATION ONLY!!!

I AM NOT AN EXPERT!

I AM NOT TELLING YOU TO DO THIS.

I AM NOT RESPONSIBLE FOR ANYTHING YOU DO.

ANYTHING YOU DO, YOU DO SO AT YOUR OWN RISK!
ELECTRICITY AND FIRE ARE REAL AND WILL KILL YOU AND YOUR ENTIRE FAMILY!!!!
