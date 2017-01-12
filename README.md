# Airstrike
aircrack-ng gets boring...

# Why?
I got tired of having to airmon-ng start interface, airodump-ng interface and aireplay-ng -0 network ssid just to kick a clinet off my network to test some evilap project I was working on.  Half the time my radio is tuned to the wrong channel and I have to reopen airodump-ng, fix things with iwconfig and such just to make the damn thing work.  Enough bitching about things...

Airstrike streamlines deauthentication workflow in an ease of use package.  Step by step configuration tool automatically ensures you're deauthing on the right channel, allows you to deauth multiple nodes of a roaming network with ease and handles ctrl-c by automatically bringing your radio out of montior mode.  Should work on any systems running Bash and Aircrack-ng.
