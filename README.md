# IvyLogViewer - Beta [![Build Status](https://travis-ci.org/ivy-supplements/ivy-log-viewer.svg?branch=master)](https://travis-ci.org/ivy-supplements/ivy-log-viewer)

Started as a simple JavaFX test project, but is actually useful as a small and simple log viewer.

![screenshot](ivy-log-viewer-screenshot.png)

## Requirements
* Java 11 with JavaFX SDK installed (on Linux you need to install `openjfx` in addition to the JDK).
    * Set an environment variable **$JAVA_FX_HOME** pointing to the JavaFX SDK.
* Maven 3 and later for building.

## Installation
Get a built IvyLogViewer from [releases](https://github.com/ivy-supplements/ivy-log-viewer/releases).

## Build
    mvn clean verify

## Run
    cd target/
    java --module-path $JAVA_FX_HOME/lib --add-modules javafx.controls,javafx.fxml -jar ivy-log-viewer-X.Y.Z-SNAPSHOT.jar