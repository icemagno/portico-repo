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
