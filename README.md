# Snappy jre part for java 8

part for Java 8 runtime. It will use zulu runtime (http://zulu.org) if available for target architecture, 
otherwise it will use openjdk-8-jre from Ubuntu archive

## How to install
In snapcraft.yaml under the part, add 
  parts:
      my-part:
         source: .
         after: [java-jre]
