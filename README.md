# AIRCV Project
## Computer vision project implemented with OpenCV with ML using Mediapipe
 
Have you ever envisioned creating art with the simple wave of your finger? Introducing the Air Canvas—a mesmerizing project that allows you to bring your imagination to life effortlessly. Using the powerful computer vision techniques of OpenCV in Python, we'll embark on a captivating journey to build a dynamic canvas that responds to your every movement.

With color detection and tracking, we'll capture the motion of a colored marker or your hand, creating a virtual palette where gestures become strokes of creativity. Through meticulous morphological operations like erosion and dilation, we'll refine our canvas, ensuring precise tracking and vibrant expression.

But the magic doesn't stop there. By integrating hand landmark detection and tracking, we'll elevate our canvas to new heights of interactivity. Imagine effortlessly sketching ideas or expressing emotions as your hand movements seamlessly translate into art.

The Air Canvas transcends traditional boundaries, offering a fusion of technology and creativity that invites you to explore the endless possibilities of digital artistry. Whether you're a seasoned enthusiast or a curious beginner, this project promises an exhilarating adventure into the world of computer vision.
Here Hand landmarks detection and tracking is used in order to achieve the objective.
So, are you ready to unleash your creativity and embark on this enchanting journey? Join us as we delve into the magic of the Air Canvas and discover the joy of art in motion.

## Algorithm
Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
Prepare the canvas frame and put the respective ink buttons on it. 
Adjust the values of teh mediapipe intilization to detect one hand only.
Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
Finally draw the points stored in array on the frames and canvas .
Requirements: python3 , numpy , opencv, mediapipe installed on your system.

## Practical Implementation
![Screenshot (569)](https://github.com/BTANISHA11/aircv/assets/110708865/be16ef45-a285-4eb6-85dc-d78cacaf2e91) ![Screenshot (568)](https://github.com/BTANISHA11/aircv/assets/110708865/cc27ef86-4aad-47c0-98bf-80d02b964fc4)
