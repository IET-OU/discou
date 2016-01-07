discou
======

DiscOU - see http://discou.info

This is the main project fro DiscOU.

- [Build a DiscOU index](https://github.com/the-open-university/discou-indexer)
- [Run a DiscOU server](https://github.com/the-open-university/discou-rest)


#### Maven users
This repository includes also a branch with a maven repository for the java artifcats:

https://github.com/the-open-university/discou/tree/mvn-repo

You can use the maven artifacts by adding the repository to the project pom.xml, or in your the settings.xml, for example in this way:
```
  <profiles>
   <profile>
     <id>discou-mvn-repo</id>
     <repositories>
       <repository>
         <id>discou-mvn-repo</id>
         <name>DiscOU Maven Repository</name>
         <url>https://raw.githubusercontent.com/the-open-university/discou/mvn-repo/</url>
       </repository>
     </repositories>
   </profile>
  </profiles>

 <activeProfiles>
   <activeProfile>discou-mvn-repo</activeProfile>
 </activeProfiles>
</settings>
```
