# cRIOGradle
Support files and template gradle project for continuing to use Java with the cRIO (pre-2015 FRC control system).  This repository includes
the 2014 WPILib and cRIO Java image, along with a template project using gradle as the build tool rather than
ant

## To run netconsole:
java -cp /path/to/sdktoolftp.jar com.sun.spot.sdk.tool.frc.NetConsole console [10.TE.AM.2]

## To use:
1. Clone this repository
2. [OPTIONAL] If desired, move the cRIO-build directory elsewhere
3. Copy the cRIOGradleTemplate directory to whereever you want your project to be, and rename it to
whatever you want the project name to be e.g. myRobot
4. Edit the build.gradle in your project directory (created in step #3) and update the configuration parameters
and/or source location as needed.  There are comments in build.gradle to help guide you in that
5. Import your project into either Eclipse or IntelliJ IDEA using their standard wizards
	* in IntelliJ, click "Import Project", then navigate to your project directory created in step #3
	above and select the gradle build script (build.gradle).  The import wizard will then take you
	through the remaining steps
	* in Eclipse, select File->Import, Gradle Project, and	select your project directory created 
	in step #3 above as the project root.  The wizard will then take you through the remaining steps
