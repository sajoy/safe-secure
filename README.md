# working title: safe-secure

## step 1:
write a randomizer program that
- returns a random shape
- returns a random size
- returns a random number
- returns a random color


## step 2:
use program to determine
- special attributes (maybe)
- how many different shapes to use (random number)
- for each shape
    - color
    - size
    - position
    - number


## step 3:
collage according to randomly selected attributes



---------
## psuedo code
```js
let piece1 = createPiece(options); // returns array below
piece1 = [
    {
        shape: ‘square’,
        color: ‘black’,
        size: ‘small’
        number: ‘5’,
        position: ‘center center’
    }, 
        {
            shape: teardrop’,
            color: ‘blue’,
            size: ‘large’
            number: ‘2’,
            position: ‘center center’
    },
    {
            shape: ‘square’,
            color: ‘blue’,
            size: ‘large’
            number: ‘4’,
            position: ‘center right’
    },
]

drawPiece(piece1); 
// would draw the shapes in a canvas, or layout the images on a webpage
// drawing rules: items cannot overlap more than 60%, items can rotate, are randomly sized within range
```
config as json

- shapes
    - square
    - rectangle
    - triangle
    - circle
    - ellipse
    - teardrop
    - arch
    - parallelogram
    - blob
    - squiggle
    - letters in “safe”
    - letters in “secure”

- size
    - small (≤ 1 inch)
    - medium (1-3 inches)
    - large (> 3 inches)

- color
    - black
    - blue
    - purple
    - other?

- number
    - 1
    - 2
    - 3
    - 4
    - 5
    - 6
    - 7

- position
    - upper left
    - upper center
    - upper right
    - center left
    - center center
    - center right
    - bottom left
    - bottom center
    - bottom right



---

## presentation

- the code
- the returned arrays
- the computer’s interpretation
- my interpretation
