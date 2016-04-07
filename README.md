Unify Multi-Protocol Settings in a JAR
======================================

This project, consisting solely of a POM, creates a JAR whose
manifest directs the Cleo Labs Toolchain Shell to properly
configure `system.properties` for the Unify URI and
multi-protocol access to Unify folders using the Unify
"magic host".

To use the JAR, type the following into the Cleo Labs Shell:

```
uri install com.cleo.labs%uri-unify%5.3.0.0-SNAPSHOT
```