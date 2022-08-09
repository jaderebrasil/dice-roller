# Documentation (Draft)
## Modes supported
- kh: Keep Higher.
- hl: Keep Lower.
- ka: Keep All.

If no mode is given, DiceExpr.roll will sum all dices together.

### Examples
`DiceExpr('3d6').roll()`
Run three d6 and return the sum.

`DiceExpr('2d10kh').roll()`
Run two d10 and return the value of the higher.
