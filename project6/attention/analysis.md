# Analysis

## Layer 4, Head 6

Head 6 in the layer 4 seems to make each token attend to the previous token. For example in the sentence "Then I picked up a [MASK] from the table." the word "up" pays most attention to "picked", and in the sentence "This is a [MASK]." the word "a" pays most attention to "is".

Example Sentences:
- This is a [MASK].
- Then I picked up a [MASK] from the table.

## Layer 7, Head 3

For layer 7, head 3 it seems that pronouns attend to the noun they refer to. For example "she" pays attention to "woman" in the sentence "The woman rode her bike because she needed to go to the [MASK]." You can also see that "her" pays attention to "the woman", but slightly less. The same attention pattern is visible for the sentence "The farmer sold his cows because he needed [MASK]." where "he" pays attention to "farmer" and "his" as well.

Example Sentences:
- The woman rode her bike because she needed to go to the [MASK].
- The farmer sold his cows because he needed [MASK].