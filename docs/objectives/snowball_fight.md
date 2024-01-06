---
icon: fontawesome/solid/snowman
---

# Snowball Fight

**Difficulty**: :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:<br/>
**Direct link**: [Snowball Fight Terminal](https://hhc23-snowball.holidayhackchallenge.com/?&challenge=snowballhero)

## Objective

!!! question "Request"
    Visit Christmas Island and talk to Morcel Nougat about this great new game. **Team up with another player** and show Morcel how to win against Santa!

??? quote "Morcel Nougat"
    Hey there, I'm Morcel Nougat, elf extraordinaire!<br>
    You won't believe this, but we're on a magical tropical island called Christmas Island, and it even has snow!<br>
    I'm so glad ChatNPT suggested we come here this year!<br>
    Santa, some elves, and I are having a snowball fight, and we'd love you to join us. Santa's really good, so trust me when I say it's way more fun when played with other people.<br>
    But hey, if you can figure out a way to play solo by tinkering with client side variables or parameters to go solo mode, go for it!<br>
    There's also ways to make the elves' snowballs do no damage, and all kinds of other shenanigans, but you didn't hear that from me.<br>
    Just remember, it's all about having fun and sharing the joy of the holiday season with each other.<br>
    So, are you in? We'd really love your company in this epic snowball battle!

## Hints

??? tip "Consoling iFrames"
    Have an iframe in your document? Be sure to [select the right context](https://gist.github.com/chrisjd20/93771da596ca5e49043f148a845c469f) before meddling with JavaScript.

??? tip "Snowball Super Hero"
    Its easiest to grab a friend play with and beat Santa but tinkering with client-side variables can grant you all kinds of snowball fight super powers. You could even take on Santa and the elves solo!

## Solution

Open the terminal and play the game. Set the mode to "VS SANTA" and select "CREATE PRIVATE ROOM".

![Start menu](../img/objectives/snowball_fight/start_menu.png)

In the address bar, change ```singlePlayer=false``` to ```singlePlayer=true``` and reload the page.

![Address bar](../img/objectives/snowball_fight/address_bar.png)

Throw snowballs at the elves and Santa until you are the last one standing. If you couldn't beat Santa, you can always disable damage using the developer console by replacing the ```player.takeHit``` function.

![Disable damage](../img/objectives/snowball_fight/disable_damage.png)

!!! success "Answer"
    Hack the snowball fight game to beat Santa.

## Response

!!! quote "Morcel Nougat"
    You're like a snowball fighting ninja! A real-life legend. Can I have your autograph!?
