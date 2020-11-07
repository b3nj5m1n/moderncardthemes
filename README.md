<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">moderncardthemes</h3>

  <p align="center">
    Modern card themes for anki.
    <br />
    <br />
    <a href="https://github.com/b3nj5m1n/moderncardthemes/issues">Report Bug</a>
    ·
    <a href="https://github.com/b3nj5m1n/moderncardthemes/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]()

A collection of anki note-types, with a matching modern design.


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* The crowd-anki addon

### Installation

1. Clone the repo
```sh
git clone https://github.com/b3nj5m1n/moderncardthemes.git
```
2. Open anki and click on "File" -> "CrowdAnki: Import from disk"
3. Select the correct directory (test_tube_Test_Deck)
4. Click import

### Configuration

* You should turn of autoplaying audio.

* Some cards require you to turn off some gestures on AnkiDroid. Mainly, you need some space to click on the screen without revealing the answer. You can do this by unassigning touch-bottom for example in the gesture settings.


<!-- USAGE EXAMPLES -->
## Usage

### Note Types

I've made some major changes to the available note types in this deck. (I removed most of the old ones, since I found I never actually used them)

* pretttyBasic - A pretty basic card with front and back
* prettyCloze - Pretty cloze card, also has a title and an extra field
* prettyPoem - A card for memorizing poems or quotes
* prettyWord - A card for memorizing vocabulary
* prettySentence - A card for memorizing sentences in a foreign language
* prettyPerson - A card for memorizing people
* prettyList - A card for memorizing lists
* prettyEvent - A card for memorizing an event
* prettyConjugation - A card for memorizing the conjugated forms of a word

### prettyWord

This card has a lot of fields, so here is a brief explanation of which ones you need to worry about:
* ID - Use this to give each card a unique identity, this is mainly for the purpose of automating the addition of new cards to the deck and the updating of existing ones via external scripts.
* Word - The word you want to memorize.
* AudioWord - Audio of the pronounciation of the word you're trying to learn.
* WordTranslation - Translation of the word you're trying to learn in your native language.
* AudioWordTranslation - Audio of the word in you're native language.
* Sentence - The word you're trying to learn used in an example sentence.
* AudioSentence - An audio of the example sentence.
* SentenceTranslation - A translation of the example sentence in your native language.
* AudioSentenceTranslation - An audio of the translation of the example sentence in your native language.
* Note/Mnemonic - A note about the word, or a mnemonic to make remembering the word easier.
* Picture - A picture representative of the word.
* CountryISO - ISO 3166-1 alpha-2 code of the country the language of the word you want to learn is used in; For example: de (Germany), es (Spain); (This will be used to show the flag of that card on the card)
* Level - For example HSK1
* Word-Symbol - For example the simplified chinese character
* Word-Symbol-2 - For example the traditional chinese character
* Language - An extra field in case you want to specify the language seperately from the country
* CreateReverse - Put something in this field if you want to have a reverse card created (Your target language -> your native language)

By default, upon seeing the front of the card, the audio of the word you're trying to memorize is played in the language the word is in, upon seeing the back of the card you'll hear the audio of the word in your native language.
Click on any of the elements that have audio (Word, WordTranslation, Sentence, SentenceTranslation) to play the audio for that.

### prettyPoem

You can use this note type to memorize poems, quotes or lyrics. When you see the front of the card, tap on it to reveal the first word of the text. (Try to remember what it was beforehand) Continue to work you're way through the text like this. At the end, judge how well you were able to remember it.

### prettyList

You can use this note type to memorize lists. When you see the front of the card, tap on it to reveal the first element of the text. (Try to remember what it was beforehand) Continue to work you're way through the text like this. At the end, judge how well you were able to remember it.
You need to put one (only one) ul or ol tag in the list field for the javascript to function correctly.

### prettyConjugation

For conjugations, you can specify the pronouns in a ; separated list, here are some examples:

* Spanish: `yo; tú; él/ella/ello, usted; nosotros/nosotras; vosotros/vosotras; ellos/ellas, ustedes;`
* French: `je; tu; il, elle, on; nous; vous; ils, elles;`
* Italian: `io; tu; lui, lei; noi; voi; loro;`
* Portuguese: `eu; tu; ele, ela, você; nós; vós; eles, elas, vocês;`
* Catalan: `jo; tu; ell, ella, vostè; nosaltres; vosaltres; ells, elles, vostès;`


![](media/basicPrettyBack.jpg)
![](media/basicPrettyFront.jpg)
![](media/clozePrettyBack.jpg)
![](media/clozePrettyExtra.jpg)
![](media/clozePrettyFront.jpg)


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/b3nj5m1n/moderncardthemes?style=flat-square
[contributors-url]: https://github.com/b3nj5m1n/b3nj5m1n/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/b3nj5m1n/moderncardthemes.svg?style=flat-square
[forks-url]: https://github.com/b3nj5m1n/moderncardthemes/network/members
[stars-shield]: https://img.shields.io/github/stars/b3nj5m1n/moderncardthemes.svg?style=flat-square
[stars-url]: https://github.com/b3nj5m1n/moderncardthemes/stargazers
[issues-shield]: https://img.shields.io/github/issues/b3nj5m1n/moderncardthemes.svg?style=flat-square
[issues-url]: https://github.com/b3nj5m1n/moderncardthemes/issues
[license-shield]: https://img.shields.io/github/license/b3nj5m1n/moderncardthemes.svg?style=flat-square
[license-url]: https://github.com/b3nj5m1n/moderncardthemes/blob/master/LICENSE.txt
[product-screenshot]: https://socialify.git.ci/b3nj5m1n/moderncardthemes/image?font=Inter&language=1&owner=1&pattern=Circuit%20Board&theme=Light
