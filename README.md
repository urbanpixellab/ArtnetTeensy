# ArtnetTeensy

H1 Artnet receiver issues by now

testsetup: sending 8 universes all doing the same, turning on one led per frame -> after 150 leds on it restarts.

network issues: 
Wifi: ping ~ 2-4ms , led animation is stotering but all are working
Cabled network: ping ~0.3ms, led animation are not visible, serial print shows only 0-2 universes are received on the teensy
