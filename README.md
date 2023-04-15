# Voter

Voter creates dead-simple digital voting cards. Just open Voter in your mobile browser. By default, your phone will display two _swipeable_ cards, one red, one green. Just check it out yourself:

![QR code](https://reimar.github.io/voter/assets/qr-code.svg)<br />
https://reimar.github.io/voter/

## Why?

I needed a simple solution for an upcoming workshop to let the participants answer voting questions. You could do thumbs up or down but that's a bit more difficult to see and count (especially in darker venues).

## Customization

### Colors & Number of Cards

To change the colors (and number of cards), you need to change a part of the url (aka the website’s _address_). Add a comma-separated list of hexadecimal color values (eg. `000000` for _black_) or [css color keywarods](https://www.w3.org/wiki/CSS/Properties/color/keywords) and Voter will create a card for each color. Here are some examples:

1. https://reimar.github.io/voter/?colors=black,white — a black and a white card
2. https://reimar.github.io/voter/?colors=2541F7,F75765,F7C625 — a blue, a red and a yellow card
3. https://reimar.github.io/voter/?colors=E37CF7,B160C1,6E3C78,331C38 — four purple cards of different shades

### Labels

You can add labels to your cards. Keep them short or they will get cut off. Some examples:

1. https://reimar.github.io/voter/?colors=E37CF7,B160C1,6E3C78,331C38&labels=1,2,3,4 — four purple cards of different shades, each with a number
2. https://reimar.github.io/voter/?colors=black,grey,white&labels=nope,,yay — three cards (black, grey and white), first card labeled _nope_, second card unlabeled, third card labeled _yay_

### Emojis

Yes. You can also add emojis. Add a list of emojis which will map to your list of colors. It’s best to explain via examples:

1. https://reimar.github.io/voter/?colors=FF6332,36A800&labels=👎,👍 — a red card with thumbs-down emoji and a green card with a thumbs-up emoji
2. https://reimar.github.io/voter/?colors=black,white&labels=💀,👻 — a black card with a skull emoji and a white card with a ghost emoji
3. https://reimar.github.io/voter/?colors=2541F7,F75765,F7C625&labels=🏄,,🍔 — a blue card with a surfer emoji, a red card with no emoji and a yellow card with a hamburger emoji

### Enable Counter Display

If you need to count the voting cards, you can _note_ your counts per card by enabling the counter:

1. https://reimar.github.io/voter/?counter — enables the counter with the default cards
2. https://reimar.github.io/voter/?colors=lightcyan,dodgerblue&counter — or add `&counter` (prefereably) to the end of your custom url

Wipe up or down on the counter to set a count. Once you refresh the page, your count will reset.

## Tips

- Create color palettes with https://color.adobe.com/create/color-wheel for your set of cards. The mumbers after the hash signs (_#_) are what you need.
- Create a QR code for your url with https://express.adobe.com/tools/qr-code-generator to easily share it.
- Copy & paste emojis from https://unicode.org/emoji/charts/full-emoji-list.html.
