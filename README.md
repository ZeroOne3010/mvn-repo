Usage
-----

Add a new repository to the pom.xml of your project, replacing "xxxxxx" with either "snapshots" or "releases":

	<repositories>
		<repository>
			<id>ZeroOne3010-xxxxxx</id>
			<url>https://github.com/ZeroOne3010/mvn-repo/raw/master/xxxxxx</url>
		</repository>
	</repositories>

After that you can add dependencies from this repository as usual. For example:

	<dependencies>
		<dependency>
			<groupId>com.github.zeroone3010</groupId>
			<artifactId>yetanotherhueapi</artifactId>
			<version>0.2.0-SNAPSHOT</version>
		</dependency>
	</dependencies>

or

	<dependencies>
		<dependency>
			<groupId>com.github.zeroone3010</groupId>
			<artifactId>tabular-data</artifactId>
			<version>1.0.0-SNAPSHOT</version>
		</dependency>
	</dependencies>

