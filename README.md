RapidMiner Extension Template
=============================

A template project for creating a RapidMiner Studio extension. 

### Prerequisite
* Requires Gradle 8.2.1+ (use the Gradle wrapper shipped with this template or get it [here](http://gradle.org/installation))

* Requires Java 11+

### Getting started
1. Clone the extension template

2. Change the extension settings in _build.gradle_ (e.g. replace 'Template' by the desired extension name)

3. Initialize the extension project by executing the _initializeExtensionProject_ Gradle task (e.g. via 'gradlew initializeExtensionProject')

4. Add an extension icon by placing an image named "icon.png" in  _src/main/resources/META-INF/_. 

5. Build and install your extension by executing the _installExtension_ Gradle task 

6. Start RapidMiner Studio and check whether your extension has been loaded
