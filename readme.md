## Groovy Koans Project ##


The Groovy Koans project is a collection of small exercises in the form of unit tests, designed to get Java
developers up to speed on Groovy features and common idioms. It starts by teaching you basic Groovy building
blocks, and gradually builds your knowledge towards metaprogramming, slurpers, and all the goodness Groovy has
to offer.

## Getting Started ##
1.  Make sure you have [JDK 1.6+][jdk] installed 
2.  Download the [Koans][groovykoans] package and unzip
3.  Remove the solutions from the Koans using `$ ./gradlew removeSolutions`
4.  Execute Koan01 with `$ ./gradlew koan01` and fail (or any other Koan using `$ ./gradlew koan##`)
5.  Fix code, and execute again
6.  Keep going until you're fluent at Groovy :)

## Q&A ##

#### I like IntelliJ. How can I use it to debug/edit the Koans? ####

* Download and install [IntelliJ IDEA Community Edition][ideac]
* Run `./gradlew idea` from the root of your unzipped Koans
* In IDEA, `File -> Open Project` and open the generated `ipr` file

#### I am forced to work behind a proxy. Can I still run the Koans? ####

The `gradlew` script downloads Groovy and Gradle for you, so you don't have to set up anything by yourself.
To allow gradlew to work through your proxy, simply add the following parameters:
```
$ ./gradlew koan01 -Dhttp.proxyHost=[http proxy] -Dhttp.proxyPort=[http proxy port]
```

#### Are there more Koans planned? How will I know? ####

These are the Koans that are currently planned: 
* Built-in builders (Xml, Html, Swing, Ant)
* Creating your own builder
* SQL and database access
* Testing
* Embedding Groovy

Follow me on [Twitter][twitter] or [GitHub][github] for updates.

## Credits and License ##
The Koan concept started way back in [Zen][zen] practice. It was then adapted by the good folks of
[rubykoans.com][rubykoans] and perfected by [Neo4j][neo4j]. The Groovy Koans project is licensed under the
[Apache 2 License][apache2].


Please feel free to leave comments and pull requests :)

Enjoy!
Nadav

[jdk]: http://www.oracle.com/technetwork/java/javase/downloads/index.html
[groovykoans]: http://groovykoans.org
[ideac]: http://www.jetbrains.com/idea/download/
[twitter]: http://twitter.com/nadavc
[github]: http://github.com/nadavc
[zen]: http://en.wikipedia.org/wiki/K%C5%8Dan
[rubykoans]: http://rubykoans.org
[neo4j]: https://github.com/jimwebber/neo4j-tutorial
[apache2]: http://www.apache.org/licenses/LICENSE-2.0.html