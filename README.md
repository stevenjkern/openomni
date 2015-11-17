# omnidocs
Docs related to better understanding omni device communication
=======
##### ** Please note this is a project created to better understand how the omnipod communicates **

#### RF HARDWARE used to RECEIVE transmissions from PDM or Pod
NooElec rtl-sdr usb dongle from Amazon: http://www.amazon.com/gp/product/B00P2UOU72
RFCAT
RFHACK

#### SOFTWARE used with the above hardware to capture wireless signals 
SDR# (SdrSharp) on Windows: http://www.rtl-sdr.com/tag/sdrsharp/
GCRX on Mac

#### SOFTWARE SETUP
Frequency to capture PDM and Pod wireless signals: 433.92 MHz
Encoding: Manchester - signals encoded by a change in state, instead of just low or high
Encryption: 2-FSK
Filter: ?

#### Example signal from PDM to request a Status response from Pod (containing Basal routine, IOB, etc)

We may add more content to the wiki here [Wiki](https://github.com/OmniAPS/Docs/wiki)

#### Stay Up to Date!
Follow us on the slack group here: https://omniaps.slack.com/messages/general/

#### Contributors:
(in no particular order)
* [@t1djoe](https://omniaps.slack.com/team/t1djoe) 
* [DanaMLewis](https://omniaps.slack.com/team/danamlewis)
* [SeattleBrighton](https://omniaps.slack.com/team/seattlebrighton)
* [NightScout](https://github.com/nightscout)
* Thanks for supporting this effort!!

***

***
