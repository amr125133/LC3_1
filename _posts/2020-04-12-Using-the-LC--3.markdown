---
layout: page
title:  "Putting it All Together"
date:   2020-04-12 20:29:56 -0400
categories: jekyll update
---
Now is the exciting part where I will guide you on how to use your text editor with your simulator.

### **Using NotePad++** 
* When using the LC-3 simulator you will be writing all of your programs in NotePad++ and then uploading them as a hex file into the simulator.
* It is important that when your are writing your programm to be using **hex values**. 
  * If you prefer to write your code in binary for practice you must convert the 16 bit binary value into its corresponing hex value.  
* The code you save should look similiar to the picture below. _Note the hex values will not be the same as the picture, this is just an example of how your code should look to be used in the simulator._  
![correct-hex](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/correcthex.PNG)  
* You **must** save your code as a .hex file so that the LC-3 simulator can regognize and use the file.
* At the end of each instruction make sure that there are no spaces after the last hex value or else the LC-3 will give you and error message that looks like the following.
![error-message](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/errorlc3.PNG)

### **Using the Simulator**
1. The application should have been download onto your computer as a exicutable jar file so you should be able to click on it and a window should pop up displaying the LC-3.
  * this is what the .jar file should look like on your desktop  
  ![LC3-icon](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/lc3icon.PNG)

    * This is what the application should look like when it is launched.  
  ![Simulator](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/LC3sim.PNG)

2. In the LC-3 simulator you will see a multitude of **Simulator Controls**. Below are a list of the buttons and thier functionality. Use the picture above as a guide to where these buttons are on the simulator.
* **Reset**: The reset button is used to restart your program. When selecting. 
  * The reset button will also bring you back to the origin of where your instructions started.  
* **Step Into**: This allows you to exicute your program instruction by instruction also going into your subroutines. 
  * If you are having troubles with a program you have written and would like to find the source of your problem _Step Into_ is a useful tool
* **Step Over**: This will allow you to go instruction by instruction but will skip over the subroutine in your instructions.
* **Step Out**: This function will get you to the end of an instruction if your are inside a subroutine. 
  * It will also continue the instructions to the Halt of your programm if you are not inside a subroutine.
* **Continue**: This function plays out all of your instructions in order until the Halt. It is continuous without breaks.
* **Breakpoint**: Using this you can create a break in your instructions or a stop so that the programm will not exicute past a certain point.
* **Jump to MEM**: This allows you to input a location in memory and then the LC-3 will transport you to that point in memory. 
  * This is easier than scrolling to a point in memory but only works if you know the adress.
* **Jump to PC-1**: This function allows the user to go back to the point in the program where the Program Counter is.  
3. **The Console** is used to display output to the user.    
  * For example if you wanted to write a prompt to ask a user to input a key, that message would be displayed here. 
  * You can also print the results of your code to the console. 
  * For example you could print the outcome of 5 + 5 to the console and the user would see 10.

4. To **upload a file** that you have created to be used in the LC-3 simulator follow these steps.
   1. Click File in the top left corner of the window.
    * ![file](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/lc3file.PNG)
    
   2. Next Click the open tab directly under the file tap you just selected. This will open a window for you to find and select your file.
     * ![open](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/openlc3.PNG)  

   3. Now you must select the file you wish to upload to the simulator.  

   4. Next select the Open button to upload your file to the simulator.
     * ![donedeon](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/donedoneLC3.PNG)  

   4. If your file was properly created in NotePad++ it should now be properly uploaded into the memory portion of the LC-3 simulator.   
     * ![finishedproduct](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/finishedproduct.PNG)  
5. There is a **Control Registers section** and a **General Purpose Registers section** of the LC-3 directly under the console. 
  * You can modify any of the registers in both sections by selecting the register you would like to modify.
    * a small window will appear when you have selected the register to change. It will look like the image below.  

     * ![register](https://raw.githubusercontent.com/amr125133/imagesforwebsite/master/registerLC3.PNG)  

  * You can now type the decimal value that you want to place in the register.
  * Click the **OK** button and your decimal value will be converted into a hex value and stored in the selected register.
