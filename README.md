# How To Install VS Microsoft C++ Building Tools on Windows
This can be used for installing anything that requires C++ compiler on Windows. 

## Installation steps
1. Download Microsoft C++ Build Tools from [here](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
2. Run the installer
3. Get to this screen, click on install
![image](https://user-images.githubusercontent.com/29135514/151630397-a31a450e-b5da-4a01-8568-1b0fac9c1dda.png)
4. Tick the top left C++ build tools, then the boxes on the right would show up. (May differ in versions) !![image](https://user-images.githubusercontent.com/29135514/151630503-d238175e-ea50-4a3b-963d-8c31c465da28.png)
5. Press Install while downloading ![image](https://user-images.githubusercontent.com/29135514/151630625-eea0c784-685e-4e8f-aa67-c47aef7f0d80.png)
6. After everything is installed, **reboot** your computer for it to take an effect.
7. Add MSBuild Tools to your system environment by going to search bar and open *Edit the System Environment Variables*![Untitled](https://user-images.githubusercontent.com/29135514/148818730-4f063261-48c5-4849-8b49-a778fa2ab820.png)
8. Click on Environment Variables <br /> ![Untitled](https://user-images.githubusercontent.com/29135514/148818749-8f3b87a4-feb8-4642-b8a5-620e99c0f2a5.png)
9. Double chlick on Path <br /> ![Untitled](https://user-images.githubusercontent.com/29135514/148818786-30ef3b24-eaaa-423d-aecc-29359d38630b.png)
10. Press New and paste this line: (or version/location u installed your MVS BuildTools at) <br /> `C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\MSBuild\Current\Bin` <br /> simple way to check if this is the right path is paste this file path and check if the location exists in your file explorer. <br /> ![Untitled](https://user-images.githubusercontent.com/29135514/148819086-29e05f2e-9d67-4393-a4da-0f1841f18cdb.png)
11. and you are set!


