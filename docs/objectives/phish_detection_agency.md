---
icon: fontawesome/solid/fish
---

# Phish Detection Agency

**Difficulty**: :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:<br/>
**Direct link**: [Phish Detection Agency Terminal](https://hhc23-phishdetect-dot-holidayhack2023.ue.r.appspot.com/?&challenge=phishdetect&id=3fee9a35-a48f-4f13-8cc7-12eb2a8140fe)

## Objective

!!! question "Request"
    Fitzy Shortstack on Film Noir Island needs help battling dastardly phishers. Help sort the good from the bad!

??? quote "Fitzy Shortstack"
    Just my luck, I thought...<br>
    A cybersecurity incident right in the middle of this stakeout.<br>
    Seems we have a flood of unusual emails coming in through ChatNPT.<br>
    Got a nagging suspicion it isn't catching all the fishy ones.<br>
    You're our phishing specialist right? Could use your expertise in looking through the output of ChatNPT.<br>
    Not suggesting a full-blown forensic analysis, just mark the ones screaming digital fraud.<br>
    We're looking at all this raw data, but sometimes, it takes a keen human eye to separate the chaff, doesn't it?<br>
    I need to get more powdered sugar for my donuts, so do ping me when you have something concrete on this.

## Hints

??? tip "DMARC, DKIM, and SPF, oh my!"
    Discover the essentials of email security with DMARC, DKIM, and SPF at [Cloudflare's Guide](https://www.cloudflare.com/learning/email-security/dmarc-dkim-spf/).

## Solution

To complete this challenge, simply mark the emails as phishing if they fail any of the checks.

### Safe Email

![Pass](../img/objectives/phish_detection_agency/pass.png)

### Phishing Emails

Failed DMARC:

![Fail 1](../img/objectives/phish_detection_agency/fail1.png)

Wrong domain:
![Fail 2](../img/objectives/phish_detection_agency/fail2.png)

### Success

![Success](../img/objectives/phish_detection_agency/success.png)

!!! success "Answer"
    Figure out which emails are phishing attempts.
    
## Response

!!! quote "Fitzy Shortstack"
    You've cracked the case! Once again, you've proven yourself to be an invaluable asset in our fight against these digital foes.
