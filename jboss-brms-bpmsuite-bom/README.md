JBoss BRMS/BPM Suite BOM
===================================

This BOM contains all supported Maven artifacts for both BRMS and BPM Suite.
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.brms</groupId>
               <artifactId>jboss-brms-bpmsuite-bom</artifactId>
               <version>6.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
