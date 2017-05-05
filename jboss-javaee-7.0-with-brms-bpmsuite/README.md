JBoss Java EE 6 with JBoss BRMS and Jboss BPM Suite
===================================

This BOM builds on the Java EE full profile BOM, adding JBoss BRMS and JBoss BPM Suite.
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.brms</groupId>
               <artifactId>jboss-javaee-6.0-with-brms-bpmsuite</artifactId>
               <version>6.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
