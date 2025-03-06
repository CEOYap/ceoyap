---
title: "WIP1: Dota 2 Collectible Card Game"
date: 2017-03-30
categories:
- Dota 2 CCG
keywords:
- dota 2
autoThumbnailImage: true
thumbnailImagePosition: "left"
coverImage: ////goo.gl/PwUaNc
metaAlignment: center
---
A simple free CCG using Unreal Engine that has the same ruleset as Hearthstone so that the game will be easy for newbies to pickup.
<!--more-->

## Why Dota 2?

Dota 2 was chosen as the main theme of the game due to the fact that i love to play the game so much! I've accumulated 834 hours on the game. Beside that the game is really well known throughout the world. The only problem with Dota 2 is that the game is not fully appreciated by Valve themselves. Even though the prize pool for "The International" is really high, it seems their budget for public marketing is really low. There are few cinematics that are made by Valve and most of them are by the community (Thanks to Source Filmmaker). 

## Why use Unreal Engine and not Unity?

I know that it's possible to use the in-game engine to make a custom card game and share it workshop. The problem is Dota 2 has shitty workshop support. There are many developers that have stopped updating their custom game to the latest playable version because there are so many broken game functions. 

I have a handful of experience on Unity engine when i was developing a multiplayer first person shooter and it was easy to understand the engine usage. The community are really amazing and helpful. Beside that, there are so many things that are available in the market that can be used to learn and develop your first game. 

The unique thing about Unreal Engine is that the image processing fx are already available in the engine and the engine itself are already made extra better for certain genre (FPS, Survival Games, Board games and etc). Dota 2 CCG will be based on the [CCG toolkit](https://www.unrealengine.com/marketplace/ccg-toolkit) that is available in the unreal engine market. 

---

### To do:

* All Dota 2 heroes and items

* New menu

* New battleground design

---
# Card Design

It took me roughly 4 hours to complete the design of the cards using Photoshop. To be honest, i'm a Photoshop newbie so i've downloaded some free vectors and masked it, and i also took some design from hearthstone 
cards especially [Pandaria](https://hydra-media.cursecdn.com/hearthstone.gamepedia.com/thumb/4/4c/Card_back-Pandaria.png/200px-Card_back-Pandaria.png?version=21f7de7534dda27a0df0f9113b27ec68) for the backing.

![Cards preview](https://i.imgur.com/alJvniC.png "Cards preview")

After completing the design, i realise the card design doesn't fit the main theme of Dota 2. The card looks too chinese and colourful. Therefore, i've attached a template for the card design. 

Specification:

* Card Size - 768x1024

{{< alert warning >}}
Size should be resized to 512x1024 due to weird engine function.
{{< /alert >}}

## Download .psd templates (Mega links)

* [CARD FRONT](https://mega.nz/#!o5FyVSZB!6GVTi0mVftrnwJLtqi3dtEb5AEOjn7lmo_SEzTVveLs)
* [CARD BACK](https://mega.nz/#!xsEnVBqJ!VpTlrqyvUozFRWvWXN3Igz260cMFb4rxP44X9Mwvtw4)

---
# Hero portraits

Dota 2 fan communities are really amazing! The fan arts they've made are almost as if VALVE themselves are making them! 

It only took me a few hours to look up for the best suitable hero portraits for the cards. Though, i am unable to give credits as i am not sure who the artists are. I will reverse-search the images through google to find the artist name and give appropriate credits.

![Resized hero portraits](https://i.imgur.com/WaltrZQ.png "Resized hero portraits")

The hero card portraits has to be resize to 512x512, in order to fit the card. In total, i resized 118 pictures.

---
# In-game deck builder

The toolkit has a working deck builder and as you can see in the picture, i've succeeded in adding Abaddon and Alchemist into the game. Adding new deck to the toolkit is quite tough because there are many nodes that are needed to be attached inside the blueprints.

![Abaddon](https://i.imgur.com/M8txUOI.png "Abaddon added!")

There are 113 Dota 2 heroes and that does not include sub-units such as spiderlings, treants, wolves and etc. So adding new cards to the game is really tough and slow process as the toolkit uses Datatable to organise cards. Therefore, i have to add the card data one-by-one.

---
# Closing thoughts

Completing the game is an almost impossible task for me. There are so many task that i have to complete for my studies and i have to prepare for my future medical school. I will try my best to keep you guys updated with the game development so do stay tuned for new updates.

---
