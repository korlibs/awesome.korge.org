---
title: Box2d support
bundle_url: "https://github.com/korlibs/korge-bundles.git::korge-box2d::4ac7fcee689e1b541849cedd1e017016128624b9##d15f5b28abbc2f58ba375d7204a6db2e90342978d02e675cd29249d0cade8f9f"
bundle_link: https://github.com/korlibs/korge-bundles/tree/master/korge-box2d
license: MIT
author: Korge
author_link: https://github.com/korlibs/
required_vars: []
platforms: [common]
category: services
icon: box2d.svg
---

Adds support for Box2D.

main:

```
registerBox2dSupportOnce()
addChild(resourcesVfs["restitution.ktree"].readKTree(views))
```

restitution.ktree:

```xml
<ktree width="921.3163135700865" height="720.0" gridWidth="20" gridHeight="20">
	<solidrect y="620.0" width="920.0" height="100.0">
		<__ex_physics friction="0.2" restitution="0.2"/>
	</solidrect>
	<ellipse x="120.0" y="246.0" anchorX="0.5" anchorY="0.5" width="100.0" height="100.0">
		<__ex_physics type="DYNAMIC" linearVelocityY="6.0" friction="0.2" restitution="0.3"/>
	</ellipse>
	<ellipse x="260.0" y="246.0" anchorX="0.5" anchorY="0.5" width="100.0" height="100.0">
		<__ex_physics type="DYNAMIC" linearVelocityY="6.0" friction="0.2" restitution="0.4"/>
	</ellipse>
	<ellipse x="400.0" y="246.0" anchorX="0.5" anchorY="0.5" width="100.0" height="100.0">
		<__ex_physics type="DYNAMIC" linearVelocityY="6.0" friction="0.2" restitution="0.5"/>
	</ellipse>
	<ellipse x="540.0" y="245.0" anchorX="0.5" anchorY="0.5" width="100.0" height="100.0">
		<__ex_physics type="DYNAMIC" linearVelocityY="6.0" friction="0.2" restitution="0.6"/>
	</ellipse>
	<ellipse x="680.0" y="246.0" anchorX="0.5" anchorY="0.5" width="100.0" height="100.0">
		<__ex_physics type="DYNAMIC" linearVelocityY="6.0" friction="0.2" restitution="0.7"/>
	</ellipse>
</ktree>
```