# ebean-jsr305

Provides class retention based `javax.annotation` `@Nullable` and `@Nonnull` annotations 
purely to annotate Ebean API to assist IDE auto-completion - especially when using Kotlin.

## Provided scope

This maven artifact is expected to be provided scope and hence the annotations use `Class Retention`.
This means that these annotations should not interfere with how a project that depends on Ebean
uses similar annotations.

```xml

<dependency>
  <groupId>io.ebean</groupId>
  <artifactId>ebean-jsr305</artifactId>
  <version>1.1</version>
  <!-- Uses @Retention(RetentionPolicy.CLASS) 
       ... so provided scope expected -->
  <scope>provided</scope>  
</dependency>

``` 