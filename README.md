# EasyAVR-Tada68
TADA68/Saber68 support for [Easy AVR](https://github.com/dhowland/EasyAVR).

# Instructions (Windows)
1. Download [EasyAVR](https://github.com/dhowland/EasyAVR), run it once and close it so that `~/.EasyAVR` is created (that's `C:\Users\[USERNAME]\.EasyAVR` for you Windows users).
2. `git clone git@github.com:hillam/EasyAVR-Tada68.git`
3. Navigate using File Explorer or `cli` to the `EasyAVR-Tada68` directory you've cloned from GitHub.
4. Copy `tada68.py` in `~/.EasyAVR/boards` and `tada68.cfg` in `~/.EasyAVR/configs`.
5. Run EasyAVR again and select 'File' -> 'New Layout'. 
6. Select Tada68, and be sure to choose ANSI or ISO in 'Available Layouts' dropdown.
7. After editing your layout, select 'File'->'Build Firmware'. 
8. Choose `\*.bin` as your 'Save as type', and save the file as `FLASH.BIN`. 
9. Press the flash button on your TADA68, and replace the `FLASH.BIN` in the storage location, and press ESC.


## TODO
- [ ] Confirm that my layouts are configured correctly by testing on an actual TADA68...
  - [ ] ANSI
  - [ ] ISO
- [ ] LED support
