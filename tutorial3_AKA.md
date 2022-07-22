# Light Display Tutorial


## Section  1
First, begin by dragging the``||basic.show icon||`` into the ``||basic. start block||``
```blocks
basic.showIcon(IconNames.Angry)
basic.forever(function () {
	
})
```
## Section 2
Next, drag the``||basic.show number||`` block into the ``||basic. forever||`` loop
```blocks
basic.showIcon(IconNames.Angry)
basic.forever(function () {
    basic.showNumber(0)
})
```

## Section 3
Last, drag the``||input.light||`` bubble into the ``||basic. show number||`` block found in the ``||basic. forever||`` loop
```blocks

basic.showIcon(IconNames.Angry)
basic.forever(function () {
    basic.showNumber(input.lightLevel())
})
```
## Section 4

Great Job! upload to your micr0:bit!