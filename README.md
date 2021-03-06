# Soot Tutorial
This is the tutorial for using Soot and Flowdroid to analyze Java and Android application. Also, it can be served as a template for future assignments. Feels free to build up your own project from this tutorial instead of creating the project from scratch.


## Prerequisites
- Intall Java 7 JDK or Java 8 JDK
- Download an IDE: Eclipse or Intellij

## Installation

My suggestion is not to download Soot and FlowDroid separately as it will introduce a lot of inconsistencies between the versions.

Instead, using the prebuilt soot-infoflow-cmd-jar-with-dependencies.jar, which has been packaged all of the necessary .jar files (soot + flowdroid + some other dependencies) into one single bundle, which will make your life easier https://github.com/secure-software-engineering/FlowDroid/releases/download/v2.6.1/soot-infoflow-cmd-jar-with-dependencies.jar.

I have downloaded and put it in here: https://github.com/bdqnghi/Soot-Tutorial/blob/master/lib/soot-infoflow-cmd-jar-with-dependencies.jar. 

Also, for those who want to look into the original source to see how a function is implemented, simply download the source here: https://github.com/secure-software-engineering/FlowDroid/releases/download/v2.6.1/soot-infoflow-cmd-classes-sources.jar and add into the classpath (this step is optional).

Next step is to import the project into the IDE and add the soot-infoflow-cmd-jar-with-dependencies.jar. into the classpath of the project. 
- To import .jar file in Eclipse, you can refer to: https://stackoverflow.com/a/3280384/2760331 
- To import .jar file in Intellij, you can refer to: https://stackoverflow.com/a/1051705/2760331

An example of a correctly imported project can be seen here (in Intellij):
![alt text](/figures/project.png)


## Examples

I have provided 2 simple examples for either Soot and FlowDroid
- ```SootIntroduction.java``` : Load a .jar file and analyze using Soot
- ```FlowDroidIntroduction.java```: Load a .apk file and analyze using FlowDroid

An example output of Call Graph can be found here: https://github.com/bdqnghi/Soot-Tutorial/blob/master/sootOutput/CFGMethod.dot, which you can copy and paste into this visulalization tool: http://www.webgraphviz.com/



