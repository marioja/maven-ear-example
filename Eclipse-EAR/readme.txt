This JAR is created by selecting the ModuleEAR project in eclipse
and selecting export EAR.

You will notice that the EJB is called ModuleEJB-1.0-SNAPSHOT.jar
in the EAR file but the META-INF/application.xml (created by Maven)
is com.example-ModuleEJB-1.0-SNAPSHOT.jar.  This is wrong because
the correct name for maven using the maven-ear-plugin version 3.0.0
or later is com.example-ModuleEJB-1.0-SNAPSHOT.jar and not
ModuleEJB-1.0-SNAPSHOT.jar.