# NoteBlockAPI
For information about this Spigot/Bukkit API, go to https://www.spigotmc.org/resources/noteblockapi.19287/

Dev builds are available at [Jenkins](http://ci.haprosgames.com/job/NoteBlockAPI/ "Jenkins")

###Repository
#### Maven
```xml
<repositories>
    <repository>
        <id>splashmc-public</id>
        <url>https://maven.splashmc.tech/repository/splashmc-public/</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.xxmicloxx</groupId>
    <artifactId>NoteBlockAPI</artifactId>
    <version>1.6.2-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```
#### Gradle
```groovy
repositories {
    repository {
        maven {
            url = uri('https://maven.splashmc.tech/repository/splashmc-public/')
        }
    }
}

dependencies {
    compile 'com.xxmicloxx:NoteBlockAPI:1.6.2-SNAPSHOT'
}```