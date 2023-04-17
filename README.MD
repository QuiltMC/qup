# QUP (Quilt Utilities for Parsing) 
A collection of utilities involving data files.

## Modules
### JSON
A simple JSON, JSONC, and JSON5 reader and writer, modeled after GSON's JsonReader and JsonWriter interface.

```kotlin
dependencies {
    implementation("org.quiltmc.qup:json:0.1.0")
}
```
### GSON
An adapter of the JSON module to GSON, allowing QUP JsonReader/Writer objects to be used with methods in the `Gson` class.

```kotlin
dependencies {
    implementation("org.quiltmc.qup:gson:0.1.0") // pulls in correct versions of qup-json and gson
}
```

## FAQ
### Can you add $FORMAT?
Probably! Feel free to open an issue or submit a PR!