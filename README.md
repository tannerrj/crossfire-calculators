# Crossfire Calculators

This project includes various calculators for the MRPG game of Crossfire.

The calculators are HTML and javascript based pages to perform functions such as:

 * Money or currency conversions (i.e., gold to silver coins)
 * Party Experience - how much experience does a monster need to have for all members in a party to gain experience for vanquishing that foe(s)

Why a calculator for Party Experience?

The calculation is not straight addition. From the Crossfire FAQ:

> The party or shared experience system operates as follows: The server initiates a certain number of "shares," which equals the sum of the individual levels of all players in the party, plus an additional 4 shares for each player. Subsequently, the total experience is distributed based on the number of "shares" contributed by each member of the group. To calculate the required experience from monsters, the experience value of the monsters must be at least the total sum of the party member levels, plus 4 multiplied by the number of members in the party (denoted as N).

> For instance, using the formula (Level 109 + Level 11 = 120) + (4 (for the level 109 character) + 4 (for the level 11 character)) = 128, it is determined that the party needs to defeat monsters with a combined experience of at least 128 XP to gain any experience.

> It is crucial to be aware that if the monsters being defeated yield insufficient experience initially, rounding calculations may result in the party receiving no experience at all.

> Additionally, it is important to note that all party members must be present on the same map to effectively "share" experience.

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