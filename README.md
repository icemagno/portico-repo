# portico-repo
Maven Repository for PorticoRTI


Add this to your POM file ( Repositories Section )
```
<repository>
	<id>portico-repo</id>
	<name>PorticoRTI Repository</name>
	<url>https://raw.githubusercontent.com/icemagno/portico-repo/master</url>
	<releases>
	    <enabled>true</enabled>
	    <updatePolicy>never</updatePolicy>
	</releases>
	<snapshots>
	    <enabled>false</enabled>
	</snapshots>
</repository>		
```    
and then choose your flavour (2.2.0 or 2.1.0)
```
<dependency>
	<groupId>org.portico</groupId>
	<artifactId>portico</artifactId>
	<version>2.2.0</version>
</dependency> 
```

If you choose to use the 2.2.0 version then you will need some other dependencies:
```
<!-- Add Log4j2 Dependency -->
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-log4j2</artifactId>
</dependency>

<!-- https://mvnrepository.com/artifact/org.bouncycastle/bc-fips -->
<dependency>
    <groupId>org.bouncycastle</groupId>
    <artifactId>bc-fips</artifactId>
    <version>1.0.2</version>
</dependency>
<!-- https://mvnrepository.com/artifact/org.jgroups/jgroups -->
<dependency>
    <groupId>org.jgroups</groupId>
    <artifactId>jgroups</artifactId>
    <version>4.0.10.Final</version>
</dependency>
```
May have some others but this worked for me until now.

