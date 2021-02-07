---
title: TextTerminal
bundle_url: "https://github.com/korlibs/korlibs-bundle-source-extensions.git::text-terminal::8a6d8af9c5cbd7be3acccfac145d0671f4477588"
bundle_link: https://github.com/korlibs/korlibs-bundle-source-extensions/tree/master/text-terminal
license: MIT
author: soywiz
author_link: https://github.com/soywiz/
required_vars: []
platforms: [common]
category: extensions
---

Creates a KorGE view displaying text, and supports klogger integration:

```
val logger = textTerminal().logger("events")
logger.info { "READY!" }
```
