# Soot Tutorial
This is the tutorial for using Soot and Flowdroid to analyze Java and Android application. Also, it can be served as a template for future assignments. Feels free to build up your own project from this tutorial instead of creating the project from scratch.


## Prerequisites
- Intall Java 7 SDK or Java 8 SDK
- Download an IDE: Eclipse or Intellij

## Soot Installation

The first step is to download the Soot .jar file. 

My suggestion is not to download Soot from the official web page: https://www.sable.mcgill.ca/soot/soot_download.html
since the version is outdated.

Instead, building the jar from the latest source code is better: https://github.com/Sable/soot. I have prebuilt one version here: 
https://github.com/bdqnghi/Soot-Tutorial/blob/master/lib/soot-3.0.1.jar. Feels free to use, no need to built from the source code again.

Next step is to import the project and add the soot-3.0.1.jar into the class path of the project

An example of correctly imported project can be seen here (in Intellij):
![alt text](/figures/project.png)


## Example

An quick example can be found in the main file ```SootIntroduction.java```, which simply configures necessary options for Soot, load a sample .jar file (located at /resource/js.jar) and print out all of the methods of a Class.
