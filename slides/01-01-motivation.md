<!-- $theme: gaia -->

<!-- $size: 16:9 -->

<!-- page_number: true -->

<!-- footer: Copyright (c) by Bjoern Kimminich | Licensed under CC-BY-SA 4.0 -->

# Motivation

---

# Security = :interrobang:

---

# Security

> The state of being free from danger or threat. \[[^1]\]

[^1]: https://en.oxforddictionaries.com/definition/security

---

# Vulnerability = :interrobang:

---

# Vulnerability

> A **flaw or weakness in system** security procedures, design, implementation, or internal controls **that could […] result in a security breach** or a violation of the system's security policy \[[^2]\]

[^2]: http://csrc.nist.gov/publications/nistpubs/800-30/sp800-30.pdf

---

# Exploit = :interrobang:

---

# Exploit

> A piece of software, a chunk of data, or a sequence of commands that **takes advantage of a bug or vulnerability to cause unintended or unanticipated behavior** to occur on computer software, hardware, or something electronic (usually computerized) \[[^3]\]

[^3]: https://en.wikipedia.org/wiki/Exploit_(computer_security)

---

# Zero Day = :interrobang:

---

# Zero-Day

> **A zero day vulnerability** refers to a hole in software that **is unknown to the vendor**.
>
> This security hole is then **exploited by hackers before the vendor becomes aware** and hurries to fix it—this exploit is called a zero day attack. \[...\]
>
> The term **“zero day” refers to the unknown nature** of the hole to those outside of the hackers, specifically, the developers. Once the vulnerability becomes known, a race begins for the developer, who must protect users. \[[^4]\]

[^4]: https://web.archive.org/web/20170704035927/http://www.pctools.com/security-news/zero-day-vulnerability/

---

# Exercise 1.1 (:pushpin:)

## Brainstorming Attackers

1. Identify and describe possible **Attackers** and their motivation
2. Rate the danger posed by each attacker type (:skull: to :skull::skull::skull:)
3. Estimate the risk of your own employer being targeted by each identified attacker type (in %)
4. Which attacker types are likely to work together and how does this impact their danger rating?

---

# Advantage of the Attacker

* Attacker must **succeed once**
  * Defender must get it right _all the time_
* Attacker can choose the **weakest spot**
  * Defender must defend _all places_
* Attacker can leverage **zero-days**
  * Defender can only defend against _known attacks_
* Attacker can **play dirty**
  * Defender needs to _play by the rules_

---

# Case Studies

---

<!-- *footer: -->

# Data Breaches (by no. of records)

[![Data Breaches by no. of records](images/01-01-motivation/worlds_biggest_data_breaches-by_no_records.png)](http://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/)

---

<!-- *footer: -->

# Data Breaches (by data sensitivity)

[![Data Breaches by data sensitivity](images/01-01-motivation/worlds_biggest_data_breaches-by_sensitivity.png)](http://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/)

---

# Aadhaar (January 2018)

> Today, The Tribune “purchased” a service being offered by anonymous sellers over WhatsApp that provided unrestricted access to details for any of the more than 1 billion Aadhaar numbers created in India thus far. [[^4]]

![Aadhaar logo](images/01-01-motivation/300px-Aadhaar_Logo.svg.png)

---

> It took just Rs 500, paid through Paytm, and 10 minutes in which an “agent” of the group running the racket created a “gateway” for this correspondent and gave a login ID and password \[...\] and instantly get all particulars that an individual may have submitted to the UIDAI (Unique Identification Authority of India), including name, address, postal code (PIN), photo, phone number and email.
>
> What is more, The Tribune team paid another Rs 300, for which the agent provided “software” that could facilitate the printing of the Aadhaar card after entering the Aadhaar number of any individual. \[[^5]\]

_800 Indian Rupee equals 10.04 Euro (28.06.2018)_ :money_with_wings:

[^5]: http://www.tribuneindia.com/news/nation/rs-500-10-minutes-and-you-have-access-to-billion-aadhaar-details/523361.html

---

# Equifax (September 2017)

> If you have a credit report, there’s a good chance that you’re one of the 143 million American consumers whose sensitive personal information was exposed in a data breach at Equifax, one of the nation’s three major credit reporting agencies. [[^5]]

![Equifax logo](images/01-01-motivation/281px-Equifax_Logo.svg.png)

---

> Here are the facts, according to Equifax. The breach lasted from mid-May through July. The hackers accessed people’s names, Social Security numbers, birth dates, addresses and, in some instances, driver’s license numbers. They also stole credit card numbers for about 209,000 people and dispute documents with personal identifying information for about 182,000 people. And they grabbed personal information of people in the UK and Canada too. \[[^6]\]

_Recommended steps for protection include "monitor your existing credit card and bank accounts closely" but also "consider placing a credit freeze" :icecream: or "placing a fraud alert on your files"._

[^6]: https://www.consumer.ftc.gov/blog/2017/09/equifax-data-breach-what-do

---

# VTech (November 2015)

> \[...\] When it comes to our identities being leaked all over the place, it’s just another day on the web. **Unless it’s our children’s identities, that’s a whole new level.** When it’s hundreds of thousands of children including their names, genders and birthdates, that’s off the charts. [[^7]]

![VTech logo](images/01-01-motivation/VTechLogo.png)

---

> When it includes their parents as well – along with their home address – and you can link the two and emphatically say “Here is 9 year old Mary, I know where she lives and I have other personally identifiable information about her parents (including their password and security question)”, I start to run out of superlatives to even describe how bad that is. \[[^7]\]

_It later came out that head shots :camera: of kids and private chat messages were also exposed. The total number of children exposed in the incident is over 6.3 million._

[^7]: https://www.troyhunt.com/when-children-are-breached-inside

---

# CloudPets (February 2017)

> \[...\] There were a lot of news headlines about how Germany had banned an internet-connected doll called "Cayla" over fears hackers could target children. One of their primary concerns was the potential risk to the privacy of children \[because\] conversations between the child and others can be recorded and forwarded. \[[^8]\]

![CloudPets logo](images/01-01-motivation/CloudPets_LogoNew.png)

---

> \[...\] Put yourself in the shoes of the average parent, that is one who's technically literate enough to know the wifi password but not savvy enough to understand how the "magic" of daddy talking to the kids through the bear (and vice versa) actually works. They don't necessarily realise that every one of those recordings – those intimate, heartfelt, extremely personal recordings – between a parent and their child is stored as an audio file on the web. They certainly wouldn't realise that in CloudPets' case, that data was stored in a MongoDB that was in a publicly facing network segment without any authentication required and had been indexed by Shodan (a popular search engine for finding connected things). [[^8]]

_Impacted parents were never notified by CloudPets. :scream:_

[^8]: https://www.troyhunt.com/data-from-connected-cloudpets-teddy-bears-leaked-and-ransomed-exposing-kids-voice-messages

---

# Exercise 1.2 _(optional)_

## Have I been pwned?

1. Visit <https://haveibeenpwned.com/>
2. Type in your email address
3. Hit the `pwned?` button

![Good news - No pwnage found!](images/01-01-motivation/haveibeenpwned-green.png) ![Oh no - pwned!](images/01-01-motivation/haveibeenpwned-red.png)

---

# Exercise 1.3 (:house:)
1. Mark potentially malicious items in the Press Kit from the _Trump-Kim Summit_ (2018) in the image on the next slide (:arrow_right:)
2. Explain possible ways how these items might actually be malicious
3. Reason about potential attackers behind this and explain their most likely motivations
4. Come up with a least two more additions to the Press Kit and explain how they could be used maliciously

:information_source: _Speculation is allowed, but still be as specific as possible!_

---

<!-- *footer: -->

![Press kit from Trump-Kim Summit in Singapore 2018](images/01-01-motivation/TrumpKimSummit_PressKit.png)
