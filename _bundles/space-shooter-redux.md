---
title: Space Shooter Redux
bundle_url: "https://github.com/korlibs/korge-free-assets.git::space-shooter-redux::313209df340578f036b81376ade911fb40d4cea4##7abbaa83a7de1da2d38aee9fce8eccc3ecd78fd09e1131b162575fbd477823e7"
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
