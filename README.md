# Kitronik blocks for micro:bit

Blocks that support [Kitronik Servo:Lite board for the micro:bit](https://www.kitronik.co.uk/5623-servolite-board-for-move-mini.html)

## ServoLite

* turn around

```blocks
input.onButtonPressed(Button.A, () => {
    Kitronik.turnRight(90);
})
```

* go forward

```blocks
input.onButtonPressed(Button.B, () => {
    kitronik.drive Forward(10);
})
```

* stop both motors when pressing ``A+B``

```blocks
input.onButtonPressed(Button.AB, () => {
    kitronik.stop();
})
```

## License

MIT

## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)


```package
pxt-kitronik-servo-lite=github:KitronikLtd/pxt-kitronik-servo-lite
```