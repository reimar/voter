# Voter

Voter creates dead-simple digital voting cards. Just open Voter in your mobile browser. By default, your phone will display two _swipeable_ cards, one red, one green. Just check it out yourself:

![QR code](https://reimar.github.io/voter/assets/qr-code.svg)<br />
https://reimar.github.io/voter/

To change the colors or number of cards, you need to change a part of the url (you might also call it the website’s _address_). Add a comma-separated list of hexadecimal color values (eg. `000000` for _black_) and Voter will create a card for each color. Here are some examples:

1. https://reimar.github.io/voter/?colors=FFFFFF,000000 — a black and a white card
2. https://reimar.github.io/voter/?colors=2541F7,F75765,F7C625 — a blue, a red and a yellow card
3. https://reimar.github.io/voter/?colors=E37CF7,B160C1,6E3C78,331C38 — four purple cards of different shades

## Tips

- Use https://color.adobe.com/create/color-wheel to create colors for your set of cards. The mumbers after the hash signs (_#_) are what you need.
- Use https://express.adobe.com/tools/qr-code-generator to create a QR code for your url to easily share it.

## Planned Features

- Proper branding (logo, icon, etc.)
- Add customizable text labels or emojis
- Add instructions and templates
- Synchronize votes/cards with a statistics page
