# Tutorial 3

## Step 1

Here is a neopixel block

```blocks
let strip = neopixel.create(DigitalPin.P0, 24, NeoPixelMode.RGB)
let distance = sonar.ping(DigitalPin.P0,DigitalPin.P0,PingUnit.MicroSeconds)
```

```ghost
let strip = neopixel.create(DigitalPin.P0, 24, NeoPixelMode.RGB)
strip.setBrightness(255)
```

That's neopixel blocks

## Step 2

Congratulations, you did it!

```package
neopixel=github:microsoft/pxt-neopixel#v0.7.6
pxt-sonar=github:microsoft/pxt-sonar#v0.0.6
```
