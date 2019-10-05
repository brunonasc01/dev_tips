**Fix do erro no mvn install**  
>Exit code: 1 - javadoc: error - The code being documented uses modules but the packages defined in http://docs.oracle.com/javase/7/docs/api/ are in the unnamed module.

Inclua a tag abaixo na dependencia do **javadoc**, no **pom.xml**

<configuration> 
    <source>8</source> 
</configuration> 
