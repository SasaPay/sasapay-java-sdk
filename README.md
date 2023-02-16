# Sasapay/Waas Sdk

>
> This SDK provides convenient access to the Waas and SasaPay API from apps written in Java/Kotlin.
>


## Documentation
Take a look at the [API docs here](https://developer.sasapay.app).

## Install

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




