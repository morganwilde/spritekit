# SKSpriteNode

This descendant of `SKNode` draws an image.

## Initialisers

```Swift
convenience init(imageNamed name: String)
```

This initialiser takes an image by name from the `Images.xcassets` collection and displays it. For example this image, called `square.png`.

![Original image](square.png)

### Default

Using the default parameters and nothing else, you get.

```Swift

let spriteNode = SKSpriteNode(imageNamed: "square.png")
```

![Default positions](sprite-node-image-named-default.png)

```Swift
(0.0,0.0)                   // spriteNode.position
(0.5,0.5)                   // spriteNode.anchorPoint
(-50.0,-50.0,100.0,100.0)   // spriteNode.frame
```

This positions the node to the bottom left - `(0.0, 0.0)`. Then shifts it so that the center of the node would be at the point `(0.0, 0.0)`.