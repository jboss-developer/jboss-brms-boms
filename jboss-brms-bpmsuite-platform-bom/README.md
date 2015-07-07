JBoss BRMS and BPM Suite Platform BOM
=====================================
This BOM contains versions for all supported BRMS and BPM Suite artifacts and also all the 3rd party transitive artifacts
used by the BRMS and BPM Suite.
The use case for this BOM is at places where one needs to depend on some 3rd party artifact and at the same time wants
to make sure it has the same version as is used by BRMS and BPM Suite (to avoid compatibility issues).
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.brms</groupId>
               <artifactId>jboss-brms-bpmsuite-platform-bom</artifactId>
               <version>6.2.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
