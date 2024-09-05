```kotlin
val arjun by lazy {
    human(
        name = "Arjun Jadeja",
        age = "24",
        setup = setup {
            machine = "💻 MacBook Air M1 (256GB, 8GB RAM)"
            android = "📱 OnePlus 7T (256GB, 8GB RAM)"
            earbuds = "🎧 Oppo Enco 2"
            chair = "🪑 Basic Recliner"
            table = "🛠️ Sturdy Wooden Table (with a slick drawer for my diary and laptop)"
        },
        tools = tools {
            notes = listOf("📝 Notion", "🗒️ Apple Notes", "✒️ Pen & Diary", "🖥️ Stickies")
            design = listOf("🎨 Figma", "🖌️ Canva", "✏️ Excalidraw")
            music = listOf("🎵 Spotify", "🎶 YouTube Music")
        },
    )
}
println("Hello 👋")
print("Feel free to connect!")
```
