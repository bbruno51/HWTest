- Forked from original project HWTest for GCW Zero from https://bitbucket.org/clach04/hwtest/wiki/Home
- Edited by bbruno5 at B5 Team

This app is made to test hardware buttons and other functionalities.

= Requirements:
=
This app means that you have Python installed in your PAP KIII Plus. To have it correctly linked, make sure you paste it in:

	/mnt/int_sd/local/python

This guarantee that you'll can use Python on other projects without multi copying the libs and binaries.

= Installation:
=
Copy and paste the directory project to your `/mnt/int_sd/apps` and create a link in gmenu2x / dmenu to HWTest.sh.
All the other needed configs will be made automatically if you follow the requirements and installation steps.

= Features:
=
- Added volume buttons to screen buttons tester.
- Changed layout of screen buttons test, to look like more with hardware design of PAP KIII Plus.

= Known issues:
=
- PAP KIII Plus seems not to have a real joystick hardware, even a software joystick, so it is interpreted like arrow keys when testing or developing.
- G-sensor module was not removed from the app.
- Audio test without headphone outputs audio in just one side, due to single side speaker's PAP KIII Plus.
