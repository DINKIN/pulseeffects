# PulseEffects

Limiter, compressor, reverberation, stereo equalizer and auto volume effects for Pulseaudio applications

![](PulseEffects/images/pulseeffects_main_window.png)
![](PulseEffects/images/pulseeffects_eq_menu.png)
![](PulseEffects/images/pulseeffects_reverb_menu.png)

Effects order:

1. Fast Lookahead Limiter
2. SC4 Compressor
3. Gstreamer Freeverb
4. Gstreamer 10 Bands Equalizer

Required libraries:

- Python 3
- PyGobject 3
- Gtk 3.18 or above
- Gstreamer, Gstreamer Plugins Good, Gstreamer Plugins Bad and Gstreamer Python
 (version 1.0 or above for all of them)
- swh-plugins from Ladspa

Arch Linux package:

[https://aur.archlinux.org/packages/pulseeffects/](https://aur.archlinux.org/packages/pulseeffects/)
