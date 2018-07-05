
 http://www.active-robots.com/ar10-humanoid-robotic-hand
# ar10withWeissTactile

This is a integration of Weiss Tactil sensor with ar10 hand. Only three tactile sensors are used which are placed on thumb, index and ring finger. 

ros_ar10-class.py is the library file where you can define type of finger joint movements. 

ar10_hand_pressurecontrol.py is the main file which reads out tactile sensor pressure as the hand is moving. If the sensor reading goes beyond a specified threshold the hand movement is halted witht he assumption that something has been grabbed or whatever the task is. 
