---
title: Double-sided heroes
author: PMD
date: 2024-05-03 17:59:00 +/-0000
image:
  path: /assets/img/posts/2024/cover-fliphero.png
categories: [Card design]
tags: [hero, card]
carousels:
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/UPR007.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/UPR007_A_Back.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD005.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD005_BACK.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DYN092.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DYN092_Special.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/EVO010.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/EVO010_BACK.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD164.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD164_BACK.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-WTR113.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DVR001.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/BOL002.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD209.width-450.format-webp.webp
  - images:
    - image: /assets/img/posts/2024/015-fliphero.png
    - image: /assets/img/posts/2024/016-fliphero.png
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/HVY240.width-450.format-webp.webp
  - images:
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-MON061.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/DTD047.width-450.format-webp.webp
    - image: https://dhhim4ltzu1pj.cloudfront.net/media/images/U-MON063.width-450.format-webp.webp
    # - image: Saving Grace 
---

With the release of [Uprising](https://fabtcg.com/products/booster-set/uprising/), Flesh and Blood introduced double-sided cards for the first time in the form of Invocation cards for the Draconic Illusionist hero. When played, these cards flip and create a Dragon ally permanent that stays in the arena, printed on the back. Since then, double-sided cards have been used by Light Illusionists to transform Figments into Angel allies, and by Mechanologists to assemble ~~Exodia~~ the Nitro Mechanoid or conquer mortality by becoming ~~Iron Man~~ Mechropotent. Whilst the Illusionist cards transform themselves into something else, the Mechanologist cards transform your equipment and your hero into something else, respectively. Finally, Shadow Brute has a double-sided demi-hero card for Levia, but its two sides do not interact with each other. In this article, we are busting out the blender and mashing flip mechanics and double-sided heroes together to create unique play patterns!

{% include carousel.html number="1" %}

## Designing double-sided heroes
So what do I have in mind when I say double-sided heroes? In this article, we explore the idea of a hero card that features an ability on each side, as well as a condition to flip to the other side.

### Why?
Aside from their aesthetic, the main reason to pick a hero is their playstyle. Generally, that playstyle is strongly informed by their hero ability because it often determines what you try to do on any given turn. So if your enjoyment of a hero comes from their hero ability, would you enjoy playing a hero twice as much if they had two abilities? Okay, maybe not, but there is something utterly satisfying about checking a box to enable future plays. Many heroes have an ability that you are ideally activating every turn to gain maximal value out of it, thus resulting in typical play patterns contained within one turn. By introducing a hero that you ideally want to flip each turn, you are creating a play pattern that spans two turns for optimal use.

### Ability talk
Okay, let's say you are designing a double-sided hero with a flip mechanic. How do you go about this? I think there are two concrete approaches. In the first approach, both sides feature an equally desirable ability, where (at least) one side plays well into the other such that you are incentivised to flip regularly. In the other approach, you create one weak side and one strong side, but give the strong side a drawback that is not sustainable over multiple turns (e.g. lose health, discard cards, destroy your arsenal, etc.), forcing you to flip back at times. I believe both are fine approaches and will yield very different play experiences and agonising decisions, especially in the latter case (maybe ideal for a Shadow hero?). However, in the rest of this article, I will focus on the first case.

## Example: Dorinthea reimagined
To illustrate the first design, consider fan favourite Warrior _Dorinthea_. This hero is centered around weapon attacks, and both of her designs focus on enabling her to attack an additional time with (one of) her weapon(s). However, her weapons do not have inherent __go again__, so to make use of her ability, she needs to find a way to give her weapon __go again__ first. Lore-wise, the War of the Monarch just led to her losing her trusted mentor and friend, _Minerva Themis_, at _Morlock Hill_, immortalised on a card of the same name. Considering both Light heroes, Boltyn and Prism, lost someone dear to them (Boltyn lost his wife, Prism presumably lost her parents), I wonder if this is the key to unlocking the Light talent. For this example, I will assume it is and reimagine Dorinthea's rebirth as a Light Warrior.

{% include carousel.html number="2" %}

The only Light Warrior we have so far uses his soul to give his attacks __go again__, so combining this with Dorinthea's signature effect left me with the following idea for a double-sided hero:

{% include carousel.html number="3" %}

At face value, the premise is simple: you __charge__ to create an Agility token and flip to the other side. Next turn, the Agility token gives your weapon swing __go again__ and if you hit, you can banish the card you __charged__ last turn to swing again and flip back to the other side. This creates a simple play pattern where you just set up for a turn by blocking with 2 cards and __charging__ with the remaining 2 during your own turn, followed by a more powerful follow-up turn. However, if you have a way of putting a card in soul during your opponent's turn whilst on the _Duskchaser_ side, like _Halo of Illumination_, _Soulbond Resolve_, or _Soul Shield_, or with the newly revealed cards from the [Boltyn Armory Deck](https://fabtcg.com/products/booster-set/armory-deck-boltyn/), you can effectively create a source of __go again__ on each of your turns, if you want. Powerful stuff!

{% include carousel.html number="4" %}

However, if you fail to hit on the _Dawn's Vengeance_ side, you cannot flip back to the _Duskchaser_ side. True to Dorinthea's playstyle, this means you probably want to include quite a few attack reactions in your deck to push through. A hero like this thus poses an interesting deckbuilding puzzle, where you both need enough cards to charge and enough cards to push through hits. Though you could print identical flip clauses on both sides, I believe these distinct conditions contribute a lot to how the hero wants to play.

## Conclusion
That's it for this week! We had a look at heroes with two abilities, one on each side of the card, with a condition to flip to the other side. As I mentioned, there are at least two ways of designing a hero like that (incentivised flipping for optimal play and powerful side with an upkeep cost), but there are definitely more than the ones discussed above. I believe this is a particularly interesting design space as it pushes a playstyle that spans multiple turns, which is not necessarily the case for some of the other hero abilities.

If you enjoyed this article, please leave a like on my socials and share the idea at your next Armory (or with your local LSS dev)!