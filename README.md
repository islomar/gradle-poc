# Gradle Proof of Concept
Time to learn a little bit about Gradle :-)
https://gradle.org/

## Installation
https://gradle.org/install/
Just use SDKMAN!! :-)


## Tutorials
https://guides.gradle.org/creating-new-gradle-builds/  >> create the basic-demo folder

## Java
https://docs.gradle.org/4.4.1/userguide/tutorial_java_projects.html
https://guides.gradle.org/building-java-applications/


## Maven related links
* https://guides.gradle.org/migrating-from-maven/
* https://gradle.org/maven-vs-gradle/


## Personal notes (basic demo)
* You can visualize and debug your build with build scans
* A project includes a collections of tasks. Gradle tasks are organized into categories.
* `gradle tasks`: it shows you which tasks are available, which ones you can use.
* `gradle wrapper`: generates a Gradle wrapper file. The wrapper is a small script and supporting jar and properties file that allows a user to execute Gradle tasks even if they don’t already have Gradle installed.
* **IMPORTANT**: While Gradle versions are very good about supporting backward compatibility, using a wrapper ensures that the user is working with a version of Gradle that the project creator supports, and is therefore considered a good practice.
* Execute all the tasks: `./gradlew tasks --all`
* Execute the copy task: `./gradlew copy`
* Remove the build directory: `./gradlew clean`


## Personal notes (java demo)
`gradle init --type java-application`


## Plugins
Gradle includes a range of plugins, and many, many more are available at the Gradle plugin portal.


## Best practices
* Use SDKMAN
* Use a wrapper
