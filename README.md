
# Material Yamba

## Installation

The following instructions will install a working environment on an bare machine.
Alternatives may work.  See the **Tools** section for specific requirements.

1. Install a JDK: ( http://www.oracle.com/technetwork/java/javase/downloads/index.html ).
Be sure to install a JDK, not a JRE!

2. Install Android Studio  ( http://developer.android.com/sdk/index.html ).

3. Optionally, install git.  There are instructions at
https://help.github.com/articles/set-up-git/ .
Note that git is not required to work with this project, just preferred.

4. Download this repository:
  1. `git clone https://github.com/bmeike/MaterialYamba.git`
  2. Alternatively, at https://github.com/bmeike/MaterialYamba ,
     download a ZIP bundle and explode it.

5. Start Android Studio to complete its installation.

6. Use the SDK manager (menu: Tools > Android > SDK Manager ) to install
the necessary Android SDK components.  The screenshot in the file Tools.png
marks the essentials with red arrows.  They must all be installed.
Optional components are marked with yellow arrows.

7. Start an emulator.  Studio creates one by default, as part of initialization.
Prefer a device, a Genymotion emulator or an Android emulator, in that order,
for testing.  See the tools section below for more on tested devices and emulators.

8. Use "Import Project" to add this project to Android Studio.
Select the MaterialYamba/build.gradle file, and Ok.

9. Run the application (menu: Run > Run 'app' ).

10. After a minute or two, Yamba should run on the emulator.
You should be able to post a message from the Tweet page
and view it, after a short pause, from the timeline view.


## Contents

The repo contains the following branches:
* master: this branch
* other branches to be added later


## Tools

This project was tested using the following tool versions:
* Git: 2.0.1, 2.3.2
* Java: 1.8.0_45
* Gradle: 2.4
* Android Studio: 1.2.2
* Android Gradle Plugin 1.2.3
* Android SDK Tools: 24.3.3
* Android SDK Platform-tools: 22
* Android SDK Build-tools: 22.0.1
* Android Support Repository: 15
* Android Support Library: 22.2
* Devices:
  * Device: Nexus 7 - API22 - 1200 x 1920
  * Emulators:
    * Android SDK: Nexus 5 - API22 - Intel x86 Atom - 1080 x 1920
    * Genymotion: Google Nexus 4 - API22 - Genymotion v2.5.0 - 768 x 1280 
