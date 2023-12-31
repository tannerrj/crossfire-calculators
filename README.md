# Crossfire Calculators

This project includes various calculators for the MRPG game of Crossfire.

The calculators are HTML and javascript based pages to perform functions such as:

 * Money or currency conversions (i.e., gold to silver coins)
 * Party Experience - how much experience does a monster need to have for all members in a party to gain experience for vanquishing that foe(s)

Why is a calculator needed for Party Experience?

From the Crossfire FAQ:

> 3.2.9 How does shared or party experience work?

> Party or shared experience works like this; The server creates a number of “shares” which is the total overall levels of every player in the party, plus 4 for each player. Then the experience is divided up by how many “shares” each group member adds to the total number. That means the experience of the monster has to be at least the sum of the party member levels added together plus 4 * N, where N is the number of members in the party.

> Example: (Level 109 + Level 11 = 120) + (4 (for the level 109 character) + 4 (for the level 11 character)) = 128; the party needs to kill monsters worth at least 128 XP in order to gain experience

> If the monsters that the group is killing give too little (or low) experience to start with, rounding might cause you to be getting no experience.

> Also remember that all members of the party need to be on the same map in order to “share” experience.

### Requirements

A web browser with javascript enabled.

## Usage

The web pages are self contained in that the necessary html elements and javascript are all within the one web page file, so open the file in a browser and it should work.

## Screenshot

 * Sample screen shot using conversion on 8 Amberium coins
 ![Crossfire Currency Converter sample image](images/crossfire-currency-converter.png)
* Sample screen of the Party Experience Calculator with some random levels
 ![Crossfire Experience Calculator sample image](images/crossfire-party-xp-calculator.png)

## Live Web Page

 * [Currency Converter](https://crossfire.real-time.com/resources/calculators/currency-converter.html)
 * [Party XP Calculator](https://crossfire.real-time.com/resources/calculators/party-xp-calculator.html)

## Contributing

 * Contributions are welcome.
 * Pull requests are welcome.
 * Creating a fork on this code base is also welcome.

## Questions

I can be reached via [tannerrj GitHub Profile](https://github.com/tannerrj)

## License:

MIT License

## Crossfire Social Media Links

 * [Facebook](https://www.facebook.com/crossfireproject/)
 * [Mastodon](https://mastodon.social/@crossfiremrpg)
 * [X (Formerly Twitter)](https://twitter.com/crossfiremrpg/)