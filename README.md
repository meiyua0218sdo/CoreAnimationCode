# Core Animation Code

These are code examples for the book _iOS Core Animation Advanced Techniques_ written by [Nick Lockwood](https://github.com/nicklockwood), include code examples from Chapter 1 to Chapter 9. 

Recently, I'm reading the book. I think I should write some code. So I copy and paste the easy part from the book to Xcode, and write the hard part bodily after I understand well. Gradually, I accumulate these code examples.

## Directory Tree 

```
.
├── 1 The Layer Tree
│   └── BlueLayer
├── 2 The Backing Image
│   ├── CALayerDelegate
│   ├── LayerContent
│   └── Sprite
├── 3 Layer Geometry
│   ├── AnchorPoint
│   ├── Clock
│   ├── ContainsPoint
│   ├── ContentsCenter
│   └── ZPosition
├── 4 Visual Effects
│   ├── DropShadows
│   ├── GroupOpacity
│   ├── LCDClock
│   ├── LayerMask
│   ├── RoundedCorners
│   ├── ShadowClipping
│   └── ShadowPath
├── 5 Transforms
│   ├── CompoundTransform
│   ├── Cube
│   ├── OppositeRoationAroundY
│   ├── OppositeRotationAroundZ
│   └── SublayerTransform
├── 6 Specialized Layers
│   ├── AVPlayerLayer
│   ├── CAEAGLLayer
│   ├── CAEmitterLayer
│   ├── CAGradientLayer
│   ├── CAReplicatorLayer
│   ├── CAScrollLayer
│   ├── CAShapeLayer
│   ├── CATextLayer
│   ├── CATiledLayer
│   ├── CATransformLayer
│   ├── LayerLabel
│   ├── Reflection
│   ├── RichText
│   └── TileCutter
├── 7 Implicit Animations
│   ├── ActionForLayer
│   ├── CustomAction
│   ├── LayerActions
│   ├── PresentationLayer
│   └── Transactions
├── 8 Explicit Animations
│   ├── AnimateTransform
│   ├── AnimateUITabBarController
│   ├── AnimationDidStop
│   ├── AnimationGroup
│   ├── CABasicAnimation
│   ├── CAKeyframeAnimation
│   ├── CATransition
│   ├── CancelAnimation
│   ├── Clock
│   ├── CustomTransition
│   ├── TransformRotation
│   └── UIBezierPath
├── 9 Layer Time
│   ├── DurationAndRepeatCount
│   ├── ManualAnimation
│   ├── SwingingDoor
│   └── TimeOffsetAndSpeed
└── README.md

65 directories
```

You can open `CoreAnimationCode.xcworkspace` to see all projects in one workspace.

## Some instereting examples

CAEmitterCell:

![code1](https://cloud.githubusercontent.com/assets/5022872/10262415/9b2bebea-69f8-11e5-9708-28e0602f66d4.gif)


timeOffset & speed test:

![code2](https://cloud.githubusercontent.com/assets/5022872/10262407/5d5a9fdc-69f8-11e5-8161-0d4b8b9ec4eb.gif)


Manual Animation:

![code3](https://cloud.githubusercontent.com/assets/5022872/10262408/68b2759e-69f8-11e5-8760-1f9f4ce1482f.gif)


Custome Transition:

![code4](https://cloud.githubusercontent.com/assets/5022872/10262410/7ab6030a-69f8-11e5-8395-0dadc09c46dd.gif)

