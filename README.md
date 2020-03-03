# SolitaireJarDownloader
Jar retriever and runner for solitaire variations

Created by Daniel Duff (dfduff@wpi.edu) and Andrew Levy (amlevy@wpi.edu) 
in partnership with Professor George T. Heineman (heineman@wpi.edu).

Designed to pull JAR files from Github repository: <a>https://github.com/combinators/solitaire-downloads</a>.

All Solitaire variation JAR files were generated using an abstracted Scala-Java CLS framework at <a>https://github.com/combinators</a>

A JAR file exists in the main directory of this project. A version of the launcher can be run directly from that JAR file. 
- Run Command: ```java -jar solitaire-player.jar```

NOTES: 
- Java 8 is reccommended for this version of the GUI launcher.
- If an error regarding a JSON parsing library occurs, be sure to add the json-jar/json-simple-1.1.1 to the classpath.
- If a new version of the launcher jar is to be created, be sure to include both the ```lib``` and ```bin``` directories of a JavaFx SDK download in the JAR's production. 
