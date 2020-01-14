# DIY-Air-Purifier
A small DIY air purifier using off-the-shelf components for &lt;$100aud.

## Background
![](images/1576814734-MelbourneSmokeHaze.jpg)
In the summer of 2019/2020 Australia is experiencing unprecedented dangerous fire conditions driven by climate change. Much of the east coast of the country south of Brisbane is engulfed in deadly bushfires and air pollution ratings in cities such as Sydney, Canberra, Melbourne and many other regional cities and towns is many times the recommended safe levels of PM2.5 particles. The long term affects of the inhalation of bushfire smoke is mostly unknown at this time, but already people have died from respiratory distress bought about by the smoke-filled air.

There has been a great deal of discussion online and in the media about the use of P2 respirators and home air purifiers to reduce the effects of the bushfire smoke. However, information about the efficiacy of P2 respirators for bushfire smoke is not readily available and what information can be found suggests they may be of limited use. Health officials are continuing to recommend eliminating exposure to PM2.5 particles and bushfire smoke-related chemicals by remaining indoors if possible. Unfortunately for many people the summer heat makes indoors extremely uncomfortable and the evaporative air conditioners installed in many homes in my state of Victoria do not filter the damaging PM2.5 particles from the air. Health officials recommend using HEPA H13 air purifiers, however these are extremely expensive with even a basic unit suitable for a single room costing around $500aud.

With all this in mind I set about finding a way to build a low-cost, effective air purifier that would meet the minimum requirement to filter PM2.5 particles in a bedroom, so that children and at-risk people could at least sleep without  inhaling these dangerous airborne contaminants.

This github sets out the process I followed to construct and test the device, as well as the BOM and 3D print STL files for recreating the device.

## Purpose
The purpose of this project is to create a small air purifier suitable for a bedroom or caravan (or similar sized space) that meets the following critiera:
  - Costs under $100aud to build (in parts);
  - Can be constructed with relatively low levels of technical skill (there is soldering of two wires required);
  - Uses off-the-shelf components available in most Australian cities, or by order over the internet from Australian suppliers; and
  - Uses a HEPA H13 rated filter; and
  - Is powered from a commonly available USB powerbank.

## Method
I selected a readily available HEPA H13 rated filter normally used in cheap vacuum cleaners and available from Bunnings Warehouse. The rest of the air purifier is based around that filter. I then selected a range of 120mm computer fans with relatively high static pressure ratings (>2.0 mmAq) that could operate on 12vDC. As the fans are 12vDC I used a USB 'booster cable' which steps-up the voltage of any USB-A port from 5v to 12v; these cables are available online or from a range of electronics shops such as Jaycar.
After selecting the components I then designed a fan housing using Fusion 360 that provides the interface between the 120mm and the HEPA filter. The filter comes with a removable seal/cover at one end, so I use that end as the base of the unit and fit the fan to the top.
After basic testing with a small smoke generator to ensure the selected fans could draw air through the filter to a reasonable standard I have determined the project suitable for release so others can create their own version of this device both for use in their homes and for further testing.

![](images/Air_Purifier_V2_2020-Jan-13_09-48-57PM-000_CustomizedView1437179471.png)
