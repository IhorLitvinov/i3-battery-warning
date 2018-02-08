i3-battery-warning
==================

Battery warning daemon for i3.
This is a simple battery warning script. It uses i3's nagbar to display warnings.
Daemon sends notification if charge level less than 17 percent. Custom critical level and message may be set at ~/.config/i3batwarn/config. Use "limit=" and "message=" parameters in different lines.

Creating deb package:
0. open terminal in folder with your script

1. install equivs:
sudo aptitude install equivs

2. generate config file:
equivs-control i3batwarn-1.0

3. edit i3batwarn-1.0

4. build package:
equivs-build i3batwarn-1.0

5. install generated package
