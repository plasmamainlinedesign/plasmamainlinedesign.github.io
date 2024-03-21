---
title: Conditional costs
author: PMD
date: 2024-03-22 17:59:00 +/-0000
image:
  path: /assets/img/posts/2024/cover-conditionalcost.png
categories: [Card design]
tags: [card, cost]
carousels:
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR159.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR14.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR191.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR200.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR203.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR188.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/007-conditionalcost.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR215.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-ARC200.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-MON192.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/008-conditionalcost.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR150.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-MON223.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/EVR011.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/009-conditionalcost.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-MON168.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD158.width-450.format-webp.webp
---

Though the main currency in Flesh and Blood is resources, which you pay by pitching cards, the rules also define the concept of an additional cost. This is typically a non-resource cost that has to be paid before a card is considered played, like putting a card from your hand on the bottom of your deck for _Enlightened Strike_ or discarding a random card from your hand for _Savage Feast_. At the same time, the game features conditional effects that are active if a certain condition is met, like the __go again__ clause on _Scar for a Scar_ or the conditional +1 damage on _Wounded Bull_. In this article, we are putting the two together to create conditional costs and discuss how they establish an intriguing design space.

{% include carousel.html number="1" %}

## What is a conditional cost?
Before we do anything else, let us define conditional costs. A conditional cost is a cost to play a card that you only have to pay if a specified condition is met. In and of itself, this is already a fun design proposition because there are two aspects here to play with: the cost and the condition. The cost could simply be resources, but it could easily be any type of additional cost that already exists in the game, or something else entirely. Likewise, for the condition, it could compare life totals like _Scar for a Scar_ and _Wounded Bull_, or refer to another aspect of the game state or an event that might have occurred earlier in the turn.

## Why?
The most evident use case for conditional costs might be to act as a limiting factor to what a card can achieve in combination with other cards. This comes down to evaluating cards in a vacuum versus as a piece of a larger whole (the deck or turn). Considering that the most "vanilla" attack action, _Wounding Blow_, costs 0, attacks for 4 and blocks for 3 at red pitch, with _Raging Onslaught_ dealing 1 more damage for each additional resource, a card is considered "on rate" if it presents 4 damage for your action point plus 1 additional damage for each resource it costs to play. If a card were to cost 0 and attack for 5 instead, this would be considered "above rate" and would thus be a good 1-card hand after you have blocked with your other 3 cards. However, for a card to be 0-for-5, there has to be a trade-off. So far, most cards that are considered above rate in some regard are worse at one of the other card aspects, like defence or pitch value. A conditional cost could simply be an alternative balancing factor. It may be a 0-for-5 attack if played as the only card in a turn, but may cost an additional 2 resources if you have played another card that turn, making it considerably worse and below rate in a wider turn.

{% include carousel.html number="2" %}

Since conditional costs can be employed to make cards above and below rate in certain scenarios, they can effectively act as a catch-up mechanic. If you are backed into a corner and forced to block, the straightforward example above allows you to play slightly above rate and maybe eke out enough of a margin to give you a fighting chance. Simultaneously, the card is far from stellar when you are already on the winning hand, making the inclusion in your deck a double-edged sword and perhaps even a commitment to a particular play style.

The design space here that fascinates me the most though, is the one where the conditional cost is not necessarily detrimental, but opens up new play lines.

## Examples
To illustrate my point, let us look at a few examples that I have thrown together.

### Generic
Similarly to attack actions presenting 4 damage at red pitch for no cost, most 0-cost defence reactions, like _Sink Below_ and _Fate Forseen_, defend at the same rate of 4 defence at red pitch. Going back to our idea in the previous section that a card can be either below or above rate depending on the conditional cost, consider the defence reaction _Divine Shelter_ below, which costs nothing and blocks for 5 if you are behind in life, but costs 2 if you are ahead. In this case, if you are on the defensive and have less life than your opponent, you get to block above rate, perhaps blocking a good on-hit effect with a single card (e.g. some of the Ranger arrows). However, if you are ahead in life total, the condition is met and you have to pay 2 resources to play it, bringing the card below rate compared to other 2-cost defence reactions, like e.g. _Guardian of the Shadowrealm_. If you are planning to be behind in life total for most of the game though, e.g. if you are playing a combo deck such as OTK Viserai or Sabers Boltyn, the conditional cost will rarely come up and the card can help you to stay alive until you are ready to go off.

{% include carousel.html number="3" %}

### Brute
As an example of a card where the conditional cost can be turned in your favour, consider this custom Brute card, _Pouncing Predator_. At a rate of 1-for-6, for which it loses its defensive capabilities, it fits very well into the Brute curve that plays lots of 2-cost attacks. A single blue pitch then converts any 2-cost attack with __go again__, e.g. through Agility, plus this into a respectable 3-card play. In addition, if you are behind, this is a solid 1-card play off of _Fyendal's Spring Tunic_. If you are playing Rhinar though, leading with _Pulping_ or _Wild Ride_ will still convert a blue pitch into two attacks, but their discard will make your hero __intimidate__ the opponent and activate the conditional cost of _Pouncing Predator_. Whilst this play now requires an additional card to be discarded, this can actually be a boon when you are trying to close out a game because it allows you to __intimidate__ a second time!

{% include carousel.html number="4" %}

### Shadow Runeblade
Another talent that shines at "fake costs" is Shadow. Since so many Shadow cards can be played from the banished zone (and benefit from it), banishing a card is no longer a real cost, but an opportunity. In this example of a Shadow Runeblade card, _Midnight Offering_ allows you to banish a card from your hand (with __blood debt__ if you want __go again__) if you have dealt arcane damage to your opponent this turn. With Vynnset's ability you can force through this arcane damage and banish e.g. a _Bounding Demigon_ to get __go again__ on this attack and +1 attack on the _Demigon_, assuming you have played a non-attack action, or an attack with __Rune Gate__, if you have the means to generate more runechants that turn. It can also act as set up for a later turn by parking some cards in the banished zone, if you are willing to suffer the __blood debt__. In other words, it allows you to go wider more efficiently if you can satisfy its condition.

{% include carousel.html number="5" %}

## Conclusion
The merging of conditional abilities with additional costs creates an opportunity to make cards above and below rate, depending on whether the condition is met or not. This pushes players to make choices to optimise when they play these cards. Having these cards in your deck will contribute to the push and pull of trading blows that make this game so enjoyable, as both players try to find the perfect window to play each card without paying the conditional cost. Adding another layer on top of this, this mechanic can also be utilised to reward players for performing certain actions through the condition, where the conditional cost may be desirable in certain situations, e.g. to discard and trigger Rhinar's ability. The combinations of conditions and costs are limitless!

If you enjoyed this article or have any thoughts or feedback, I would be happy to hear from you!