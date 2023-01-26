Stereo Audio Codec Breakout - WM8960
========================================

[![SparkFun Audio Codec Breakout - WM8960](https://cdn.sparkfun.com/assets/parts/2/1/0/1/0/21250-_BOB_SparkFun_Audio_Codec_Breakout-_01.jpg)](https://www.sparkfun.com/products/21250)

[*SparkFun Audio Codec Breakout - WM8960 (BOB-21250)*](https://www.sparkfun.com/products/21250)

The SparkFun WM8960 Audio Codec Breakout is a low-power, high-quality stereo codec with 1W Stereo Class D speaker drivers and headphone drivers. The WM8960 acts as a stereo audio ADC and DAC and communicates using I<sup>2</sup>S, a standard audio data protocol (not to be confused with I<sup>2</sup>C). This audio codec is chock full of features some of which include advanced on-chip digital signal processing for automatic level control (ALC) for the line or microphone input, programmable gain amplifier (PGA), pop and click suppression, and its ability to configure I<sup>2</sup>S settings and analog audio path through software via I<sup>2</sup>C. 

The 6x flexible analog input pins allow for a variety of sound source signal types to be routed internally to the ADC inputs. These signal types include line level and microphone level (balanced, and un-balanced) sources. This allows you to accept audio from the sound card on your computer, headphone output of your smartphone, electret microphones, MEMs microphone, etc. The flexible analog signal routing includes PGAs and multiple boost stages so that it can accept a wide range of audio signal levels.

Its efficient class-D driver also means low heat and long battery life when driving 8&ohm; speakers at up to 1W per channel for portable audio applications. As an alternative output, users can also use the audio codec to drive 16&ohm; headphones at up to 40mW for portable audio applications.

Audio feeling a bit... empty? Turn on the 3D enhancement to artificially increase the separation between the left and right channels. In other words, you will feel as if the room is full of sound coming from all directions during playback.  We've written an extensive Arduino Library that allows you to easily control all of the audio codec's features from simple volume control to 3D-enhanced audio playback. 

The board breaks out the WM8960 pins along the edge of the PCB with 0.1"-spaced pins to connect to a breadboard. Utilizing our handy Qwiic system saves you from manually wiring the I<sup>2</sup>C port when configuring the audio codec's settings. A power LED (PWR) is included on the board to indicate when power is applied to the audio CODEC through 3.3V. It can be disabled by cutting the LED jumper on the bottom side. To power the analog (AVDD) and speaker driver (SPKVDD), you will need to include power on the VIN pin. The built-in XC6222 3.3V/700mA voltage regulator regulates the voltage down for the analog circuit. Jumpers for the analog circuit (i..e. AVDD-ISO) and speaker drivers (VIN/SPKVDD) are included for users that want to power each with a separate power supply. 

This board is great for projects that require you to encode or decode audio signals. Add the SparkFun Audio Codec Breakout WM8960 to your next portable digital player or immersive VR game. 

Repository Contents
-------------------

* **/Documents** - Datasheets, additional product information
* **/Hardware** - Eagle design files (.brd, .sch)

Documentation
--------------

* **[Library](https://github.com/sparkfun/SparkFun_WM8960_Arduino_Library)** - Arduino library for the Stereo Audio Codec Breakout - WM8960.
* **[SparkFun Fritzing Part](https://github.com/sparkfun/Fritzing_Parts/blob/main/products/21250_sfe_stereo_audio_codec_breakout_WM8960.fzpz)** - Fritzing diagrams for SparkFun products.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/2761)** - Basic hookup guide for the Stereo Audio Codec Breakout - WM8960.

Product Versions
----------------

* [BOB-21250](https://www.sparkfun.com/products/21250) - Initial Release

Version History
---------------
* v1.0 - Initial Release 

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
