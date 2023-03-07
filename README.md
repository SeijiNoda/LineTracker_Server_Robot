# LineTracker Server Robot
> ### Robot that follows a path and dodges obstacules while hosting a web socket server.
> #### Developed in the first semester of 2021 for our final project in TI502 (Robotics).

This is a robot made in the [Webots IDE](https://cyberbotics.com) and programmed in Python designed to have two functionalities:
- <strong>Line Tracker</strong>:<br>
               The robot was programmed in [Python](https://www.python.org/) to follow the black line. It uses 3 infrared sensors in front of the robot to detect its path. <br>
               It also can dodge obstacules found blokcing the path with the help of the distance sensors on the sides. That said, it functions like this:<br><br>
               [![Demonstration Video](https://res.cloudinary.com/marcomontalbano/image/upload/v1623608774/video_to_markdown/images/streamable--hijhav-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://streamable.com/hijhav "Demonstration Video")<br>
- <strong>Web Socket Server</strong>:<br>
               Besides that, our teacher also requested that the robot hosted a socket server that responded an HTTP request with the current image that the camera on top of the robot took.
