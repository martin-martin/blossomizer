# 💥🌼🌸 - Blossomizer
This is a very simple [Crash Blossoms](http://www.crashblossoms.com/) Generator.

## Whazzitdo?

It creates ambiguous **pseudo-headlines** (in easy [Title Case](https://en.wikipedia.org/wiki/Letter_case#Headings_and_publication_titles))

## Howsitdodat?

I sat down this morning and drew some crazy papers with boxes and arrows to figure out what does a Crash Blossom consist of at an abstracted level.

Obviously there are more possibilities.

I found one that I felt I could implement at my current level of knowledge, which is:

### Ambiguity based on words that can be both *nouns* and *verbs*

English is a weakly inflected language, meaning that *generally* words don't change according to their grammatical position. A lot is simply done with word order. Other languages change their verbs and nouns in those cases, making this type of ambiguity much less likely to occur.

[This article](http://www.nytimes.com/2010/01/31/magazine/31FOB-onlanguage-t.html) and some thinking brought me to the conclusion that I'll try to do make Crash Blossoms that draw from the following:

- focusing on **noun-verb ambiguity**
- also using the fact that both **plural nouns** and **verbs in 3rd person singular** end with an **-s**
- two pairs of (potential) **composite nouns** next to each other
- the **middle ones** should be noun-verb **ambiguous**

That allows e.g. for sentences such as:

>Gator Attacks Puzzle Experts


So I thought up these rules:

1. Capitalize words to increase possible ambiguity
2. Use nouns that pluralize with -s
3. The inner two need to be noun-verb ambiguous
4. The noun-verb associated with the composite noun needs to end with -s

### Noun-Verbs

I used BeautifulSoup to 


