# avaje-jsr305

Provides class retention based `javax.annotation` `@Nullable` and `@Nonnull` annotations 
purely to annotate API to assist IDE auto-completion - especially when using Kotlin.

## Provided scope

This maven artifact is expected to be provided scope and hence the annotations use `Class Retention`.

```xml

<dependency>
  <groupId>io.avaje</groupId>
  <artifactId>avaje-jsr305</artifactId>
  <version>1.0</version>
  <!-- Uses @Retention(RetentionPolicy.CLASS) 
       ... so provided scope expected -->
  <scope>provided</scope>  
</dependency>

``` 
