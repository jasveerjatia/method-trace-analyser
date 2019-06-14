# method-trace-analyser
Solution for tracing the methods and analysing it for debugging code

Java based GUI application to parse and compare multiple trace files, to help debugging the code. Method trace is used for post-mortem debugging. It consists of timestamp of entry and exit points for each method invocation. They may also contain stack-trace for each invocation. In case of functionality issues, comparing of the data is used for debugging.

#Functionalities included:

Compare two trace files: one from failing and passing case each and find out the anomaly.
Calculate the execution time of each method and compare the extra time taken. This will be helpful in addressing hang and performance related problems.
Parse one or more trace files and create a tabular view for the number of times each method is invoked.
Compare code-flow and stack trace for failing and passing case and find anomalies.
#Technology Stack: Java, IBM Java Method trace, Eclipse Photon, WindowBuilder, Open JDK with OpenJ9

#Description of files uploaded:

IbmGuiWindow.java - Includes java code for GUI
LogAnalysis.java - Includes java code for implementation of Method-Trace Analyser
SyncPipe.java - Supporting doc for running Xtrace commands in Command Prompt through Java
ideation document - Documentation consisting of idea
ppt  - Presentation based on idea
undertaking.pdf - Documentation of Undertaking
video.mp4 - Video showing implementation of functionalities
#Team Name: EH Cbreak

#Team Details: Jai P Jatia
