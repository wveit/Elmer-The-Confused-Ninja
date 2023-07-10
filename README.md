# Elmer the Confused Ninja

This is a game, written in java and javafx.
It is a running, but unfinished project.
It includes 3 minigames.

### Requirements:

JDK 1.8 with javafx included

- Keep in mind that many java distributions don't include javafx anymore. Corretto, Temurin, and the "regular" Zulu distributions do not include it.
- If you are using [sdkman](https://sdkman.io/) to manage java installations, there is a Zulu distribution that includes javafx (e.g. 8.0.372.fx-zulu)

### Basic instructions to build and run from command line:

- Build the project:
  - Navigate to project root directory in terminal
  - Create a build directory, if it doesn't already exist
    - `$ mkdir build`
  - Use javac to build the project
    - `$ javac -d build -sourcepath ./src src/**/*.java`
- Copy the assets directory into the build directory
- Enter the build directory and run the project:
  - `$ cd build`
  - `$ java application.Control`
