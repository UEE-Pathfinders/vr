# Star Citizen VR Recommendations
This is a breif guide to recommend some settings/options for Star Citizen using VR. Be aware that VR in ***Star Citizen*** is very experimental and the information contained in this guide may not be valuable from one patch to another.  I will do my best to keep it relevant but do not expect miracles.

Special Thanks to all the brilliant minds on [Star Citizen Reddit](https://reddit.com/r/startcitizen) and [Chachi's VR Citizen Discord](discord.gg/kJ9RHRuc6j) who have provided many of the tips and tricks in this guide.

## Headset Calibration
One of the most important things you can do to ensure you have a good VR experience in ***STAR CITIZEN VR*** is to get your headset well placed on your head, comfortable and make sure the physical IPD adjustments (if they are available) are as correct as possible for your unique face and eyes.

1. Ensure the headset rests comfortably on your face, with a VR environment open, try sliding it up and down a bit to see where the ***Sweet Spot*** is where things are sharpest.  Once you find this look up and down with your eyes only.  If it is sharper down or up you may need prescription lenses as you are viewing the environment through stronger magnification at those points.  Keep adjusting in small increments until it is both comfortable and as sharp as possible when looking forward.

2. Use a ruler or tape measure to calculate your ***Inter Pupillary Distance*** (IPD).  This is the distance in centimeters between your pupils.  There are apps that will do this for you, but in my experience they are usually not even close to accurate, but if you have no way to physically measure then use them.
    - Go to a bathroom or hallways mirror that you can lean in and get close to (the closer the better within reason).  Close one eye and line up the `0` mark on your ruler (the cm side) with one of your pupils, try to keep the ruler or tape measure as close to your eye as comfortable for accuracy.
    - Press against your brow or find a way to ensure the 0 mark does not move, then close that eye and open the other.  Take note of the value in cenitmeters that is directly lined up with the center of your pupil that is now open.  Ensure you are looking straight ahead into the mirror.
    - Write down this measurement, it is your IPD and a good thing to remember.

`This whole process is much easier if you happen to have an eye exam and can ask the doctor for your IPD, or have a friend do the measurements while you look straight ahead.`

3. Take this hard won number and with your headset on in its most comfortable position, adjust the ***Physical IPD** for the headset as *close* as possible to your IPD.  Not all headsets have this adjustment, and some offer much finer adjustments than others, for example Quest2 offers three ranges to pick from where Quest3/3s offers a slider between a large range of common IPD.  If your IPD falls outside these ranges, again just go to the maximum as close to your IPD as possible.

Once your IPD has been set on your headset you can again play with the positioning/angle just to make sure its still as sharp as possible.  A good headstrap and facial interface can make a world of difference for this.  Bellow are some recommend accessorie for headsets, but I only own a Meta Quest 3 so if others wish to make recommendations please let me know!

### Headset Accessories
These headset accessories can greatly improve your VR gaming experience in ***Star Citizen*** but are *not* required.  If you can afford them it is recommended for both your comfort and the ability to correctly position the headset for the clearest and most immersive experience.

#### Quest 3 / 3S

##### Head Straps
###### Meta Quest Elite Strap
Meta's own advanced headstrap with or without a battery on the back to help with headset life and balance. (Note when using Virtual Desktop you can go completely wireless so batteries can be nice if you dont mind the extra weight)
* [Amazon - w/ battery](https://amzn.to/3N2QHAN)
* [Amazon - no battery](https://amzn.to/4qb8zI3)

###### BoboVR S3 Pro Battery Strap
This headset is like the swiss army knife of headsets including high capacity 10000mah hot-swappable battery, very comfortable headstrap that really supports the headset and even a cooling fan to keep your Quest 3/3s nice and cool.  It comes at the cost of adding a not small amount of weight, but many say the counterbalance of the battery and the better support makes it feel more comofrtable than default or meta straps.
* [Amazon](https://amzn.to/4aPfAtw)

##### Facial Interfaces
- Something Something Darkside

## Software
It is highly recommended you use [Virtual Desktop](https://https://www.vrdesktop.net/) to stream the game to your headset in most instances. This software uses a wireless network to connect and stream modern codecs such as h.264 or AV1 to provide crisp clear quality, but requires 5ghz or better wireless router that is ideally in the same room in line of sight of your headset, also ideally dedicated to just this job.

If you cannot afford the above or lack the required wireless equipment it will fall to your headsets standard PCVR solution, such as Meta Link for Quest 2/3/3s.  

### Virtual Desktop Settings
If you have a 5-6ghz dedicated router it is recommended under the streaming settings you use H.264+ at 500Mbit for the least latency and highest quality results.  If your network is not capable of supporting that without stuttering or issues and you have a Quest3, use AV1 for the lower bandwidth high quality option.  AV1 has the advantage of being a 10-bit codec so it is very pretty, but more prone to smearing and latency as it is complex to decode for the headset. 



## Star Citizen VR Settings
To play star citizen in VR you should first ensure you are able to run **Vulkan** in game. **DX11** will not work for VR with Star Citizen in its current incarnation. Again be aware this is an experimental feature and a lot will change in coming updates. 

### Console Tweaks
These settings are not cut and paste, you will want to play with these to get markers for QT and ships to look "right".  This is a temporary work around until **CIG** implements something more robust and handles the 2D text layers of the HUD in a way that makes sense for the 3D environment.  The settings below are ***MY*** settings and again you should start with things at a low number and experiment with them till they look good for ***YOU*** as these are dependent on the physical *IPD* settings of your headset and the *IPD Scaling* setting in the menus.


`r_StereoScaleformDepth = 4` - Push the depth of labels out?
`r_StereoUILayerScale = 1.25` - Use this to bring the markers together
`r_StereoUiLensDepth = 20` - This is the same as IPD Scale slider in the VR settings, recommend you use that.

## Bonus Software

### Open Kneeboard

### Other Passthrough App


## Questions & Unknowns
1. How to recenter the theatre screen upon loading VR star citizen.  Sometimes appears far to a side.
2. ?
