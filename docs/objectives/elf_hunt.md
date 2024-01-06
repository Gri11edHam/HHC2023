---
icon: material/duck
---

# Elf Hunt

**Difficulty**: :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:<br/>
**Direct link**: [Elf Hunt Terminal](https://elfhunt.org/?&challenge=elfhunt&id=494a7135-624b-4ee1-823a-b523edb9e92e)

## Objective

!!! question "Request"
    Piney Sappington needs a lesson in JSON web tokens. Hack Elf Hunt and score 75 points.

??? quote "Piney Sappington"
    Hey there, friend! Piney Sappington here.<br>
    You look like someone who's good with puzzles and games.<br>
    I could really use your help with this Elf Hunt game I'm stuck on.<br>
    I think it has something to do with manipulating JWTs, but I'm a bit lost.<br>
    If you help me out, I might share some juicy secrets I've discovered.<br>
    Let's just say things around here haven't been exactly... normal.<br>
    So, what do ya say? Are you in?<br>
    Oh, brilliant! I just know we'll crack this game together.<br>
    I can't wait to see what we uncover, and remember, mum's the word!<br>
    Thanks a bunch! Keep your eyes open and your ears to the ground.

## Hints

??? tip "JWT Sectrets Revealed"
    Unlock the mysteries of JWTs with insights from [PortSwigger's JWT Guide](https://portswigger.net/web-security/jwt).

## Solution

To complete the challenge, click the elves before they go offscreen. You need to click 75 elves to win. If the elves are moving too fast and you can't click them, you can slow them down by changing the cookie.

![Cookie](../img/objectives/elf_hunt/cookie.png)

To do this, copy the part of the cookie between the two periods.

![Second Part](../img/objectives/elf_hunt/second_part.png)

Then decode it as base64.

![Decode](../img/objectives/elf_hunt/decode.png)

Next, change the value of speed and re-encode it.

![Re-encode](../img/objectives/elf_hunt/re_encode.png)

Finally, paste the new value back into the cookie and reload the page.<br>
After reloading, you should have an easier time clicking the elves.

![Win](../img/objectives/elf_hunt/win.png)

!!! success "Answer"
    Click the elves to win the game.

## Response

!!! quote "Piney Sappington"
    Well done! You've brilliantly won Elf Hunt! I couldn't be more thrilled. Keep up the fine work, my friend!<br>
    What have you found there? The Captain's Journal? Yeah, he comes around a lot. You can find his comms office over at Brass Buoy Port on Steampunk Island.
