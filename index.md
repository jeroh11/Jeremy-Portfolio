# Camera Gimbal
This project details the system of a 3D printed camera gimbal that stabilizes a user's video footage using MPU sensors, servoes and an Arduino board. The project was built with improvisation on parts such as nuts and bolts, as well as a power source, to complete and finalize building. The process of building this entire system provided knowledge on coding and basic engineering such as soldering and wiring from a source such as USB. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Jeremy H | Saratoga High School | Electrical, Firmware and Mechanical Engineering | Incoming Sophmore

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
-->

# Final Milestone
<!--For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->

# Second Milestone
For my second milestone, I achieved the basic completion of my project and the succesful functions of the components as a whole. I uploaded specific code to the my Arduino board, which powers the MPU6050 accelerometer, which controls the gyro values of the device. I have an external source of electricity, a power bank, which powers the servos to coordinate with the accelerometer to stabalize movement on the gimbal. The biggest issue with the completion of the device was a consistent amount of errors with the servos while testing, as the servos started to move unnesscesarily, which I am troubleshooting with the hopes of pinpointing and fixing in the near future. Currently, I assume that the problem has to do with the placement of the wiring that binds the components together, which is inconsistent in length and can tug along the servo's wires, creating errors.

<iframe width="560" height="315" src="https://www.youtube.com/embed/FN5Kb476y0Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
For my first milestone, I achieved two key points to my project: To successfully aquire my MPU6050 accelerometer readings and then visualize their readings in real time with a coding software called processing. Something I definitely did not expect was the amount of troubleshooting that I had to complete in order to achieve my milestone, as the code being used had many errors that affected the readings of the component. The code I implemented included error values to counter drift that the accelerometer would pick up over time, which were wrong. I had to find the exact error values of the X, Y and Z readings to get accurate readings through guessing and checking. 

This is the code that visualizes the readings of the MPU onto Processing:
![Headstone Image](Capture.PNG)
The code takes the code from the Arduino board and creates a model of the breadboard the accelerometer and Arduino is pinned into and changes it in real time according to the readings of the accelerometer.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_8qPUXlMU-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project
For my starter project, I built a board featuring the classic game of Simon Says. This project includes working with a basic components such as a microcontroller, resistor and capacitor. In addition, the board required basic soldering to complete and function, which was the biggest obstacle I faced while working on this Simon Says board. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/s5TrzVyCpa0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
<!--Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

# Code
<!--Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->
# Bill of Materials

| **Part** | **Purpose** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| MPU 6050 IMU | Accelerometer for Gyro Detection and Stabilization | $9.99 | <a href="https://www.amazon.com/HiLetgo-MPU-6050-Accelerometer-Gyroscope-Converter/dp/B00LP25V1A?crid=EPJ36BB9OJLO&keywords=MPU-6050&qid=1664878452&qu=eyJxc2MiOiIyLjkwIiwicXNhIjoiMi45NSIsInFzcCI6IjIuOTcifQ%3D%3D&sprefix=mpu6050,aps,266&sr=8-3&linkCode=sl1&tag=howto045-20&linkId=a10e35b9e08344c4716bc03a15f70908&language=en_US&ref_=as_li_ss_tl"> Link </a> |
|||||
| MG996R Servo | Device Arm Movement | $15.99 | <a href="https://www.amazon.com/YoungRC-MG996R-Torque-Digital-Helicopter/dp/B07PBJ1L8F?crid=U460WD9J18O5&keywords=MG996R&qid=1668338350&sprefix=mg996r,aps,470&sr=8-10&linkCode=sl1&tag=howto045-20&linkId=da31e960c0d15fb4970dcb1c3c0542ac&language=en_US&ref_=as_li_ss_tl"> Link </a> |
|||||
| Arduino Nano Board | Holds All Code and Function | $26.00 | <a href="https://www.amazon.com/Arduino-A000005-ARDUINO-Nano/dp/B0097AU5OU/ref=as_li_ss_tl?keywords=arduino+nano&qid=1554818901&s=electronics&sr=1-4&linkCode=sl1&tag=creativity02-20&linkId=b9db1fe83cb2f834ad5f8d01ece300cd&language=en_US"> Link </a> |
|||||
| Anker Power Bank | Provides Power to Device | $17.99 | <a href="https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y/ref=sr_1_11?crid=2NBYWOCLV5SOO&keywords=anker+power+bank+5+volt&qid=1687464871&sprefix=anker+power+bank+5+vo%2Caps%2C169&sr=8-11"> Link </a> |

# Other Resources/Examples
<!--One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
