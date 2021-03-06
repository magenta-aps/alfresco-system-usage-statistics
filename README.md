Alfresco System Usage Statistics
=============================================

This module is sponsored by Redpill Linpro AB - http://www.redpill-linpro.com.

Description
-----------
This project contains some basic statistics gathering of your Alfresco system

Structure
------------

The project consists of a repository module and a share module packaged as jar files.

Building & Installation
------------
The build produces several jar files. Attach them to your own maven project using dependencies or put them under tomcat/shared/lib.

Repository dependency:
```xml
<dependency>
    <groupId>org.redpill-linpro.alfresco.statistics</groupId>
    <artifactId>alfresco-system-usage-statistics-repo</artifactId>
    <version>1.0.0</version>
</dependency>
```

Share dependency:
```xml
<dependency>
    <groupId>org.redpill-linpro.alfresco.statistics</groupId>
    <artifactId>alfresco-system-usage-statistics-share</artifactId>
    <version>1.0.0</version>
</dependency>
```

Maven repository:
```xml
<repository>
  <id>redpill-public</id>
  <url>http://maven.redpill-linpro.com/nexus/content/groups/public</url>
</repository>
```

The jar files are also downloadable from: https://maven.redpill-linpro.com/nexus/index.html#nexus-search;quick~alfresco-system-usage-statistics


License
-------

This application is licensed under the LGPLv3 License. See the [LICENSE file](LICENSE) for details.

Authors
-------

Marcus Svartmark - Redpill Linpro AB
