# GodotFloatBarrier
Provides a visual barrier at a constant 4km from the world origin in the Godot engine.

* FloatBarrier.tscn provides an outward-facing barrier. In a nutshell, if you designed your game correctly, keeping things within 32-bit floating precision limitations, then you should never see this. You can ship this in your game and ideally nobody would ever notice.

* FloatBarrierInv.tscn provides an inward-facing barrier. This one is more meant as a visual aid, to help level designers avoid going out too far.

Because the root node is a Node and not a Spatial, you don't have to worry about parenting. The barrier will always be 4km from the global world origin.
