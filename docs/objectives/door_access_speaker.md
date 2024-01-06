---
icon: fontawesome/solid/door-open
---

# Space Island Door Access Speaker

**Difficulty**: :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:<br/>
**Direct link**: [Door Access Terminal](https://islanddoor.space/?&challenge=accessspeaker&id=a236ba23-ae73-475b-a7b6-2bc6f481e759)

## Objective

!!! question "Request"
    There's a door that needs opening on Space Island! Talk to Jewel Loggins there for more information.

??? quote "Jewel Loggins"
    What are _you_ doing here, and who are you?<br>
    Me first? I'm Jewel Loggins. And I was trekking through the jungle and happened to find this place.<br>
    I liked this spot and decided to set up camp. Seeing you here is quite the surprise.<br>
    Well, because the only other person I've ever seen come here is Wombley Cube.<br>
    I thought this tram station in the middle of the jungle was strange to begin with, but then Wombley added to the intrigue.<br>
    I guess all this spy stuff is typical for him, so maybe I shouldn't think much of it. I'm sure everything's fine.<br>
    Every time he comes here, he says something to the speaker. Then, the door opens, and he rides the tram somewhere.<br>
    I gave it a try, but the door didn't open for me. Knowing Wombley, it's some kind of secret passphrase.<br>
    If you wanna see where the tram goes, I think you need to find out what that passphrase is.<br>
    Ribb Bonbowford over at Coggoggle Marina on Steampunk Island works with Wombley. Try asking if he knows.<br>
    I hope you find it. I'll be here when you get back!

## Hints

??? tip "MFA: Something You Know"
    Wombley says a specific phrase into the Access Speaker. He works in the Research Department and everything they do it super secret, so it may be a challenge to find out what the phrase is. Ribb also works in that department. Try to find and ask him.

??? tip "MFA: Something You Are"
    It seems the Access Speaker is programmed to only accept Wombley's voice. Maybe you could get a sample of his voice and use an AI tool to simulate Wombley speaking the passphrase.

## Solution

First, complete the [Active Directory](./active_directory.md) challenge and list the contents of the secret file.

![Passphrase](../img/objectives/door_access_speaker/passphrase.png)

Then talk to Jewel Loggins.

!!! quote "Jewel Loggins"
    What, you know the passphrase!? Let me try it!<br>
    Nope, didn't work. Knowing Wombley, the passphrase isn't the only requirement. He's all about that MFA!<br>
    Oh yeah, multi-factor authentication! The passphrase for something he knows, and his voice for something he is!<br>
    That's it! You need to be Wombley. You need his voice. Now, how are you gonna get that?<br>
    Since only us elves can get a subscription to use ChatNPT, try searching for another AI tool that can simulate voices. I'm sure there's one out there.

You can mimic Wombley's voice with [PlayHT](https://play.ht/).<br>
Go to ```Voice Cloning``` and upload a sample of Wombley's voice. The sample can be found on Film Noir Island.

![Clone Voice](../img/objectives/door_access_speaker/clone_voice.png)

Create a new file and select Wombley's cloned voice.

![Select Voice](../img/objectives/door_access_speaker/select_voice.png)

Next, generate the speech.

![Generate](../img/objectives/door_access_speaker/generate.png)

Download the generated speech file and select the downloaded file when you click on the door speaker.

!!! success "Answer"
    And he whispered, 'Now I shall be out of sight; So through the valley and over the height.' And he'll silently take his way.

## Response

!!! quote "Jewel Loggins"
    Are you like a master spy or something? I've only seen stuff like that in the movies!<br>
    It sure is scary what you can do with AI, huh? I sure hope ChatNPT has better guardrails in place.
