# resolve-dctl
Color Transform Lanaguage library providing transforms for Davinci Resolve

Includes:

* S-Curves - Generate S-Curve using various Sigmoid functions
* Mid-Highlight - Green Highlight on Middle Gray at 18% reflectance (40.5 IRE) or selectable IRE at Data Levels
* Mid-Select - Show Mid Gray at 18% reflectance (40.5 IRE) or select IRE at Data Levels; everything else Black
* Blackout - Black Out specified area based on luma
* Whiteout - White Out specified area based on luma
* full2legal - Convert Data signal to Video levels using proper quantization equation
* legal2full - Convert Video signal to Data levels using proper reverse quantization equation
* Channel-Saturation - Adjust Red, Green and Blue saturation based on Upper and Lower thresholds
* Gray-Chart - Generate Chart with Black, Middle Gray and White in Scene or Linear gamma
* Signal-Limiter - Limit clip based on Signal levels
* Luma-Limiter - Limit clip based on overall Luma levels
* Gray-Chart-Extended - Generate Gray Chart + custom defined Peak value (i.e. 1000 NIT); Uses Linear gamma
* Clamp - Clamp values between 0.0 and 1.09
* Clamp-Extended - Clamp values between 0 and 1000
* Step-Ramp - Generate linear ramp with up to 4096 steps and custom scale
* Inverse-S-Curves - Generate Inverted S-Curves using various Sigmoid functions
* Power-Knee - Highlight roll-off based on Power function
* Inverse-Power-Knee - Inverse Highlight roll-off based on Power function
* Quantization - Quantize clip from 1 - 32 bits using Data Level or Video Level


Transforms use Rec.709 Color Primaries where applicable.
Most DCTL files can be used with either a Scene or Linear timeline gamma.


## Installation
Save the DCTL files to the relevant locations based on the host Operating System as noted below:

#### Windows
C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT\

#### Mac
/Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT

#### iPad
LUT folder located within DaVinci Resolve App

#### Linux
/home/resolve/LUT

or

/opt/resolve/LUT

