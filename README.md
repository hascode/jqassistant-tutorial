# jqAssistant Tutorial

This sample project demonstrates how verify architectural 
constraints with [jqAssistant] by specifying constraints as Cypher queries 
embedded in an AsciiDoc document.

To validate this project, simple run the following command using [Maven]:

```bash
mvn clean package jqassistant:scan jqassistant:analyze
```

The result (failing build) can be viewed in the following [Bitbucket Pipelines Build].

Please feel free to visit my blog at [www.hascode.com] for further information or read the full article [here].

----

**2017 Micha Kops / hasCode.com**

   [jqAssistant]:https://jqassistant.org/
   [www.hascode.com]:http://www.hascode.com/
   [Maven]:http://maven.apache.org/
   [Bitbucket Pipelines Build]:https://bitbucket.org/hascode/jqassistant-tutorial/addon/pipelines/home#!/
   [here]:http://www.hascode.com/2017/12/software-architecture-exploration-and-validation-with-jqassistant-neo4j-and-cypher/
   