# Light the way Activity 1

```blocks
sensors.color3.onLightChanged(LightIntensityMode.Ambient, LightCondition.Dark, function () {
    brick.showImage(images.objectsLightOn)
    loops.pause(5000)
    brick.clearScreen()
})
```