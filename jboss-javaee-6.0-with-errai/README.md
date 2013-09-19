JBoss Java EE 6 with Errai
==========================

This BOM builds on the Java EE full profile BOM, adding the Errai framework and the Google Web Toolkit plus its Maven plugin.
 
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.wfk</groupId>
               <artifactId>jboss-javaee-6.0-with-errai</artifactId>
               <version>2.4.0-build-3</version>
               <type>pom</type>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
