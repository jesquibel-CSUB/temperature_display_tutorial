# How to Create a Temperature Display
## Step 1
Begin by dragging the ``||basic.clearScreen||`` command in the ``||basic.onStart||`` block
```blocks
basic.clearScreen()

```

## Step 2
Next drag the ``||basic.show Number||`` icon into the ``||basic.forever||`` loop

```blocks
basic.forever(function () {
    basic.showNumber()
})
```

## Step 3
Last, drag the ``||input.temperature||`` block into the ``||basic.showLeds||`` blocks
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```
