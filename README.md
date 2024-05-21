# How to install Flutter and Android Studio in your laptop

## 1. Start building Flutter native desktop apps on Windows

https://docs.flutter.dev/get-started/install/windows/desktop

To install the Flutter SDK on Windows, follow these steps:

**Download the Flutter SDK**:

Go to the Flutter official website: Flutter SDK Download

Download the latest stable version of the Flutter SDK

**Extract the Flutter SDK**:

Extract the downloaded zip file to a desired location on your computer, for example, C:\flutter

![image](https://github.com/luiscoco/Flutter_Installation/assets/32194879/64517bd7-7779-49b5-adf9-0de2aec03627)

**Update your Path**:

Add the flutter\bin directory to your system's PATH environment variable

You can do this by following these steps:

Open the Start Search, type in "env", and select "Edit the system environment variables"

In the System Properties window, click on the Environment Variables button

In the Environment Variables window, under System variables, find the Path variable, select it, and click Edit

Click New and add the path to the flutter\bin directory, for example, C:\flutter\bin

Click OK to close all windows

**Run flutter doctor**:

Open a new command prompt or PowerShell window and run the following command to verify your Flutter installation:

```
flutter doctor
```

or 

```
fluter doctor -v
```

This command will check your Flutter environment and display the installation status of dependencies and tools needed to develop Flutter apps

Follow any additional instructions provided by flutter doctor to complete the setup

