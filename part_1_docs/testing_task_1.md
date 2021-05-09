### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    # ERROR: = assignment used instead of == equality operator
    if card.value = 1: 
      return True
    # ERROR: no colon after else keyword
    else 
      return False
   
  # ERROR: 'dif' typo instead of def keyword
  # ERROR: no comma after card1 parameter
  dif highest_card(self, card1 card2):
  # ERROR: no indentation for code block
  if card1.value > card2.value:
    # ERROR: card is not defined, should be card1
    return card
  else:
    return card2
  

# ERROR: this method is not indented into the card game class
def cards_total(self, cards):
  # ERROR: total is not assigned anything
  total
  for card in cards:
    total += card.value
    # ERROR: total is supposed to be an int (presumably) and cannot be concatenated to a string
    # ERROR: return should not be indented in the for loop
    # ERROR: missing space at end of string
    return "You have a total of" + total
  
```
