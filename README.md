# 💥🌼🌸 - Blossomizer
This is a very simple [Crash Blossoms](http://www.crashblossoms.com/) Generator.

## Whazzitdo?

It creates ambiguous **pseudo-headlines** (in [Title Case](https://en.wikipedia.org/wiki/Letter_case#Headings_and_publication_titles)).

## Howsitdodat?

It uses some **fun ambiguities** that exist in natural languages - specifically one that is pervasive in English:

### Ambiguity based on words that can be both *nouns* and *verbs*

English is a weakly inflected language, meaning that *generally* words don't change according to their grammatical position. A lot of meaning is done with word order instead. Other languages change their verbs and nouns to expressing grammatical concepts, making such type of ambiguity less likely to occur.

Reading [this article](http://www.nytimes.com/2010/01/31/magazine/31FOB-onlanguage-t.html) and doing some crazy drawings brought me to the conclusion that I'll try to make Crash Blossoms based on the following:

- focusing on **noun-verb ambiguity**
- additionally utilizing that both **plural nouns** and **verbs in 3rd person singular** end with an **-s**
- putting two pairs of (potential) **composite nouns** next to each other
- where the two **middle ones** should be noun-verb-**ambiguous**

That allows the reader to flip-flop between two possible interpretations, which is essentially the basic fun of all that.

Of course there's much more to the humor of Crash Blossoms, and this one-day-hack for learning purposes doesn't catch a lot of it.

But, if you're lucky and enter the right words, you can get sentences such as:

>Gator Attacks Puzzle Experts

Which sseems to actually be a real headline and I think it's super fun! (at least if you're not a puzzle expert) 😱🐊

## Showyasteps!

1. I checked out a few Crash Blossoms to look for some generalized pattern I'd be able to re-create.

2. I read a bit and drew a bit.

3. Then I distilled these half-actionable rules:
	- Capitalize words to increase possible ambiguity
	- Use nouns that pluralize with -s
	- The inner two need to be noun-verb ambiguous
	- The noun-verb associated with the composite noun needs to end with -s

4. I wrote some HTML and JS that takes word input and sticks it onto the page
5. Only when I saw that all this could work, I went to scrape for Noun-Verbs
	- 	and used [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) to get a list of Noun-Verbs [from the net](http://www.enchantedlearning.com/wordlist/nounandverb.shtml)
6. Then I puzzled it together _(Constantly looking over my shoulder for that_ 🐊!)_
7. And finally did some mini prettification and put it up on github

## Ideas

- Use **Collocation** info to make the results actually fun
- Use **Sentiment Analysis** to filter the happy words from that small list of words I'm using (okay... to practice Sentiment Analysis)
- Add **more possibilities** for creating **different types** of Crash Blossoms
