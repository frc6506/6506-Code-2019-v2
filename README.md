# 6506-Code-2019-v2
This code has been forked from the outgoing programming lead's repository as of the end of the 2021 FRC season. Property and copyright of FRC Team #6505, Steel Boot Robotics. Visit https://steelboot.weebly.com/contact-us.html if you would like to inquire about using it unless a proper license is has been added to this repository.
Upstream: https://github.com/x64-bit/6506-Code-2019-v2
Team website: https://steelboot.weebly.com
Email Address: FRCteam6506@gmail.com

## Original repository README [Headings Modified]:

Simplified rewrite of the old CommandBased code with TimedRobot implementation. Far easier to debug on the fly (read: actually readable).

### CONTROLS:
- LJoystick - Move
- RJoystick, vertical - Lift/lower arm
- L**bumper**: Intake ball
- R**bumper**: Outtake ball

### NOTES:
- Code does not check for arm positioning. Please be wary when lowering arm all the way down as the motor *will not stop*.
- Former controls were A for Ascend, B for  **B** escend. These were deprecated at Champs in favor of analog controls.
- Similarly, the intake used to use the triggers. Buttons were easier to implement as they didn't require a wrapper class. Don't know why we used them in the first place.
- Thanks to the FTA who helped us w/ this.
- I forgot to upload this the entire summer. Sorry Noah.
