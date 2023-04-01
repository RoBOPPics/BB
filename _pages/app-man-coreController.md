---
permalink: /coreController/
title: "Core Controller"
toc: true
toc_sticky: true
toc_label: "Contents"
sidebar:
  nav: "appman"
---

## Core Controller

The Core Controller gives you direct control over the BallBOPPer robot. 

When you press Play this Pattern in a Patterns kabob menu, the Pattern is transmitted to the robot, and the Controller pops up automatically in the App. Press PLAY and the robot will begin playing the Pattern. 

![Controller Image](../assets/images/ControllerScreen_500.png){: width="300" .align-center }

The eight buttons at the top of the Controller mirror the functions of the four physical buttons on the BallBOPPer robot.

The top row of buttons in the App: Stop, Pause, Play and Queue; are the same as when you press the identical physical buttons on the robot.

The second row of buttons in the App: Reboot, Reload, Delay and Navigate; are the same as the physical buttons on the robot when you press and hold the button for three seconds.

Reboot will reboot the BallBOPPer's onboard computer. 

Queue is for queueing the Drill or Pattern you wish to play onto the BallBOPPer. Pressing Queue in the App sends you back to the Pattern Libraries where you can select from all of the possibilities in the libraries. You then use the "Queue this Pattern" or "Queue this Playlist" in the Kabob menu on a Pattern or Playlist to transmit and queue the Pattern or Playlist on the BallBOPPer. The BallBOPPer will respond by displaying the 8 character "Display Name" on its LED display. When you press the Queue button on the robot, you can cycle through and select, using the buttons and display on the robot, from the Drills and Patterns that you have previously queued on the robot. This makes it possible to play Drills and Patterns, those that you have previously played on the robot, when on-court without a smartphone or tablet (see the Robot Manual for more details). 

Delay will delay the beginning of the playing of a Drill or Pattern by 15 seconds each time it is pressed. Press twice for a 30 second delay, three times for 45 seconds, etc. 

Locate is used for calibrating the Location system before beginning a training session on an unfamiliar court.

Pressing Reload will present you with three ball reloading options: Zone Control Sweep, Back Court Sweep and Ball Search Sweep.

![Reloader Image](../assets/images/ReloaderOptions.jpg){: width="300" .align-center }

The Zone Control Sweep option gives you manual control over the ball reloading process. When you choose this option, you are presented with the Rover Zone Controller. You use the Zone Controller to send the BallBOPPer to a particular Zone on the court, and it will reload all of the balls it finds there. You can continue to send the BallBOPPer to the zones that contain balls until they are all collected.

With the Back Court Sweep option, the BallBOPPer will sweep the entire area behind the baseline of its side of the court, collecting all of the balls it finds there. 

With the Ball Search Sweep option, the BallBOPPer will use it's onboard cameras to locate concentrations of balls and plan and execute it's own reloading process.

Note that you can switch between these three methods as needed, to expedite the reloading of the balls. Also note that the robot will only reload the balls that are found on it's side of the court. See the Robot Manual for best practices when using the Reloading function.

## Rover

### Rover Zone Controller

The Rover Zone Controller is a positional controller that gives you the ability to send the BallBOPPer to a particular position on it's side of the court. 

![Playlist Image](../assets/images/RoverController500.jpg){: width="300" .align-center }

Press the spot where you want the BallBOPPer to move to, and the BallBOPPer will travel to that spot, shutdown and wait. 

If you are using the Zone Controller in the context of the Zone Controller Sweep function, as explained above, then the robot will reload all of the balls it finds in the destination zone, and then wait to be sent to a different zone to repeat the ball reloading process.

## Settings

The three Settings on this page allow you to turn the Location, Rover and Reloader services On and Off. 

You may wish to not use the Rover and Reloader for various reasons, and you can therefore turn them off. 

![Playlist Image](../assets/images/ControllerSettings500.jpg){: width="300" .align-center }

If you are using the BallBOPPer in a location that is not a tennis court, such as your driveway or backyard, then the BallBOPPer will not be able to determine its location and will indicate an ERROR. 

The only way the BallBOPPer will operate when not on a tennis court is with the Location service turned Off. Also note that when you turn the Location service Off, it also turns Off the Rover and Reloader services. None of these three services will operate if you are not on a tennis court. 

With the Location Service turned Off, you will need to manually position and point the Robot in the correct direction. You may also need to adjust the Launch and Bounce points in your patterns according to the space that is available. 

The Correct Drift settings is specifically for correcting for windy, or other conditions, that are preventing the launched balls from bouncing on their spots. 

You can add or subtract distance, adjust the shots left or right, and elevate them higher or lower. These settings are temporary and revert to the default settings when you turn the BallBOPPer off.


  <nav class="pagination">
      <a href="/BallBOPPer/shotDesigner/" class="pagination--pager" title="Shot Designer">Previous</a>
        <a href="/BallBOPPer/community/" class="pagination--pager" title="Shot Designer">Next</a> 
  </nav>
  

