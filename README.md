## GUI Application in Java

It configures the compiler to use UTF-8, Java 11

It includes SLF4J as logging API, logback (with ISO8601 timestamps) as logging backend, JUnit 5 for testing, and AssertJ for test assertions.

It copies the dependencies to target/lib, and configures the JAR file with a main class and a classpath,
so that the resulting JAR can be run with `java -jar`.


## Building and run

`cd` `{path of the folder}` to go to the folder where the application is located.

Run into the folder which the application is located `mvn clean package` and check the `target` folder.

Now, run `java -jar target/jukebox-1.0-SNAPSHOT.jar ` and you will see the GUI of my application

## User Manual

![Link to Screenshot from 2023-01-19 18-42-58](https://user-images.githubusercontent.com/92748811/222906951-a55347a5-b4cc-45a0-bcd4-91ebab5802d7.png)

First of all, User should select **Select Folder** button or **Select m3u file** button, for creating a list with mp3 files. If user chooses the **Select Folder** button, he should select a folder that contains the mp3 files that he wants to listen. If user chooses the **Select m3u file** button, he should select a m3u file that contains the mp3 files that he wants to listen. Now, user can select the mp3 file that he wants to listen by pressing the **Select Mp3** button.

After all, he can listen a mp3 file by pressing the **Play** button, he can stop this mp3 file by pressing the **Stop** button and he can resume this mp3 file by pressing the **Resume** button, etc.














