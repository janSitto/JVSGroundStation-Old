 # JVSGroundStation - Old

WARNING: This project still works just as expected, but the name "JVSGroundStation" is being migrated to a newer pet project of mine that is more complex, uses better hardware and will be more safe.
The new project rises from issues with latency with this current code arrangement, but if that is not an issue and you're only controlling not dangerous stuff like a rc car, boat or a small indoor fpv quad i'd say its fine.
However, you are responsible for any damage caused related or not related to this software. You have been warned.
If anyone wants to keep developing this, im completely fine with it. But i'd suggest rebuilding it from scratch and doing a proper test battery.

JVSGroundStation is a tool made to be used with t16km flight stick and arduino uno with irx4+ transmitter attached. Still not complete. Use and modify it to use other joysticks/flight sticks at your own risk.

You MUST have a 2s lipo (7.4v) feeding the transmitter and arduino in order to everything work properly.
THIS VERSION NEEDS THE JOYSTICK DEVICE AND ARDUINO CONNECTED BEFORE RUNNING. 
But you can try uncommenting setup_check and commenting setup = 1 to test the work-in-progress feature. (in Main.py)


Credits:
PPM generator code by David Hasko.
