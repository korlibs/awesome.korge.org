---
title: Space Shooter Redux
bundle_url: "https://github.com/korlibs/korge-free-assets.git::space-shooter-redux::531e1bd6a588358266f1815daa143bd057ed6841##b31b6f1e1f4b96209ec22dc422fa95b2e77173736a093db0aeeb7ee50a937e16"
bundle_link: https://opengameart.org/content/space-shooter-redux
license: CC0
author: Kenney
author_link: https://www.kenney.nl/
required_vars: []
platforms: [common]
category: assets
icon: space-shooter-redux.svg
image: space-shooter-redux.png
---

Space-related backgrounds, spaceships, fonts and sounds.

Sample code (views decorators/builders prefixed with `spaceShooterRedux`):

```kotlin
import com.soywiz.korge.*
import com.soywiz.korim.color.*
import spaceredux.*

suspend fun main() = Korge(width = 512, height = 512, bgcolor = Colors["#2b2b2b"]) {
    //spaceShooterRedux.putBackground(SpaceShooterReduxBackground.Type.BLUE, speedX = 2.0, speedY = 1.0)
    spaceShooterRedux.putDemoCode()
}
```
