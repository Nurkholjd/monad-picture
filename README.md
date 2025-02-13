# monad-picture
picture
**Monad-Frog Metaphor**:
``` python
class FrogMonad:
    def __init__(self, value):
        self. purple = value
        
    def jump(self, function):
        return FrogMonad(function(self.purple))
        
result = FrogMonad("🐛").jump(process_food).jump(change_energy)
```
