# Build Information Adder

## How was the project created

```script
mvn io.quarkus.platform:quarkus-maven-plugin:3.0.0.CR2:create
     -DplatformVersion=3.0.0.CR2
     -DprojectGroupId=dk.stonemountain.github
     -DprojectArtifactId=build-info-adder
     -DprojectVersion=999-SNAPSHOT
     -DprojectName="Build Information Adder"
     -DprojectDescription="Adds build info to the source code"
     -Ddata="github-action-codestart.github-repository=my/build-info-adder"
     -Dextensions="io.quarkiverse.githubaction:quarkus-github-action:2.0.1"
     -DbuildTool=gradle
```

Afterwards, the 3.0.0.CR2 was changed to 3.0.0.Final

Read this: https://quarkiverse.github.io/quarkiverse-docs/quarkus-github-action/dev/create-github-action.html


