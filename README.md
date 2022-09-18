# psmove-vr
A way to play SteamVR games without a real VR headset (kinda).

Do you have old PSMove controllers laying around and a PS3Eye? Well well well, you can finally use them to play VR games! PSMoveVR achieves that by replicating the PSVR functionality so that it works with *every* headset and *every* PCVR game!

WIP - The project is still in it's early develelopement stage, so here's a list of things that I already did and things that I plan to do:

+ ❗ Controller position and rotation tracking (position done, rotation in progress)
+ ✔ Emulate grip button as the PS Move doesn't have one for some reason
+ ❌ Connection to SteamVR (preferrably by done drivers and FreePIE)
+ ❌ Compatibility for *every* real VR game

What am I doing right now:
- Switching to another AHRS/IMU library because the old one was a bit off, plus the new one will have magnetometer calibration included so I don't have to program it myself
- FreePIE UDP receiver plugin and hydra emulation script, there's a critical bug in it that it isn't even emulating the hydras.

Future ideas:
- Head tracking using a LED diode and a ping-pong ball
- Joystick on the controller using a hybrid of the JoyCon and the PSMove
