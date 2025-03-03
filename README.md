# Kasa-Nice
A desktop GUI application for python-kasa to control devices in your local network.

Uses the NICEGUI library to launch a desktop application (or browser, through http://localhost:8080/) from which you are able to control your TP-Link Kasa smart home devices.

Note: the app can only discover devices in your LOCAL NETWORK, it has no access to your cloud account.

Tested on Windows 10 only so far, BUT should work on other OSes as well. Lemme know ;)

![kasa-nice screenshot](Kasa_GUI_Screenshot.png?raw=True)

# How to install
You can download the latest release.

# How to customize
This application is written in Python primarily using the modules Python-kasa, Nicegui and Plotly.


# Supported devices
As supported by the python-kasa module:

Plugs
- HS100
- HS103
- HS105
- HS107
- HS110
- KP105
- KP115
- KP125
- KP401
- EP10

Power Strips
- EP40
- HS300
- KP303
- KP200 (in wall)
- KP400
- KP405 (dimmer)

Wall switches
- ES20M
- HS200
- HS210
- HS220
- KS200M
- KS220M
- KS230

Bulbs
- LB100
- LB110
- LB120
- LB130
- LB230
- KL50
- KL60
- KL110
- KL120
- KL125
- KL130
- KL135

Light strips
- KL400
- KL420
- KL430
