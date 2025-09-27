# Nozzle-Wiper-FLSUN-V400
The nozzle cleaning module is designed to be compact and mounted outside the printable area. It effectively removes filament residue while maintaining the full build volume, and is easy to remove and clean.
If you are working on the FLSUN V400 combined with Boxturtle by glennkaufman
,I believe this design will be a useful addition.

# BOM:
- I use the silicone brush from the Bambu Lab A1
![S70d7733df0c3458fa00cab6be903e6d63](https://github.com/user-attachments/assets/5553a32e-ab44-49d1-b9df-2b99512bc3e6)
- servo 90S (Metal gear version) 
- M3x10 BHCS (2pcs)
- M3 threaded heatset insert (2pcs)
- M4X10 SHCS (2pcs)
- Slider nut M4 (2pcs)
# Note:
 - If you experience the servo jittering during operation, try switching to another 5V PWM signal pin.
 
 - Try testing with the macro program first without enabling the servo. If the position is correct as desired, then test it again combined with the servo mechanism.

 - I think I will add a limit switch to this mechanism soon, as a precaution in case the servo does not rotate to the correct position.
   
 - Provide a separate 5V power supply for the 90s servo, do not connect it to the 5V supply on the mainboard

# Since this is the first version, there are still some flaws, but overall it works well. If you have any suggestions, please share them with me.

https://github.com/user-attachments/assets/cab717e3-aba5-488f-a006-8cfa6793ded9

