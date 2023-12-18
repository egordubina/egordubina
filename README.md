```kotlin
data class Developer(
    val name: String,
    val age: Int,
    val contacts: List<Social>
)

val egordubina = Developer(
    name = "Egor Dubina",
    age = 18,
    contacts = listOf(
        Telegram(username = "egordubina"),
        Email(username = "egordubina@icloud.com"),
        VK(username = "egordubina"),
        GitHub(username = "egordubina"),
        VK(username = "egordubina"),
        // TODO: Deprecated. Change Twitter to X
        Twitter(username = "egordubina"),
    )
)
```
# Contacts
[Telegram](https://t.me/egorduina)

# About
City: Moscow, Russia<br/>
Education: [School 21](https://21-school.ru)
