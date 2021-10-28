# youtube-data-api

- Language: Java
- Input search argument from the command line.
- Search YouTube videos using the specified keyword and output in a list.

# Requirement
- Install Java
- Install Gradle

# Usage
- Change `youtube.apikey` in **youtube.properties** file to the key taken from Google Cloud Console.
- Build and run application.
    - On Windows:
        - Run **build-app.bat** to build project.
        - Run **run-app.bat** to run the application.
    - On Linux:
        - Run **build-app.sh** to build project.
        - Run **run-app.sh** to run the application.
    - Manually:
        - Run `gradle clean build fatJar` in application folder location to build project.
        - Run `java -jar app/build/libs/youtube-data-api.jar` in application folder location to run the application.
- Input search query and press Enter.
