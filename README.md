# Precompiled BigBox firmware .hex files

## Flash over USB

Recommended to use XLoader | http://russemotto.com/xloader/

Or with OctoPrint Plugin | https://github.com/OctoPrint/OctoPrint-FirmwareUpdater


## Firmware Versions

ABL - Auto Bed Leveling.

* BigBox v1.0 Dual (Direct Dual) Kickstarter
  marlin_direct_dual.hex

* BigBox v1.0 Pro (Direct Pro) Kickstarter
  marlin_direct_pro.hex

* BigBox v1.1 Dual Hybrid (Titan & Non-Titan)
  marlin_hybrid_dual.hex

* BigBox v1.1 Pro Hybrid (Titan & Non-Titan)
  marlin_hybrid_pro.hex

MBL - Mesh Bed Leveling.

Requires that the IR Sensor be moved to the Heated Bed | https://www.thingiverse.com/thing:1531536

* BigBox v1.1 Dual Hybrid (Titan & Non-Titan)
  marlin_hybrid_dual_mesh.hex

* BigBox v1.1 Pro Hybrid (Titan & Non-Titan)
  marlin_hybrid_pro_mesh.hex
  
## Extruder Steps-Per-MM

To set the Steps-Per-MM via the LCD, press the LCD knob and navigate to Control > Motion > Esteps / mm

  * 0.9° Stepper Motors
    Non-Titan Hybrid Extruders using the larger 0.9° Stepper Motors set the Steps-Per-MM to 304.
    Titan Hybrid Extruders using the larger 0.9° Stepper Motors set the Steps-Per-MM to 835.

  * 1.8° Stepper Motors
    Non-Titan Hybrid Extruders using the smaller 1.8° Stepper Motors set the Steps-Per-MM to 152.
    Titan Hybrid Extruders using the smaller 1.8° Stepper Motors set the Steps-Per-MM to 417.5.
    

