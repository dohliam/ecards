# Open Ecard Generator - Serverless, non-expiring electronic greeting cards

This is a working prototype for a purely client-side javascript ecard generator. You can try it online [here](https://dohliam.github.io/ecards/) or download the repo and host it anywhere, including a local network (requires no internet or server access).

## Features

* Mobile-friendly
* No ads, spam, or other junk
* Customized cards never expire
* No need to send or store data on a server
* Can be run locally or offline
* Use your own images, colours, and text
* Unicode-friendly
* Import card links from other instances
* No need for email -- send link by instant message, text or however you want

## Demo

[Open Ecard Generator Online Demo](https://dohliam.github.io/ecards/)

## Usage

The default ("create") page provides a simple interface to design your electronic greeting card. The message text, card image, background colour and pattern, and sender and receiver names can all be customized. Your card will appear in an automatically-updating preview at the bottom of the screen as you begin to edit it. Press the "Toggle preview" button to turn off the preview feature.

While you are designing your card, a link will appear to the final card. You can share this link (which goes to the "receive" page) with anyone you would like to send the card to.

All of your customizations are encoded in the url, so the card contents will not expire or change as long as the site is up (and even if the site goes down, you can still retrieve your card by downloading the generator and importing the link.)

The card generation and retrieval process is done entirely locally on your device, so none of the card contents is ever stored anywhere on any server.

## To do

* Change font and font colour
* Add optional banner and banner text
* Auto adjust text size for long messages
* Show preview in modal window
* Share button with preformatted link
* ~~Import/export card templates~~
* Config file to store default icon/pattern locations, sender name etc
* Interface translation
* Audio?

## Credits

* Default card background patterns from [transparent-textures](https://github.com/mike-hearn/transparent-textures) by @mike-hearn
* Default card images from the [elegant-circles](https://github.com/dohliam/elegant-circles) repo, original artwork by [Elegant Themes](http://www.elegantthemes.com/)
* Logo based on [Wedding Invitation](https://thenounproject.com/term/wedding-invitation/3327167/) by [The Icon Z](https://thenounproject.com/theiconz) from the Noun Project


## License

MIT.
