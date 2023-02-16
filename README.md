# Sasapay/Waas Sdk

>
> Sasa Pay API provides a whole host of products that can facilitate you to improve your business processes and gain a better competitive edge. We expose endpoints for C2B, B2C, B2B, cashback, your customers transactions, and Anti-Money Laundering (AML) . To invoke the API, you can utilize tools such as Postman REST client, curl, and HTTPie. In this documentation, we have included sample code snippets in various languages along with the expected JSON responses..
>


## Documentation
Take a look at the [API docs here](https://developer.sasapay.app).

## Install

Maven:

You can depend on the jars through Maven (from `https://jitpack.io`):
```xml
        <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
...
       <dependency>
	    <groupId>com.github.MusauEric</groupId>
	    <artifactId>sasapaysdk</artifactId>
	    <version>1.0</version>
	</dependency>
```
or sbt:

```
resolvers += "jitpack" at "https://jitpack.io"
// Get all services
libraryDependencies += "com.github.MusauEric" % "sasapaysdk" % "1.0"	
```

or Gradle (Groovy DSL):
```groovy
repositories {
  maven {
    url  "https://jitpack.io"
  }
}

dependencies{
  // Get all services
    implementation 'com.github.SasaPay:sasapay-java-sdk:1.0'
```

or Gradle (Kotlin DSL):
```kotlin
repositories {
    jcenter()
    maven { url 'https://jitpack.io' }
}

dependencies{
  // Get all services
    implementation 'com.github.SasaPay:sasapay-java-sdk:1.0'
}
```




