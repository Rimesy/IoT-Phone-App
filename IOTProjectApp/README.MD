# IoT Phone App

Josh Rimes (Student at Cardiff University)

Project start date: 29/01/24

This project builds upon a group project I was part of for my 'CM2211 - Internet of Things' module at Cardiff University. Not all the code is my own.

## Project overview

This is the mobile app side of the project, meant to be installed on an Android phone.
The app itself has been created in .NET MAUI.

### How to run:
These instructions are for Windows devices, but it can also be installed and ran on MacOS and Linux

1. Install [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) and [Visual Studio 2022](https://visualstudio.microsoft.com/en/vs/)
2. When installing Visual Studio 2022, ensure to download the MAUI workload. This can be found under 'Desktop & Mobile' workloads.
3. Install Java 17. The Microsoft distribution can be found [here](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-17)

   **Note**: This must be Java 17 (no newer versions). You are welcome to use your own Java distributions

4. Ensure `java.exe` has been added to the PATH variable.
5. Use [this guide](https://learn.microsoft.com/en-us/dotnet/maui/get-started/first-app?view=net-maui-8.0&tabs=vswin&pivots=devices-android) to install an Android emulator and run the Android app. Note that you must use an API version greater than 34 (I recommend downloading the Google Pixel 6a emulator)

