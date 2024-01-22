# Autonomous-Car
The project deals with an autonomous car equipped with Raspberry pi and Arduino board along side with DC motors, RPLidar and a Camera. The aim of the project is to learn the operations of RPLidar and Pi camera using Python and OpenCV library. The project includes tasks like mapping using RPLidar, object detection and path following using Pi camera. The final task consists of driving the car on a track wehre the Pi camera leads the car by following the white line on the center of the track, and RPLidar makes sure the car is not moving into any obstracle. 
![Car image](./car_system.jpg)
<br><br>
The Raspberry pi is mounted on the Arduino board as shown in the above picture. On the front, Pi camera is placed for the front view. The RPLidar is placed at the rear end of the car. The sensor is lifted up to get the best readings of the surroundings. The DC motors are placed right below the RPLidar to control the rubber wheels. Below the Pi camera, a metallic sphere is placed which acts a single ball bearing, it helps the car to take turns. The DC motors will control the cars movements. To take turns, the motors will have to programmed accordingly. For example, to take right turn, the left motor will accelerate more compared to the right motor. The DC motors are powered by 9V / 500mAH rechargeable Lithium battery. And the power source for the Raspberry Pi is given by a 5000mAH / 18.5Wh Powerbank.
