Tutorial 1:
A simple robot program that runs the CIM motor using a CANSparkMax
has a bunch of folders except the "build" folder which seems like is not needed idk if some of the other ones are needed

Notice:
  - See how specific robot components are initialized from imported libraries, specifically the CANSparkMax and 
  - How the constructor is called. The constant fed to the constructor is the CANSparkMax's hardware CAN ID. This is found by powering that 
      sparkmax specifically by USB connected to the REV hardware client. 
      You can learn more about it by searching "REV SparkMax" or asking the electrical team
  - See how the XBOX controllers getter function is used to get the joystick value and give that value to the 
  - setter functions of the m_motor object to set the speed of the motor

ALSO NOTE:
  - This program is just to give you a feel for how Object-Oriented-Programming works with using vendor libraries (the things we import at the beginning of the class such as the controller and the CANSparkMax motor controller, 
  - Real FRC robots are NOT programmed all in the Robot.java class. Continue Reading the WPILIB documentation
    - git: https://docs.wpilib.org/en/stable/docs/software/basic-programming/git-getting-started.html
    - introduction to command based programming: https://docs.wpilib.org/en/stable/docs/software/commandbased/index.html
    - read through topics: (the introduction and the first eight topics)
      - What Is “Command-Based” Programming?
      - Commands
      - Command Compositions
      - Subsystems
      - Binding Commands to Triggers
      - Structuring a Command-Based Robot Project
      - Organizing Command-Based Robot Projects
      - The Command Scheduler
:)
