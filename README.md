# Voter

Voter creates dead-simple digital voting cards. Just open Voter in your mobile browser. By default, your phone will display two _swipeable_ cards, one red, one green. Just check it out yourself:

![QR code](https://reimar.github.io/voter/assets/qr-code.svg)<br />
https://reimar.github.io/voter/

## Customize Your Cards

### Colors & Number of Cards

To change the colors (and number of cards), you need to change a part of the url (aka the website’s _address_). Add a comma-separated list of hexadecimal color values (eg. `000000` for _black_) and Voter will create a card for each color. Here are some examples:

1. https://reimar.github.io/voter/?colors=000000,FFFFFF — a black and a white card
2. https://reimar.github.io/voter/?colors=2541F7,F75765,F7C625 — a blue, a red and a yellow card
3. https://reimar.github.io/voter/?colors=E37CF7,B160C1,6E3C78,331C38 — four purple cards of different shades

### Emojis

Yes. You can also add emojis. Add a list of emojis which will map to your list of colors. It’s best to explain via examples:

1. https://reimar.github.io/voter/?colors=FF6332,36A800&symbols=👎,👍 — a green card with thumbs-up emoji and a red card with a thumbs-down emoji
2. https://reimar.github.io/voter/?colors=000000,FFFFFF&symbols=💀,👼 — a black card with a skull emoji and a white card with a baby angel emoji
3. https://reimar.github.io/voter/?colors=2541F7,F75765,F7C625&symbols=🏄,,🍔 — a blue card with a surfer emoji, a red card with no emoji and a yellow card with a hamburger emoji
4. https://reimar.github.io/voter/?colors=E37CF7,B160C1,6E3C78,331C38&symbols=1️⃣,2️⃣,3️⃣,4️⃣ — four purple cards of different shades, each with a keycap digit emoji

## Tips

- Use https://color.adobe.com/create/color-wheel to create colors for your set of cards. The mumbers after the hash signs (_#_) are what you need.
- Use https://express.adobe.com/tools/qr-code-generator to create a QR code for your url to easily share it.
- Head over to https://unicode.org/emoji/charts/full-emoji-list.html to copy & paste emojis.

## Planned Features

- Proper branding (logo, icon, etc.)
- Add instructions and templates
- Synchronize votes/cards with a statistics page
