---
title: Space Shooter Redux
bundle_url: "https://github.com/korlibs/korge-free-assets.git::space-shooter-redux::313209df340578f036b81376ade911fb40d4cea4##bdb3ed203e90a9827608e4a7bbb5f30a8b9cd03408a3b5be75c07df3e98e4ebe"
author_url: https://opengameart.org/content/space-shooter-redux
license: CC0
author: Kenney
required_vars: []
platforms: [common]
category: assets
icon: space-shooter-redux.png
---

Space-related backgrounds, spaceships, fonts and sounds.

Sample code (views decorators/builders prefixed with `spaceShooterRedux`):

```kotlin
import spaceredux.*

suspend fun main() = Korge(width = 512, height = 512, bgcolor = Colors["#2b2b2b"]) {
    //spaceShooterRedux.putBackground(SpaceShooterReduxBackground.Type.BLUE, speedX = 2.0, speedY = 1.0)
    spaceShooterRedux.putDemoCode()
}
```
