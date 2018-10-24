# Ender-3
Slicer settings and printed files for the Ender 3

# Slicer Settings

Layer Height: 0.1mm for highest qualtiy but long print time. 0.2mm still produces good quality

Initial layer height: 0.2mm

Wall thickness: Must be a multiple of nossle width, if not layers will have air gaps and won't adhere. 2mm for maximum strength, 0.8mm minimum for non strength critical parts.

Optimize Wall printing order: On

Infill: varies for application. Infill overlap percentage 20%. Infill layer thickness 0.2mm

Material: CCTREE Black PLA 1.75mm: Printing temp: 200, Build plate temp: 60, Flow: 93%

Retraction: 5mm, 60mm/s

Print Speed: Max 60mm/s, use 40mm/s potential slight quality increase.

Travel Speed: 120mm/s

Initial Layer Print Speed: 1/2 Print Speed

 No Z Hop when retracted

Print cooling: 100% fan speed after first layer

Support: Touching build plate only(unless required and can be removed after print), Overhang angle 70°, support density 15%

Experimental Settings: Enable Coasting at 0.096mm^3, 0.1mm^3 Min volume before coasting, coasting speed 90%
