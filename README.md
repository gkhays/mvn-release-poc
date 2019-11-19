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

## Jenkins

Use Jenkins for build automation. Including the `M2 Release Plugin`.

```bash
docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts
```
