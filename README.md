# Virtual Robot
A 2D simulator to help beginning Java programmers learn to program for FTC Robotics.

# How to use this simulator
  1. Make sure you have the Java 8 JDK installed on your PC. Also, install IntelliJ IDEA.
  2. Download the repository zip (or git clone), and extract the contents. Open the project in IntelliJ. You'll see three modules in
     the project (Controller, TeamCode, and virtual_robot). It
     contains the opmodelist and org.firstinspires.ftc.teamcode packages, as well as an virtual_robot.assets directory.
  3. Write your OpModes in the org.firstinspires.ftc.teamcode package; make sure to include a @TeleOp or @Autonomous annotation. These must
    extend the OpMode class (may either extend OpMode OR LinearOpMode). OpMode must provide init() and loop() methods;
     LinearOpMode must provide runOpMode() method.
  4. Make sure at least one gamepad is plugged in to the computer.
  5. Run the application.
  6. Press start-A or start-B on gamepad(s) to select which is gamepad1 vs. gamepad2.
  7. Use Configuration dropdown box to select "Two Wheeled Bot" or "Mecanum Bot". The configuration will be displayed.
  8. Use the Op Mode drop down box to select the desired OpMode.
  9. Prior to initialization, position the robot on the field by left-mouse-clicking the field (for robot position),
     and right-mouse-clicking (for robot orientation).
  10. Use the INIT/START/STOP button as you would on the FTC Driver Station.
  11. If desired use the sliders to introduce random and systematic motor error, and inertia.