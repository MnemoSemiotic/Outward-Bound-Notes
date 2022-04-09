# Outward-Bound-Notes
Just notes for the RPG Outward Bound, by Penflower Ink


#### Simple Python Dice Roller

```python
from random import choice
def roll_dice(n=1, sides=6): 
    return sum([choice(range(1,sides+1)) for _ in range(n)])
```


