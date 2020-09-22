
# How to import

Download this repository (Export it if you download as zip), open anki and click on "File" -> "CrowdAnki: Import from disk".
Select the correct directory (🧪_Test_Deck) and click import.

# Note Types

I've made some major changes to the available note types in this deck. (I removed most of the old ones, since I found I never actually used them)

* pretttyBasic - A pretty basic card with front and back
* prettyCloze - Pretty cloze card, also has a title and an extra field
* prettyPoem - A card for memorizing poems or quotes
* prettyWord - A card for memorizing vocabulary
* prettyPerson - A card for memorizing people
* prettyList - A card for memorizing lists
* prettyEvent - A card for memorizing an event
* prettyConjugation - A card for memorizing the conjugated forms of a word

# General Notes

* You should turn of autoplaying audio.

* Some cards require you to turn off some gestures on AnkiDroid. Mainly, you need some space to click on the screen without revealing the answer. You can do this by unassigning touch-bottom for example in the gesture settings.

# prettyWord

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

By default, upon seeing the front of the card, the audio of the word you're trying to memorize is played in the language the word is in, upon seeing the back of the card you'll hear the audio of the word in your native language.
Click on any of the elements that have audio (Word, WordTranslation, Sentence, SentenceTranslation) to play the audio for that.

# prettyPoem

You can use this note type to memorize poems, quotes or lyrics. When you see the front of the card, tap on it to reveal the first word of the text. (Try to remember what it was beforehand) Continue to work you're way through the text like this. At the end, judge how well you were able to remember it.

# prettyList

You can use this note type to memorize lists. When you see the front of the card, tap on it to reveal the first element of the text. (Try to remember what it was beforehand) Continue to work you're way through the text like this. At the end, judge how well you were able to remember it.
You need to put one (only one) <ul> or <ol> in the list field for the javascript to function correctly.
![](media/basicPrettyBack.jpg)
![](media/basicPrettyFront.jpg)
![](media/clozePrettyBack.jpg)
![](media/clozePrettyExtra.jpg)
![](media/clozePrettyFront.jpg)
