# How to Create a Temperature Display

## begin by dragging the ``||basic.show Number||`` icon into the ``||basic.forever||`` loop

```blocks
basic.forever(function () {
    basic.showNumber()
})
```

## Next drag the ``||input.temperature||`` block into the ``||basic.showLeds||`` blocks
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```
