# Start

##  section 1
First begin by dragging the ``||basic.show icon||`` into the ``||basic.start block||``


```blocks
basic.showIcon(IconNames.Heart)
basic.forever(function () {
	
})
```

##  section 2
Next, drag the ``||basic.show number block||`` into ``||basic.forever loop block||``
```blocks

basic.showIcon(IconNames.Heart)
basic.forever(function () {
    basic.showNumber(0)
})
```


##  section 3
Last, drag the ``||input.temperature bubble||`` into the ``||basic.show number ||`` block found in the ``||basic.forever||`` loop

```blocks
basic.showIcon(IconNames.Heart)
basic.forever(function () {
    basic.showNumber(input.temperature())
})

##  section 3
Congratulations, now  you can upload this progrm to your micro:bit
