WAT-S 2.0
=========
Web Annotation Tool for Segment Labeling.

This is a further development of WAT-SL from the Webis Group ([Webis](https://www.webis.de)) and not the origin Web Annotation Tool for Segment Labeling.

Usage
-----
Unpack the example.zip and cd into the example project folder. Then use

    java -jar ../wat.jar [<port>]

to start the server on the given port (default port is 2112). You can then access documentation on how to adjust and use the server at

    http://localhost:<port>/index.html


Building
--------
* Convert the project (Eclipse: right klick -> Convert to Maven Project)
* add <classpathentry kind="src" path="resources"/> to the .classpath file 
* Launch configuration: de.aitools.aq.wat.WatServletServer
* Eclipse: Set the path of the example project data ("example-annotation-project-data") in the Run Configurations: Arguments -> Working directory -> other -> .../git/new-WAT-SL/example-annotation-project-data
