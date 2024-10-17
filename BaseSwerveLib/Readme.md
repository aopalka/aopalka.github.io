# Swerve README
Hello, this is what I'm calling the "Base Swerve".</br>

- [Swerve Details](Swerve.md)
- [Getting Up and Running](GettingStarted.md)


# BaseSwerve </br>
**Supported Functionality**
----
- [x] CANivore Support
- [x] "Universal" Gyro support </br>
    - [x] Pigeon2 Support </br>
    - [x] NAVX Support </br>
- [x] "Universal" Motor support ( Rev/CTRE/WCP ).</br>
    - [x] Falon500 Support </br>
    - [x] KrakenX60 Support </br>
    - [x] NEO Support </br>
    - [x] Vortex Support </br>
- [x] "Universal" Absolute Encoder support ( CTRE/Helium ).</br>
    - [x] Helium Encoder Support </br>
    - [x] CANCoder Support </br>
- [x] Phoenix 6 API Integration. </br>
- [x] AdvantageKit/Scope Integration. </br>


This code was designed with Swerve Drive Specialties MK4i style modules with other COTS modules.</br>


**Controller Mappings**
----
This code is natively setup to use a xbox controller to control the swerve drive. </br>
* Left Stick: Translation Control (forwards and sideways movement)
* Right Stick: Rotation Control </br>
* Y button: Zero Gyro (useful if the gyro drifts mid match, just rotate the robot forwards, and press Y to rezero)
* B button: Resets Modules to forward.
* Left Bumper: Switches To Robot Centric Control while held
* DPAD Up: Strafe Forward while held
* DPAD Down: Strafe Back while held
* DPAD Left: Strafe Left while held
* DPAD Right: Strafe Right while held