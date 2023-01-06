[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=9690113)
# Repository for BITL CS2 lab exercises

![Scala version](https://img.shields.io/badge/Scala-2.12.10-blue)

## Setting up the project

### using git/GitHub Desktop

- Clone your repository (using git, GitHub Desktop or any other tool for managing git repositories)
- Create **New project from Existing Sources** in IntelliJ. Agree to everything it asks :)
- Open the Hello.scala file and configure Java and/or Scala SDK

OR

### using IntelliJ git integration

- Create a **New project from Version Control** in IntelliJ. Agree to everything it asks.
- Log in to GitHub inside IntelliJ
- clone the repository inside IntelliJ (it will take a while!)
- Open the Hello.scala file and configure Java and Scala SDK

## Configuring Java and Scala versions

You should install Java SDK and a Scala plugin for your IntelliJ.

IntelliJ also needs to know where is Java and what version to use, as well as where is Scala and what version to use.

### For Java
After importing the project, if you do not see a notification about missing Java configuration, go to File -> Project Structure -> Platform settings -> SDKs and select Java SDK version to use. If you do not see a Java version there, click on the + button and find the version you installed.

### For Scala 

Open the Hello.scala file, notice a header above the file that suggests installing Scala. Click on it and select your Scala version.

## Doing homework

- create a new package ("folder") and object (file) under `src/main` according to homework instructions
- write your code
- run your code by clicking on the green arrow next to your object or method declaration
- test your code by running your tests by clicking the green arrow next to your test suite

## Turning in your work

- create a new commit with the new changes added (all files under `src/` are mandatory, other files and folders might be needed in some cases, eg some config files)
- push changes to your repository on GitHub
- check that your changes appear on GitHub (meaning your git push worked fine)
