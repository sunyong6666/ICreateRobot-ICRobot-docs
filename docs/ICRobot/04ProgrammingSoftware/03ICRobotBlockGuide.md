#ICRobot Block Guide
## Motion
### Move (Forward/Backward/Turn Left/Turn Right) at ( ) power
![](img/IB01.png)

Controls the robot to move in the specified direction at the given power.

Example:

![](img/IB02.png)

### Move (Forward / Backward / Turn Left / Turn Right) at () Power for () Seconds
![](img/IB03.png)

Controls the robot to move in the specified direction with a given power for a certain number of seconds. This is a blocking block.

Example:

![](img/IB04.png)

### Move (Forward / Backward / Turn Left / Turn Right) at () Power for () cm
![](img/IB05.png)

Controls the robot to move in the specified direction with a given power for a specified distance. This is a blocking block.

Example:

![](img/IB06.png)

### (Turn Left / Right) at () Power for () degrees until finished
![](img/IB07.png)



Controls the robot to turn left or right with the specified power until the target angle is reached. This is a blocking block.

Example:

![](img/IB08.png)

### Move Left Wheel at () Power, Right Wheel at () Power
![](img/IB09.png)

Independently control the power of the left and right wheels.

Example:

![](img/IB10.png)

### Move (Left Wheel / Right Wheel) at () Power for () (Seconds / cm)
![](img/IB11.png)

Controls a single wheel to move at the specified power for a given time or distance.

Example:

![](img/IB12.png)

### Move (Left Wheel / Right Wheel) at () Power Continuously
![](img/IB13.png)

Continuously control a single wheel to move at the specified power.

Example:

![](img/IB14.png)

### Stop Movement
![](img/IB15.png)

Stop the robot's motion.

## Display (Matrix LED)
### Set display brightness to (1–10)
![](img/IB16.png)

Set the brightness level of the dot matrix screen (1 = dimmest, 10 = brightest).

Example:

![](img/IB17.png)

### (Static / Scroll Left / Scroll Right / Scroll Up / Scroll Down) Display () for () seconds
![](img/IB18.png)

Show the matrix pattern with the selected animation for a specified duration.

Example:

![](img/IB19.png)

### (Static / Scroll Left / Scroll Right / Scroll Up / Scroll Down) Display ()
![](img/IB20.png)

Continuously display the selected matrix pattern with the chosen animation.

Example:

![](img/IB21.png)

### Display Text ()
![](img/IB22.png)

Display a text string on the matrix; if the string exceeds the matrix width, it scrolls; otherwise, it displays statically.

Example:

![]((img/IB23.png)

### Light up x() y()
![](img/IB24.png)

Turn on the LED at coordinate (x, y); (0, 0) is bottom-left.

Example:

![](img/IB25.png)

### Only light up x() y()
![](img/IB26.png)

Light up only the LED at (x, y), turning off all others.

Example:

![](img/IB27.png)

### Turn off x() y()
![](img/IB28.png)

Turn off the LED at coordinate (x, y).

Example:

![](img/IB29.png)

### Toggle x() y()
![](img/IB30.png)

Switch the LED at (x, y) between on and off.

Example:

![](img/IB31.png)

### Set tail light color（）
![](img/IB32.png)

Change the tail light to a selected color.

Example:

![](img/IB33.png)

### Set tail light color to R() G() B()
![](img/IB34.png)

Set RGB values for the tail light.

Example:

![](img/IB35.png)

### Turn off display
![](img/IB36.png)

Turn off the matrix display.

Example:

![](img/IB37.png)

## Audio
### Upload Audio File
![](img/IB38.png)

Choose and upload a custom audio file, and assign a filename.

![](img/IB39.png)

### Set volume to ()
![](img/IB40.png)

Set playback volume (range: 0–10).

### Play music () until finished
![](img/IB41.png)

Play selected audio file; wait until it finishes before continuing the next action.

Example:

![](img/IB42.png)

### Play music ()
![](img/IB43.png)

Play selected audio file immediately.

Example:

![](img/IB44.png)

### Stop playback
![](img/IB45.png)

Stop the current audio.

### () Play local audio ()
![](img/IB46.png)

Play an uploaded audio file in real-time.

Example:

![](img/IB47.png)

## Actuators
### Gripper (port) (open/close)
![](img/IB48.png)

ontrol the gripper at the selected port.

Example:

![](img/IB49.png)

### Gripper (port) (open/close) until done
![](img/IB50.png)

Control the gripper and wait until action completes before next step.

Example:

![](img/IB51.png)

### Launcher (port) shoot (number) marbles
![](img/IB52.png)

Launch specified number of balls from selected port.

Example:

![](img/IB53.png)

### Launcher (port) shoot (number) marbles until done
![](img/IB54.png)

Launch and wait until finished before proceeding.

Example:

![](img/IB55.png)

## Sensors
### Button (left/right) pressed
![](img/IB56.png)

Detect if left or right button is pressed.

Example:

![](img/IB57.png)

### Sound（）（）
![](img/IB58.png)

Check if detected sound is greater/less than/equal to a value.

Example:

![](img/IB59.png)

### Current sound level
![](img/IB60.png)

Return the detected sound level.

Example:

![](img/IB61.png)

### Current battery level
![](img/IB62.png)

Return remaining battery.

Example:

![](img/IB63.png)

### （）current speed
![](img/IB64.png)

Get current speed of each wheel.

Example:

![](img/IB65.png)

### Privacy switch status
![](img/IB66.png)

Return status of privacy switch.

Example:

![](img/IB67.png)

### （）movement distance
![](img/IB68.png)

Return the movement distance.

Example:

![]((img/IB69.png)

### Set line-tracking sensor to () mode
![](img/IB70.png)

Choose binary/gray/color detection mode.

Example:

![](img/IB71.png)

### Start binary learning for line-tracker
![](img/IB72.png)

Trigger binary mode learning.

Example:

![](img/IB73.png)

### Learn color () for line-tracker
![](img/IB74.png)

Learn a specific color.

Example:

![](img/IB75.png)

### Line-tracker probe () value
![](img/IB76.png)

Get value from probe (L1, L2, M, R2, R1).

Example:

![](img/IB77.png)

### Line-tracker probe () detects ()
![](img/IB78.png)

Check if probe detects specific color.

Example:

![](img/IB79.png)

### Line-tracker probe () value () ()
![](img/IB80.png)

Compare value (>, <, =) to specified number.

Example:

![](img/IB81.png)

### Turn off line-tracking sensor
![](img/IB82.png)

Disable line-tracker.

Example:

![](img/IB83.png)

### Start auto line-tracking at () speed
![]((img/IB84.png)

Begin tracking at low/medium/high speed.

Example:

![](img/IB85.png)

### Start auto line-tracking at () speed until state is ()
![](img/IB86.png)

Auto-tracking continues until all probe values meet target condition.

Example:

![](img/IB87.png)

### Stop auto line-tracking
![](img/IB88.png)

Stop line-following behavior.

Example:

![]((img/IB89.png)




