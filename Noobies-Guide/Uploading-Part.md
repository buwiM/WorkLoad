###Using your Gizduino
![](http://i.imgur.com/CqYgN96.png?1)  
**Things you'll need:**
 - A USB type A to B cable (for the old versions, the minis, and the X).  
   ![](http://i.imgur.com/YOtVxTJ.jpg?2)  
   _or_  
   A miniUSB cable (for the newer ones).  
   ![](http://i.imgur.com/hLpVGSB.jpg?3)
 - A USB to UART converter for the Gizduino Mini
 - A Laptop or Computer with the Arduino IDE (whichever version) and the correct drivers installed.  
 
####Uploading your Sketch
 >Future Update: Pics for this part.

 0. **For the GizduinoX, the Gizduino+, and the GizduinoV:**  
      Connect your Gizduino board to your Laptop or PC using your USB cable.  
      >Picture-fitting-description.PNG  

      One of your Gizduino's LED indicator should blink rapidly.  
      
    **For the Gizduino Mini:**  
      Follow the wiring diagram below and connect your USB to UART converter to your Laptop or PC using your USB cable.  
      >miniGizduino-Wiring-Diagram.PNG  
      
      One of your Gizduino's LED indicator should blink rapidly.  
    
    **For the Gizduino MiniUSB:**
      - A jumper should be placed on the J2 jumper pins on the Gizduino MiniUSB board.
        > closeup-shot-of-jumper-placement.png
      
      - Press and hold the **Reset** button and plug in the Gizduino MiniUSB to your USB port.
        >Picture-fitting-description.PNG 
    
      - Release the **Reset** button.
        >Picture-fitting-description.PNG 
      
 0. Launch your chosen Arduino programming software.
    >Picture-fitting-description.PNG 
  
 0. Go to the **File** tab and click on **Open** to load your sketch (.ino file) to the IDE.
    >Picture-fitting-description.PNG 
  
 0. Go to the **Tools** tab and hover over the **Board** option and select the board you're using from the list.  
    >Picture-fitting-description.PNG 
    
  _If you can't find any Gizduino Boards from the selection list, your Arduino IDE isn't patched._
  
 0. Again, go to the **Tools** tab and hover over the **Port** option.  
   >Picture-fitting-description.PNG 
    
  Check if the serial port selection is correct.
    - On Windows using the **Device Manager**.
    - On OSX it should be named something like /dev/tty.usbserial****.
    - On Linux this command "ls /dev/serial/" should list all available USB ports.
  
 0. Next press the **Upload** button or **Ctrl+U** on your keyboard.
    >Picture-fitting-description.PNG 
   
 0. Wait for a bit for your sketch to compile and upload. A few LEDs should be blinking.
    >Picture-fitting-description.PNG 
    
  After a few seconds your code should be running! Happy Coding!
