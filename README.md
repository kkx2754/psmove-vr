# psmove-vr
A way to play SteamVR games without a real VR headset (kinda).

Do you have old PSMove controllers laying around and an old camera? Well well well, you can finally use them to play VR games! PSMoveVR achieves that by replicating the PSVR functionality so that it works with *every* headset and *every* PCVR game!

WIP - The project is still in it's early develelopement stage, so here's a list of things that I already did and things that I plan to do:

+ ✔ Controller position and rotation tracking
+ ✔ Emulate grip button as the PS Move doesn't have one for some reason
+ ✔ Connection to SteamVR (Hydra drivers and FreePIE)
+ ❌ Compatibility for *every* real VR game

What am I doing right now:
- Switching to another AHRS/IMU library because the old one was a bit off, plus the new one will have magnetometer calibration included so I don't have to program it myself

Future ideas:
- 3D engine in the program so it's more user-friendly
- WinUI3?
- Head tracking using a LED diode and a ping-pong ball
- Joystick on the controller using a hybrid of the JoyCon and the PSMove
