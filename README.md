# SimCar
## **Description:**
SimCar is a project based around teaching myself some vehicle dynamics while learning more C++ and possibly unreal engine support. It will take a car's parameters and use them to simulate an ideal lap around a circuit. 


## **Objectives:**
### **1. Simulate a car with given physical parameters (spring stiffness, mass, cog, etc.)**
Ideally this will culminate in a simulation of a car driving around a given track, allowing for tuning of a car without relying on the driver for feedback. The laps returned will be consistent and deterministic. The fidelity of this model will start low and hopefully increase given more time and experience. Ultimately this could be used as a sort of test bed for car setups in Assetto Corsa or something similar. See Progress Plan for details.

### **2. Display the car's progress through a lap**
This can be a simple display, a dot moving along a line in the shape of the track to indicate progress. It would also be beneficial to display the car's bearing, and various statistics of the car (spring travel at each corner, speed, etc.)

### **3. Have fun!**
This project shouldn't be too stressful. Have fun with it and learn something. There aren't any deadlines yet. Just fiddle and learn.


## Progress Plan:
### **1. Straight Line Acceleration, unsprung, no ui**
Simulate a car starting from stop, going a certain distance, and maybe stopping in a certain distance. No UI is necessary unless you want to dig into Unreal stuff early. The main goal is to get back in the swing of C++ and learn how the objects work! 

### **2. Straight Line Acceleration, Sprung, No UI**
Add in the challenge of simulating a simple quarter-car model going forward. 

### **3. Straight Line Acceleration, Sprung, with a simple UI**
Learn more about Unreal Engine or other physics engines. See if you want to use them to do some of the computing or if you want to homebrew all the physics. Homebrewing will be fun, but Unreal may be nice for a UI. Also check out other options.

### **4. Add some curves!**
Figure out the physics of anti-roll bars, steering, etc. around a simple constant-radius corner. This doesn't require vector import of a track layout or anything, just be able to figure out the max speed the car can handle through the corner.

### **5. Corner approach, entry, apex, and exit**
Now you need to start figuring out how to get through a more complicated corner. It's not going to be easy from here, calculate the maximum constant-speed through each point of the curvature, then account for speed changes in transition? Start at apex, work outward? then need to iterate through corner speeds smartly to navigate the corner and figure out braking points! 

### **6. Import a track.**
Figure out how to create a vector graph of the driving line, and then make that the input to the simulator. 

### **7. Become a programming god.**
Using these tools, figure out the fastest line through a track. This would be ridiculously difficult, but neat! No getting your hopes up.