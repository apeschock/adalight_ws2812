Adalight WS2812 w/ Sleep Timer
===============

This is a fork of Adalight WS2812 (https://github.com/Wifsimster/adalight_ws2812) using the FastLED library (v 3.1).
Forked to add a sleep timer. If the serial connection hasn't sent data for the last 5 minutes, the LEDs will turn off and wait.
Also removed the Red, Green, and Blue flashes when initializing.

FastLED library can be found on Github here : https://github.com/FastLED/FastLED
