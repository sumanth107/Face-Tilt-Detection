# Tilt-Face-Detection
Determines the angle of tilt of face in an image or video (here webcam live feed)
   
![demo.gif](demo.gif)
  
Here, the program not only detects face and eyes but also shows the angle of tilt. The base logic behind calculating angle of tilt is *The angle between lines is same as the angle between their perpendiculars* .  
Assuming the line joining the centres of two eyes is perpendicular to face, we determine the change in the angle of line joining eyes. This angle will precisely be equalt to the angle of tilt of the face.
