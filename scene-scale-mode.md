# SKScene.scaleMode

The four possible `SKScaleMode` settings.

![Original image](rectangle.png)

## Default setting

```Swift
let scene = SKScene(size: CGSize(x: 736, y: 414))
scene.scaleMode = .Fill
```

![Original image](scene-scale-mode-fill.png)

### Other settings

```Swift
let scene = SKScene(size: CGSize(x: 736, y: 414))
scene.scaleMode = .AspectFill
```

![Original image](scene-scale-mode-aspect-fill.png)

```Swift
let scene = SKScene(size: CGSize(x: 736, y: 414))
scene.scaleMode = .AspectFit
```

![Original image](scene-scale-mode-aspect-fit.png)


```Swift
let scene = SKScene(size: CGSize(x: 736, y: 414))
scene.scaleMode = .ResizeFill
```

![Original image](scene-scale-mode-resize-fill.png)