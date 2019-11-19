# mvn-release-poc
Release a component using the Maven Release Plugin

```xml
<plugin>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-release-plugin</artifactId>
	<configuration>
		<tagNameFormat>v@{project.version}</tagNameFormat>
	</configuration>
</plugin>
```
