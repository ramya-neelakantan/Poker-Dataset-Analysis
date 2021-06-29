# Poker-Dataset-Analysis
Using Random Forest Classifier to predict hand in Poker

Each record in the dataset is an example of a hand consisting of 5 playing cards drawn from a standard playing deck of 52. Each card is described using 2 attributes (suit and rank), for a total of 10 predictive attributes. The target column describes the hand, with the possibilities being: 0. Nothing in hand; not a recognised poker hand

1. One pair; one pair of equal ranks within 5 cards
2. Two pairs; two pairs of equal ranks within 5 cards
3. Three of a kind; 3 equal ranks within 5 cards
4. Straight; 5 cards, sequentially ranked with no gaps
5. Flush; 5 cards with the same suit
6. Full House; pair + different rank three of a kind
7. Four of a kind; 4 equal ranks within 5 cards
8. Straight Flush; Straight + Flush
9. Royal Flush; {Ace, King, Queen, Jack, Ten} + Flush
The order of the cards is important, which is why there are 480 possible Royal Flush hands as compared to 4 (1 for each suit).
