# Oh Heck
Score keeper for the card game "Oh Heck"


###Known Bugs
- Cut-throat rule check does not update when an entered bid is edited before end of bidding
  
  (Ex: Adam and Bill bid 0 and 3 respectively on a round with 5 cards.  Bill accidentally typed '4' on his bid, and edits the box to '3' instead.  The app will not allow Clara to bid '1' at this point, even though the updated bids should only disallow '2')
  
  [Current workaround: uncheck the 'cut-throat' box in settings while entering the last bid]
