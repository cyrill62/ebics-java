Java client for ebics protocol
==============================

The code was synced (with svn2git) and mavenfied

Original Project
----------------

http://sourceforge.net/projects/ebics/

Maven
-----

You need to add the following mirror in your ~/.m2/settings.xml otherwise stax could not be resolved.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<settings>
    <mirrors>
        <mirror>
            <id>simexplorer</id>
            <name>SimExplorer repository</name>
            <url>http://maven.simexplorer.org/repo/</url>
            <mirrorOf>central, SE-springsource-release, SE-springsource-external, SE-IN2P3, SEIS-codelutin, SE-nuiton, SE-restlet</mirrorOf>
        </mirror>
    </mirrors>
</settings>
```

Related Links
-------------

* [EBICS official website](http://www.ebics.org/)
* [EBICS Qualification](http://www.qualif-ebics.fr/)
* [LinuxFR news](http://linuxfr.org/news/enfin-un-client-ebics-java-libre)
