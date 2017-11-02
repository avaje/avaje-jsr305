# ebean-jsr305

Provides class retention based `javax.annotation` `@Nullable` and `@Nonnull` annotations 
purely to annotate Ebean API to assist IDE auto-completion - especially when using Kotlin.

## Provided scope

This maven artifact is expected to be provided scope and hence the annotations use `Class Retention`.
This means that these annotations should not interfere with how a project that depends on Ebean
uses similar annotations.

 