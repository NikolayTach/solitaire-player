# SolitaireJarDownloader
<a href="https://java-nogue.io" rel="nofollow"><img src="https://camo.githubusercontent.com/d7558dcb1235994939a8ab60181d2f940f9057c6c9f12a886b65524a56f156c3/68747470733a2f2f696d672e6573612e696f2f75706c6f6164732f70726f64756374696f6e2f6174746163686d656e74732f31373539362f323032312f30352f31382f3130313539302f31306639623332642d663161622d346633622d613566312d6563666234616630316339392e706e67" alt="nogue" data-canonical-src="https://img.esa.io/uploads/production/attachments/17596/2021/05/18/101590/10f9b32d-f1ab-4f3b-a5f1-ecfb4af01c99.png" style="max-width: 100%;"></a>

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
