# Snappy jre part for java 8

part for Java 8 runtime. It will use zulu runtime (http://zulu.org) if available for target architecture, 
otherwise it will default to openjdk-8-jre from Ubuntu archive
Environmental variable JAVA_HOME and updated PATH are automatically included for apps.

## How to use
Include provided snap/plugins/x-java-jre.py in your project, then add to snapcraft.yaml
  parts:
    java-jre:
        plugin: java-jre

For additional customisation refer to provided snapcraft.yaml
