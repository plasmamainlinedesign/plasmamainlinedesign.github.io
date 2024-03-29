---
title: Hidden pitch
author: PMD
date: 2024-03-29 17:59:00 +/-0000
image:
  path: /assets/img/posts/2024/cover-hiddenpitch.png
categories: [Card design]
tags: [pitch, hidden, card, cost, keyword]
carousels:
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/HVY212.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/OUT001.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR1.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-ARC217.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR159.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/HVY239_mIMmydw.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR115.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR113.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR132.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-CRU082.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/OUT026.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-ARC159.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/010-hiddenpitch.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD139.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD138.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD137.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/011-hiddenpitch.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-ARC159.width-450.format-webp.webp
---

Card games thrive on hidden information. Perhaps you could even consider it one of their defining features. When you sit down to play a game of Flesh and Blood, looking at the opposing hero will give you an idea of what the deck is capable of, assuming you are familiar with the card pool that hero has access to, but ultimately the exact configuration of their deck is unknown to you. As you start playing, they gradually reveal which cards they have in their deck, but you are still left guessing whether they play one, two, or three copies of any given card. And I am sure many long-time card gamers have been blown out at some point by a rogue card inclusion that they were not expecting. This is inherent in card game design and for some people the driving force to play card games is to win with these "gotcha" moments. 

Whilst the contents of your opponent's deck may be a mystery, the more immediate question you are usually trying to answer is "What cards does my opponent have in their hand?", as the answer to this question can significantly impact what we want to do on our turn. This may be the reason why we have seen cards like _Seduce Secrets_, whose only purpose is to gain information about your opponent's options. The general consensus in the Flesh and Blood community seems to be that these cards are not worth including in your deck, but surely they will prove to be useful at some point. In addition to the cards in your opponent's hand falling in the "hidden information" category, so do many other things, and in particular face down cards in various areas, like the cards banished by _Uzuri_'s or _Rhinar_'s ability. In this article, we take a look at face down cards in the pitch zone.

{% include carousel.html number="1" %}

## Hidden information
For the purposes of this article, we define "hidden information" as knowledge about the game state that one player has and can act upon, but their opponents do not. The most common example are the cards in a player's hand: each player knows what they have in their hand, but this information is hidden from their opponents. Another example of hidden information is e.g. when a player __opts__ or puts a card on the bottom of their deck to play _Enlightened Strike_. In both cases, the player performing these actions gains knowledge of the top or bottom card of their deck without revealing this information to their opponents. This is in contrast to when you pitch a card, of which both players are aware when it goes to the bottom of the deck. Note that with this definition mechanics like __clash__ are not considered to rely on hidden information because generally players are not aware of what the top card of their deck is.

{% include carousel.html number="2" %}

## Compelling uses of hidden information
Of all the mechanics in card games, random elements may generate the greatest excitement (or disappointment), but hidden information makes for tense decisions. Simply think of facing a _Dawnblade_ attack. If the opposing _Dorinthea_ player has any resources and cards left in their hand, you are faced with a decision which you have to base on incomplete information. They might only have an attack reaction with __reprise__, in which case blocking with equipment or a defence reaction from arsenal is preferable, but they might just as well have an unconditional pump or _Twinning Blade_, in which case you would rather save your equipment for a later turn. 

{% include carousel.html number="3" %}

Similarly, _Uzuri_'s ability can set up nailbiter scenarios as well. If you have a valuable card in arsenal, every single __stealth__ card poses the question "Will you commit 6 block to ensure that you are not hit with _Command and Conquer_?" A slight variation on this question is whether you want to play a defence reaction after _Uzuri_ has activated her ability, but before the attack is revealed on the off chance that you can no longer react with it afterwards if they do reveal a _Command and Conquer_.

{% include carousel.html number="4" %}

For me, the central questions that emerge from these examples are "Do they have it?" and "What do they have?". So how can we apply this concept to the pitch zone?

## Hidden pitch
In general, if a card is not free to play, you have to pitch one or more cards to pay for it. The pitched cards are placed face up in your pitch zone and are put on the bottom of your deck at the end of each turn. So what can we do with the concept of hidden pitch? And how do we make it different from _Enlightened Strike_'s additional cost?

### __Cloak__ keyword
I will center my examples around a new keyword, which I will call __cloak__. It has the following effect:

> As an additional cost to play this, pitch a card face down. At the end of the defend step, turn the pitched card face up (do not gain resources). Then, gain each mode for which there is at least one card in your pitch zone with the specified properties.

This keyword is then paired with modes that specify a card property and an associated ability. Similarly to _Uzuri_'s ability, this creates a layer of tension during the defend step of the attack since your opponent is never quite sure what they are defending against.

Since the property of the cards in the pitch zone can really be anything, there are numerous options. Let us consider a few with some examples.

### Color strip
Since we are dealing with the pitch zone, the first property that comes to mind might be the color strip. Taking inspiration from the _Widespread_ cycle of majestic Shadow Runeblade attacks, the example _Widespread Agony_ represents a combination of all three of those original _Widespread_ cards. However, now its effect is tied to the __cloak__ mechanic and the cards in the pitch zone. True to the Shadow talent, it can be played from the banished zone, but only if you do not have any cards in your pitch zone yet, thus limiting its effect. On the other hand, if you play it from hand, you may be able to set up more cards in the pitch zone to gain multiple effects. Decisions, decisions. (Note that you could play it from the banished zone and holding priority, react with a non-zero cost instant to squeeze out an extra effect though.)

{% include carousel.html number="5" %}

### Types
Alternatively, one could consider card types in the pitch zone. As an example of this, consider this twist on the much-discussed classic _Command and Conquer_. This version has all the effects of the original, but requires the player to do a bit more setup to get both effects. Additionally, it would require the player to construct their deck in a certain way. Of course, depending on the deck's playstyle, it could also be constructed to take advantage of only one of the two modes. However, since decks typically don't run too many attack and defence reactions, you have room to declare no blocks and call their bluff.

{% include carousel.html number="6" %}

### Other properties
Finally, without presenting specific examples, there are a myriad other ways to leverage this mechanic. Brute cards could refer to the attack value, Guardian cards to the defence value, talented cards to other cards of that talent, you name it. The design space here is only limited by the properties and keywords on cards. Furthermore, unlike both examples presented above, cards could combine a regular resource cost and a __cloak__ cost to enable the activation of multiple modes.

## Conclusion
I would like to see more unique interactions with the pitch zone, and in this article I have presented one possible twist on the pitch mechanic. Rather than pitching face up, the pitched card remains hidden until after your opponent declares blocking cards, at which point the pitched card is revealed and the attack gains abilities based on the properties of the cards in your pitch zone. This gives attacking players more options to bluff and creates a tense blocking phase. And of course, the defending player is always free to call your bluff and take it on the chin.

As usual, if you enjoyed this article or have feedback, please reach out to me!