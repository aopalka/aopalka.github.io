# Swerve README
Hello, this is what I'm calling the "Base Swerve".

- [Swerve Details](Swerve.md)
- [Getting Up and Running](GettingStarted.md)


# BaseSwerve
**Supported Functionality**
----
- [x] CANivore Support
- [x] "Universal" Gyro support
    - [x] Pigeon2 Support
    - [x] NAVX Support
- [x] "Universal" Motor support ( Rev/CTRE/WCP ).
    - [x] Falon500 Support
    - [x] KrakenX60 Support
    - [x] NEO Support
    - [x] Vortex Support
- [x] "Universal" Absolute Encoder support ( CTRE/Helium ).
    - [x] Helium Encoder Support
    - [x] CANCoder Support
- [x] Phoenix 6 API Integration.
- [x] AdvantageKit/Scope Integration.


This code was designed with Swerve Drive Specialties MK4i style modules with other COTS modules.


**Controller Mappings**
----
This code is natively setup to use a xbox controller to control the swerve drive. 
* Left Stick: Translation Control (forwards and sideways movement)
* Right Stick: Rotation Control
* Y button: Zero Gyro (useful if the gyro drifts mid match, just rotate the robot forwards, and press Y to rezero)
* B button: Resets Modules to forward.
* Left Bumper: Switches To Robot Centric Control while held
* DPAD Up: Strafe Forward while held
* DPAD Down: Strafe Back while held
* DPAD Left: Strafe Left while held
* DPAD Right: Strafe Right while held