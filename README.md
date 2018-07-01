Kotlin Private Data Class with Same Name Demo
==============================================

Two files contain private data classes with same name, there will be some compilation errors.

```
./gradlew compileKotlin
```

There will be compilation errors like following:

```
e: /Users/freewind/workspace/kotlin-private-data-classes-compilation-error-demo/src/main/kotlin/example/Hello1.kt: (3, 20): Redeclaration: User
e: /Users/freewind/workspace/kotlin-private-data-classes-compilation-error-demo/src/main/kotlin/example/Hello2.kt: (3, 20): Redeclaration: User
```