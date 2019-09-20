# PWM Protocol Analyzer for Saleae Logic
Clone this repository to your disk or download and extract the ZIP file.

Open a terminal and type:

    git submodule update

To build on Windows, open the visual studio project in the Visual Studio folder, and build. The Visual Studio solution has configurations for 32 bit and 64 bit builds. You will likely need to switch the configuration to 64 bit and build that in order to get the analyzer to load in the Windows software.

Based on: https://github.com/dustin/logic-pwm  
Differences: Release DLL and Visual Studio project build files.  
Tested: Logic version 1.2.18 on Windows 10 64-bit.
