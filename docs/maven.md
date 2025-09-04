# Maven

It is tool for easily fetching the dependencies without worrying about getting the jar libraries manually.

```xml linenums="1"
<project>
	<modelVersion>4.0.0</modelVersion>

    <!-- Project Coordinates -->
    
	<groupId>com.example</groupId> <!-- City -->
	<artifactId>mySpringApp</artifactId> <!-- Street -->
	<version>0.0.1-SNAPSHOT</version> <!-- House (Optional) -->
	<name>mySpringApp</name>
	<description>Demo project for Spring Boot</description>
    
    <dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
            <version>2.8.2</version>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
                <version>9.2.3</version>
			</plugin>
		</plugins>
	</build>

</project>
```
