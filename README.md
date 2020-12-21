# SpigotVersions

Public list of Spigot versions and their respective api and artifact versions.

## BuildTools

`java -jar BuildTools.jar --rev (version)`

## POM.xml

```xml
<dependency>
    <groupId>org.spigotmc</groupId>
    <artifactId>spigot-api</artifactId>
    <version>(artifact version)</version>
    <scope>provided</scope>
</dependency>
```

## plugin.yml

```yml
api-version: (api version)
```
