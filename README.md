# mvn-release-poc
Release a component using the Maven Release Plugin

```xml
<plugin>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-release-plugin</artifactId>
	<configuration>
		<tagNameFormat>@{project.artifactId}-@{project.version}</tagNameFormat>
	</configuration>
</plugin>
```
