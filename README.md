# Driver_Assist
Many old manual transmission cars lack an interesting feature we see a lot more commonly today: a display with the current selected gear.

Driver assist is a software that uses a camera with live image classification to analyze the shifter position and display show the 
driver their current gear, along with other insight.

This project currently isolates the shifter position as the key metric for its output. In the future the project could include 
and on board imu to detect the current road slope and therefore the possible strain on the car. An extra step would be to tap 
into the cars onboard metrics using the OBD port and the CAN protocol to retrieve the wheelspeed and rpm to further improve the 
reliavility of the feedback.
