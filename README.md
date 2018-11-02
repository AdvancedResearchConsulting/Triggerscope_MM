# Triggerscope_MM
Metamorph Driver for Triggerscope Device Controllers
Initial Release 

***This is the 57,600 Baud version of the driver***

To install:
  1. Copy both the txt file and the DLL to your C:\MM directory
  2. Attached your triggerscope, and locate the COM number it's using by checking the windows device manager.
  3. MAKE SURE you are using com # 1-9, but not any higher #. 
  4. Open the triggerscopeCOM.txt file and enter the COM # for your triggerscope.
  5. Save and close the file. 
  6. Open Metamorph, and add the mm "custom driver". In the DLL file path enter the triggerscope dll location. 
  7. close and reopn the driver. 

You should now have devices populated in the driver. If not:
  - check that you have Microsoft Visual Studio C++ Runtime 2017 installed.
  - Any issues check the output in the debug file which is created when the triggerscope is used. 
  - It's located in c:\mm. 
  - For support email Austin Blanco, at Advanced Research Consulting - austin@austinblanco.com
  
