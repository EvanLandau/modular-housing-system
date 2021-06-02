Copyright 2021 Evan Landau

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Modular Housing System
Created by Evan Landau

This module system is intended for the construction of houses and other residential structures. It is intended to be highly flexible and can be transported on "lowboy" trucks. Modules can be stacked, and are assumed to be constructed from A500 steel. The modules are connected vertically with HSS segments inside of the larger vertical segments, and then bolts are run through both the inner and outer HSS to hold them in place. Bolts are also used to hold adjacent modules together. The holes for these bolts should be created before shipment to the site, and walls should be welded into their places before shipment. Drywall should be placed between modules. For interior walls between two modules, a single 2.5" thick "inner panel" should be used, and then 1" of gypsum drywall on one side, and a 0.5" resilient clip holding 1" thick gypsum drywall. This should provide a 1 hour fire rating in combination with intumescent paint on steel members not otherwise protected by drywall. The bottom panel should be composed of two 3/4" plywood subfloor panels and then 3" of some flooring material, which combined with a 1" gypsum panel beneath the joists should provide a 1' fire rating.

These modules are designed for either a pile-type foundation or a slab foundation, which can be attached to modules with anchor plates or the same HSS-in-HSS connection used for connecting different stories of a building.

HVAC utilities are provided by bathrooms. Electrical circuit breakers are located atop the ceilings of each module, and should be connected to one another by electrical conduits. No provision has been made for gas piping.

This module passed physical simulations of 3-story-tall construction, wind loads from the side for any part of the US (as listed in the IBC), and earthquake accelerations of up to 2 gs, which all caused some distortion of an unreinforced module, but without any collapse. I also simulated a 50% weakening of the steel due to fire, and a simulated 3-story construction remained standing.

The garage module included interacted in a bizarre fashion with the mechanical simulation, and it is unclear if it will hold up to forces. It also uses a different foundation format, where the HSS segments that support it should be mounted to the foundation by slotting them into larger HSS segments or with anchor plates.

"Core" Modules:
- Basic Module
- Bathroom Module
- Kitchen Module
- Bedroom Module (IRC compliant)
- Bedroom Module (Small)
- Staircase
- Roofing Modules

Other Modules:
- Decking Modules
- Garage
- Hallway Module
- Dining Room
- Long Dining Room
- Sitting Room
- Long Sitting Room
- Kitchen Extension
- TV Room
- Office Module
- Walk-In Closet/Pantry

Wall Cores:
- Basic
- Door
- Small Window
- Awning Window
- Picture Window

The staircases in the decking and stair module are, as far as I can determine, ADA compliant, but due to time constraints, no elevator module has been designed. Most of the "other modules" are fairly arbitrary, and should be treated as examples more than anything else.

The .fcstd files included are intended for use with FreeCAD. The screws used for demonstration in the basic module layout file require the FreeCAD fasteners workbench.
