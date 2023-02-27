# Sasapay/Waas Sdk

>
> Sasa Pay API provides a whole host of products that can facilitate you to improve your business processes and gain a better competitive edge. We expose endpoints for C2B, B2C, B2B, cashback, your customers transactions, and Anti-Money Laundering (AML) . To invoke the API, you can utilize tools such as Postman REST client, curl, and HTTPie. In this [documentation](https://developer.sasapay.app), we have included sample code snippets in various languages along with the expected JSON responses..
>


## Documentation
Take a look at the [API docs here](https://developer.sasapay.app).

## Install

Maven:

You can depend on the jars through Maven (from `https://jitpack.io`):
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file
```
        <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
Step 2. Add the dependency
```
        <dependency>
	    <groupId>com.github.SasaPay</groupId>
	    <artifactId>sasapay-java-sdk</artifactId>
	    <version>1.0</version>
	</dependency>
```
or sbt:

Add it in your build.sbt at the end of resolvers:
```
 resolvers += "jitpack" at "https://jitpack.io"
 ```
 Step 2. Add the dependency
 ```
// Get all services
```
libraryDependencies += "com.github.SasaPay" % "sasapay-java-sdk" % "1.0"	
```

or Gradle (Groovy DSL):
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file
```groovy
repositories {
  maven {
    url  "https://jitpack.io"
  }
}
```
Step 2. Add the dependency
```
dependencies{
  // Get all services
    implementation 'com.github.SasaPay:sasapay-java-sdk:1.0'
```

or Gradle (Kotlin DSL):

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

```kotlin
repositories {
    jcenter()
    maven { url 'https://jitpack.io' }
}
```

Step 2. Add the dependency
```
dependencies{
  // Get all services
    implementation 'com.github.SasaPay:sasapay-java-sdk:1.0'
}
```




