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
* No need for email -- send link by instant message, text or however you want

## Demo

[Open Ecard Generator Online Demo](https://dohliam.github.io/ecards/)

## Usage

The default ("create") page provides a simple interface to design your electronic greeting card. The message text, card image, background colour and pattern, and sender and receiver names can all be customized. Press the "Preview" button to see what your ecard will look like.

While you are designing your card, a link will appear to the final card. You can share this link (which goes to the "receive" page) with anyone you would like to share the card with.

All of your customizations are encoded in the url, so the card contents will not expire or change as long as the site is up (and even if the site goes down, you can still retrieve your card by downloading the generator and opening the link locally with the same parameters.)

The card generation and retrieval process is done entirely locally, so none of the card contents is ever stored anywhere on any server.

## To do

* Change font and font colour
* Add optional banner and banner text
* Auto adjust text size for long messages
* Show preview in modal window
* Share button with preformatted link
* Import/export card templates
* Config file to store default icon/pattern locations, sender name etc
* Interface translation
* Audio?

## Credits

* Default card background patterns from [transparent-textures](https://github.com/mike-hearn/transparent-textures) by @mike-hearn
* Default card images from the [elegant-circles](https://github.com/dohliam/elegant-circles) repo, original artwork by [Elegant Themes](http://www.elegantthemes.com/)

## License

MIT.
