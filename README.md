# EasyAVR-Tada68
Added TADA68 support for [Easy AVR](https://github.com/dhowland/EasyAVR).

# Instructions
1. Download [EasyAVR](https://github.com/dhowland/EasyAVR), run it once and close it so that `~/.EasyAVR` is created (that's `C:\Users\[USERNAME]\.EasyAVR` for you windows users).
2. Place `tada68.py` in `~/.EasyAVR/boards` and `tada68.cfg` in `~/.EasyAVR/configs`.
3. Run EasyAVR again and select 'File' -> 'New Default Layout'. 
4. Select Tada68, and be sure to choose ANSI or ISO in 'Available Layouts' dropdown.
5. After editing your layout, select 'File'->'Build Firmware'. 
6. Choose `\*.bin` as your 'Save as type', and save the file as `FLASH.BIN`. 
7. Press the flash button on your TADA68, and replace the `FLASH.BIN` in the storage location, and press ESC.


## TODO
- [ ] Confirm that my layouts are configured correctly by testing on an actual TADA68...
  - [ ] ANSI
  - [ ] ISO
- [ ] LED support
