# ShieldsUp GCODE Files
### Arranged by printer type to facilitate novice users getting going quickly

## Format of file names to maintain sense, and sorting:

* _Machine Code_ -Cura assigns three characters, i.e. Creality Ender 3 -> CE3 (we need this so we know what multiple files named the same are for)
* _File Name Printed_
* _Xup_ (number of frames in the print, omitted equals 1) 
* _Layer Height_
* _Infill Setting_
* _Adhesion_ (N=none, S=Skirt, B=Brim, R=Raft)
* _Filament Type_
* _Speed_
* _Hours Minutes_
* _E-TempC_ Extruder Temp
* _B-TempC_ Bed/Base Temp

ie. CE3_Shields_Up_Project_-_SUP_V2__2up_0.2_if30_S_PLA_50mm-s_4h58mins_E-215C_B-62C.gcode
* Creality Ender 3
* Shields_Up_Project_-_SUP_V2
* 2 Frames in the print
* 0.20mm layer height
* Infill 30%
* Skirt
* PLA filament
* 50mm/s print speed
* 4hours 58 minutes expected print time. 
* Extruder at 215degC
* Base/Bed at 62degC

## If you are using Cura
A useful plugin for the Cura slicer that will assist in keeping track of gcodes you produce.

Install the plugin Gcode filename format plugin. In the market place top right of your screen.
After install and restart it will appear in your extensions menu.

This configuration will give you the filing format we're asking for in the GitHub Repo, when you select the plugin and "Edit Format" and paste this in -> [base_name]_[layer_height]_if[infill_sparse_density]_[adhesion_type]_[material]_[speed_print]mm-s_[print_time_hours]h[print_time_minutes]mins_E-[material_print_temperature]C_B-[material_bed_temperature]C

If you have working gcodes and you're on printers other than the UM2/UM2+/ UM5, Ender 3/3Pro, please send J-P Hale a copy in Slack so we can load into GitHub for newbies to help get them going quicker. 

# Shields UP, Stay Safe!

COVID-19 Face Shield is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License. This version is by [Jase] on behalf of Shields Up and based on a work by Prusa Research, available at https://www.prusaprinters.org/social/16-prusa-research/prints.

* gcode files can misbehave on some machines, even when they have been created for your make and model, please watch what it is doing to ensure that it is working as expected. Do Not set and forget until you know it works correctly.
* Do Not use a gcode file from a different printer to yours you may damage your machine.
* Use at your own risk, if in doubt ask an expert!