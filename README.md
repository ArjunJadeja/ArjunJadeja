```kotlin
val arjun by lazy {
    human(
        name = "arjun jadeja",
        age = 24,
        setup = setup {
            machine = "macbook air m1 (256gb, 8gb ram)"
            android = "oneplus 7t (256gb, 8gb ram)"
            earbuds = "oppo enco 2"
            chair = "basic recliner"
            table = "sturdy wooden table (with a slick drawer for my diary and laptop)"
        },
        tools = tools {
            notes = listOf("notion", "apple notes", "pen & diary", "stickies")
            design = listOf("figma", "canva", "excalidraw")
            music = listOf("spotify", "youtube music")
        },
    )
}
println("hello 👋")
print("feel free to connect!")
```
