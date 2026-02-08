# IS120 Reusable Cards Assignment

The intent of this assignment was to display my capability in creating custom CSS cards from scratch. A combination of W3Schools and lecture material helped me accomplish this, and I am now capable of re-using my card designs or optimizing them as I see fit.

## Use of Margin
Margin was used in selectors such as .card, .card-title, and .card-button etc. to establish the minimum "distance" in pixels that every card should take before duplicating. I also used margin in the titles and following descriptions in order to create a proper sense of hierarchy and distance from one another, so that it makes a pleasant aesthetic. Without margin, all of the cards would stick together and there would be no real sense of breathable space between every element.

## Use of Padding
Padding was used in several locations, such as card-title. Let us take card-title for a moment. Padding was used here to fill the space around the text, with border-radius rounding the corners. I used padding here to make the card seem more lively. Without padding, I would have had to use margin. However, I already used margin to establish the distance between it and the image, and the rest of the card. Padding is necessary here, otherwise the aesthetics would simply look horrendous. .card-button also uses padding in order to increase the clickable area.

## Use of Display
Display is used in nearly all selectors. I will point out the most notable ones:
#### .card's display: inline-block
This handles how each card class will behave when it is duplicated. Inline-block, in the most simplest terms, enables the cards to sit right next to each other (with a distance controlled by Margin in my CSS). If I did not have inline-block, then my cards wouldn't be able to sit right next to each other, and my card padding would be a bit useless.

#### .card-button's display: block
Stylistically, this display allows my button to take up and entire block-level element's worth of size inside of my card. I used it in this way because I do not find a reason to have text in the same place that I would have my button. However, this can easily be changed to an inline element if necessary. I also made sure to use margin: 16px auto 0; here in order to reduce the size that it takes up, so that it looks aesthetically better. Without the margin, the button spans the entire width of the card.


