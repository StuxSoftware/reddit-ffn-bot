# Fanfiction Data Bot for Reddit

[![Join the chat at https://gitter.im/tusing/reddit-ffn-bot](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/tusing/reddit-ffn-bot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

#### New features!
##### - Parse multiple links in a single call using semicolons: ```linkffn(fic1; fic2; fic3; fic4)```
##### - Automatically find links to fanfics in a comment and reply, without even calling the bot by adding  ```ffnbot!directlinks``` to a comment

###**USAGE, TIPS, AND TRICKS**

#### SUPPORTED WEBSITES:
#### *`linkffn(...)`* ([fanfiction.net](https://www.fanfiction.net/))
#### *`linkao3(...)`* ([archiveofourown.org](http://archiveofourown.org/))
#### *`linkffa(...)`* ([hpfanficarchive.com](http://www.hpfanficarchive.com/stories/))
#### *`linkfp(...)`* ([fictionpress.com](https://www.fictionpress.com/))

&nbsp;

#### *The following tips apply for all supported websites!*

***To link Harry Potter and the Natural 20:***

* You can use the **name of the story**.
* You can use the **author name** in the link request for more accuracy. This is *especially* helpful if your requested fic has a generic name.
* You can use **direct links**.
* You can use the **story ID**.

You can expect the *last two methods to be the* ***most accurate***.


***Thus, the following will all yield the same result.***
```
linkffn(Harry Potter and the Natural 20)

linkffn(Harry Potter and the Natural 20 by Sir Poley)

linkffn(https://www.fanfiction.net/s/8096183/1/Harry-Potter-and-the-Natural-20)

linkffn(8096183)

---- OR ----

[Check out this awesome fic!](https://www.fanfiction.net/s/8096183/1/Harry-Potter-and-the-Natural-20)
ffnbot!directlinks
```
> [***Harry Potter and the Natural 20***](https://www.fanfiction.net/s/8096183/1/Harry-Potter-and-the-Natural-20) by [*Sir Poley*](https://www.fanfiction.net/u/3989854/Sir-Poley)
>
> >Milo, a genre-savvy D&amp;D Wizard and Adventurer Extraordinaire is forced to attend Hogwarts, and soon finds himself plunged into a new adventure of magic, mad old Wizards, metagaming, misunderstandings, and munchkinry. Updates Fridays.
>
> >Fiction  T - English - Chapters: 72   - Words: 301,307 - Reviews: 5,265 - Favs: 3,749 - Follows: 4,307 - Updated: 2/275/7/2012 - id: 8096183
>
>
>
> *Read usage tips and tricks  [here](https://github.com/tusing/reddit-ffn-bot/blob/master/README.md).*

&nbsp;

**You can namedrop multiple links in a comment.**
**You can separate queries with semicolons.**

```
Check out this completely awesome fic I found! linkffn(By the Divining Light by enembee) and it's sequel! linkffn(Conlaodh's Song enembee)

or

Check out these awesome fics! linkffn(By the Divining Light; Conlaodh's Song)
```
> [***By the Divining Light***](https://www.fanfiction.net/s/5201703/1/By-the-Divining-Light) by [*enembee*](https://www.fanfiction.net/u/980211/enembee)
>
> >Book 1. Follow Harry and Dumbledore as they descend into the depths of Old Magic seeking power and redemption in equal measure. En route they encounter ancient enchantments, a heliopath and an evil that could burn the world.
>
> >Fiction  T - English - Fantasy/Adventure -  Harry P., Albus D. - Chapters: 6   - Words: 24,970 - Reviews: 127 - Favs: 518 - Follows: 168 - Updated: 1/23/20107/8/2009 - Status: Complete - id: 5201703
>
>
>
> [***Conlaodh's Song***](https://www.fanfiction.net/s/5971274/1/Conlaodh-s-Song) by [*enembee*](https://www.fanfiction.net/u/980211/enembee)
>
> >Book 2. As the Second War begins, Voldemort becomes obsessed with harnessing the realm of Old Magic to his own ends. Meanwhile, Harry has to contend with the Ministry, ancient foes and the machinations of a world he barely understands.
>
> >Fiction  T - English - Fantasy/Adventure -  Harry P., Luna L. - Chapters: 13   - Words: 57,777 - Reviews: 201 - Favs: 470 - Follows: 283 - Updated: 4/28/20115/14/2010 - Status: Complete - id: 5971274
>
>
>
>
> *Read usage tips and tricks  [here](https://github.com/tusing/reddit-ffn-bot/blob/master/README.md).*
