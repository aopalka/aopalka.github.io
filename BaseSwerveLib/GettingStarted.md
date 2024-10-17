# Getting started with the Library
This library is inteded to be quick and simple to set up and abstract the core of the swerve implementation away enabling teams new to swerve to just "plug" some basic information in and drive.

## What Is needed

- CANivore bus name
- Controller Type ( PS4,PS5, or Xbox)
- Chassis Dimensions
    - Track Width ( Inches )
    - Track Length ( Inches )  
- Speed Limits
    - Module Max Aceleration
    - Module Max Velocity
    - Chassis Max Aceleration
    - Chassis Max Velocity    
- Drive Characteristics ( Defaults can be left untouched )
    - driveKS
    - driveKV
    - driveKA 
- Drive Indicator  
    - Indicator Type
    - Indicator CANBus Name
    - Indicator LED Count    
- Gyro/IMU
    - Gyro Type
    - Gyro CANBus Name
    - Gyro CAN ID  
- Front Left ( MOD0 )
    - Module Properties
        - Module Type
        - Level/Gearing
        - Wheel Circumference
    - Drive Motor
        - Motor Type
        - Idle Mode ( COAST ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Angle Motor
        - Motor Type
        - Idle Mode ( BRAKE ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Absolute Encoder
        - Encoder Type
        - CAN Id
        - CAN bus Name
        - Encoder Offsett
        - Inverted
- Front Right ( MOD1 )
    - Module Properties
        - Module Type
        - Level/Gearing
        - Wheel Circumference
    - Drive Motor
        - Motor Type
        - Idle Mode ( COAST ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Angle Motor
        - Motor Type
        - Idle Mode ( BRAKE ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Absolute Encoder
        - Encoder Type
        - CAN Id
        - CAN bus Name
        - Encoder Offsett
        - Inverted
- Back Left ( MOD2 )
    - Module Properties
        - Module Type
        - Level/Gearing
        - Wheel Circumference
    - Drive Motor
        - Motor Type
        - Idle Mode ( COAST ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Angle Motor
        - Motor Type
        - Idle Mode ( BRAKE ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Absolute Encoder
        - Encoder Type
        - CAN Id
        - CAN bus Name
        - Encoder Offsett
        - Inverted
- Back Right ( MOD3 )
    - Module Properties
        - Module Type
        - Level/Gearing
        - Wheel Circumference
    - Drive Motor
        - Motor Type
        - Idle Mode ( COAST ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Angle Motor
        - Motor Type
        - Idle Mode ( BRAKE ) , don't edit this unless you know what you are doing.
        - Motor CAN ID
        - CAN bus name
        - Inverted
    - Absolute Encoder
        - Encoder Type
        - CAN Id
        - CAN bus Name
        - Encoder Offsett
        - Inverted

## Getting up and Running
One of two methods are available , clone the BaseSwerve Project or start from scratch. 


### Clone BasicSwerve Project
------------------------
This is the most easy and fastest way to get up and running.
Simply :
- Clone the Repository at BasicSwerve [https://github.com/aopalka/BasicSwerve]
- Configure the Swerve with the Configuration Utility [https://aopalka.github.io/BaseSwerveLib/ConfigUtility] save to deploy folder
- Deploy code to robot

### Create from new Project
------------------------
This is more work , follow the steps below to get up and running.
- Add the VendorDep
    - using online vendor package [https://aopalka.github.io/BaseSwerveLib/BaseSwerveLib.json] 
- Configure the Build.gradle
- Input Configuration and Save to Deploy
- Review and add code from the gist located here [https://gist.github.com/aopalka/e046bb0d6f6ede4916e5e72e7144eac2]
- Deploy code to robot