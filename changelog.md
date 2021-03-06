# Quake II RTX Change Log

## 1.1.0

**New Features:**
  * Added music playback support - see the [Readme](readme.md) for instructions.

**Fixed Issues:**
  * Fixed the crash with message "recursive error: bad tail" that sometimes happened at the end of the `biggun` map.
  * Fixed the issue with players spawning at the wrong level entrance after loading an autosave: https://github.com/NVIDIA/Q2RTX/issues/13
  * Fixed the Linux install script to work with spaces in paths: https://github.com/NVIDIA/Q2RTX/pull/1
  * Fixed the interpretation of `pt_fake_roughness_threshold`: https://github.com/NVIDIA/Q2RTX/issues/9
  * Fixed the bright noise that appeared at the end of the `hangar2` map after closing the hangar doors.
  * Fixed the image blurring on FOV changes.
  * Added limits for sky brightness to avoid denoiser artifacts when the sky is too bright.

**Other Improvements:**
  * Re-arranged some menu options to make the menu less confusing.
  * Added the player models from the Quake II shareware demo to the package.
  * Added a menu option to invert mouse controls.
  * Enabled cl_adjustfov by default because that works better for wide screens.
  * Tweaked the tone mapper to make really dark places brighter.

## 1.0.0

**Initial Release**
