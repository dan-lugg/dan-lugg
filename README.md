<!--suppress HtmlDeprecatedAttribute -->

<p align="center">
    <img src="./assets/luggsoft-dan-lugg.png?raw=true" alt="dan-lugg" />
</p>


```kotlin
object Dan : Engineer, Person(
    currentRole = "Software Engineering Manager",
    currentArea = "Ontario, Canada",
) {
    override val technology = listOf(
        "typescript",
        "kotlin",
        "csharp", 
        "fsharp", 
        "java", 
        "php",
    )
}
```
