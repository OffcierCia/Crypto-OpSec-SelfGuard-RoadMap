
**Here we collect and discuss the best DeFi,Blockchain and crypto-related OpSec researches and data terminals - contributions are welcome.**

**Feel free to submit a pull request, with anything from small fixes to translations, docs or tools you'd like to add.**

[![Support Project](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/DeFi-Developer-Road-Map#support-project) [![Supported by GitCoin](https://img.shields.io/badge/Support%20via-GitCoin-yellowgreen)](https://gitcoin.co/grants/3150/defi-developer-roadmap)
  [![Research Base](https://img.shields.io/badge/Research-Base-lightgrey )](https://github.com/OffcierCia/ultimate-defi-research-base)
       [![Mail](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com) 


```
_________                        __           ________          _________               .____    .__          __   
\_   ___ \_______ ___.__._______/  |_  ____   \_____  \ ______ /   _____/ ____   ____   |    |   |__| _______/  |_ 
/    \  \/\_  __ <   |  |\____ \   __\/  _ \   /   |   \\____ \\_____  \_/ __ \_/ ___\  |    |   |  |/  ___/\   __\
\     \____|  | \/\___  ||  |_> >  | (  <_> ) /    |    \  |_> >        \  ___/\  \___  |    |___|  |\___ \  |  |  
 \______  /|__|   / ____||   __/|__|  \____/  \_______  /   __/_______  /\___  >\___  > |_______ \__/____  > |__|  
        \/        \/     |__|                         \/|__|          \/     \/     \/          \/       \/        
```

> Note: OpSec is a term coming from the military, meaning operational security. It has been widely used to describe security precautions in various sensible activities, and more recently also in cryptocurrency management. 


# **Translations:**

- [Portuguese-Brazilian](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/Portuguese.md)
- [Russian](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/Russian.md)
- [French](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/French.md)


# OpSec SelfGuard RoadMap

**| Special Author's Notes:**

- [My Blog on Mirror](https://officercia.mirror.xyz/UpFfG7-1E4SDJttnmuQ7v4BMc4KrCXzo80vtx7qV-YY)
- [My Blog on Medium](https://officercia.medium.com)

#

#### Problem 1

Use a secure email provider like Protonmail or Tutanota. Also use trused VPN like Mullvad or ProtonVPN. E2E (end-to-end) encryption is only as secure as the service you are sending the email to. For example, if a Protonmail user sends an email to a GMail user, the email is encrypted with TLS, but Google can still read and hand over any data that passes through their server. E2E can be re-established by using features such as the password-protected email feature from Protonmail.

[Watch More](https://www.youtube.com/channel/UCYVU6rModlGxvJbszCclGGw)
[Read More on Email Encryption with Proton](https://proton.me/support/proton-mail-encryption-explained)

---

#### Problem 2

Use different emails and different strong passwords. Store them in one place like a password manager. Never reuse passwords, especially for accounts with personally identifiable and sensitive information (e.g. Facebook, Gmail, AppleID, Twitter, banks/payments, crypto accounts). Use passwords that are at least 8 characters in length, but a minimum of 12 is generally recommended for memorization. Along with that, if using memorization, ensure that a minimum complexity requirement is met: which means having an uppercase character, a lowercase character, a digit, and a non-alphabetic character. 

Using a string of unrelated words while still meeting the dictionary requirement makes it easy to have an extremely secure password while still being able to remember it. If fully relying on a password manager, a password of 20+ characters in length that is randomly generated can be used. If you see suspicious password activity or failed log-ins on any of your accounts, change all of your passwords, starting with sensitive and authorization accounts, such as your primary email and bank/crypto accounts. [KeePass](https://keepass.info) or [KeePassDX](https://www.keepassdx.com) or [KeePassXC](https://keepassxc.org) or BitWarden are good options. I also found [this tutorial](https://forums.linuxmint.com/viewtopic.php?f=42&t=291093) for [integrity check](https://keepass.info/integrity.html) (and other checks) very helpful, be sure to check it out as well: [link](https://forums.linuxmint.com/viewtopic.php?f=42&t=291093).

**On the opposite:**

> For 2FA one can use KeePass + Yubikey as well. KeePass allows setting up TOTP to any entry in your .kdbx file. Yubikey could be used in company with KeePass to add a bit of entropy on each re-encryption when adding an entry in your db file: [Ref No.1](https://developers.yubico.com/Developer_Program/Guides/Touch_triggered_OTP.html); [Ref No.2](https://www.reddit.com/r/KeePass/comments/opx34q/keepassxc_and_yubikeys_setting_up_the); [Ref No.3](https://github.com/keepassxreboot/keepassxc/discussions/6344).

[Read More](https://blog.keys.casa/7-ways-to-level-up-your-bitcoin-opsec/)
[NIST 800-63b Password Guidelines and Best Practices](https://specopssoft.com/blog/nist-800-63b/)

---

#### Problem 3

Never link phone numbers to crypto platforms. Use trusted multiple e-sims if you have to link the phone. To lock down your SIM, contact your mobile phone carrier. Ask them to NEVER make changes to your phone number/SIM unless you physically show up to a specific store with at minimum two forms of identification. This (should) prevent hackers from calling up AT&T or T-Mobile or Vodafone, claiming to be you, and asking them to port your phone number to a new phone.

[Read More](https://medium.com/the-business-of-crypto/fundamentals-of-opsec-in-crypto-7844ba701b1d)

---

#### Problem 4

Instead of SMS-based 2FA, use Authy or Aegis OTP for iOS or Android. Google Authenticator is generally not recommended anymore in order to stay out of the Google ecosystem, and Authy offers more robust account recovery options (Aegis does not offer the same level of account recovery options). Keep in mind that the codes generated by 2FA apps are device specific. If your account is not manually backed up to Google cloud or iCloud and you lose your phone, you’ll need to spend some time proving your identity to restore your 2FA. The added security is worth the hassle!

Hardware-based 2FA options are regarded as more secure than phone-based OTP options since the keys are stored on the YubiKey device itself, not on your phone, or in the cloud, or on your computer.

**On the opposite:**

> Aegis Authenticator is open source (licensed under GPL v3) and the source code [can be found here](http://github.com/beemdevelopment/Aegis). The issue with Authy is that it depends on a phone number which can be changed through an email request, allowing anyone access to HOTP/TOTP after an approximate 4-day wait period. To avoid that, disable multi-device!

[Read More](https://www.threatstack.com/blog/five-opsec-best-practices-to-live-by)

---

#### Problem 5

Cold storage, and separate “hot” wallet. Use multisig (gnosis-safe as example) or at least a hardware wallet. Never store your seed phrase digitally. Seed phrases are intended to be stored on the paper card included with hardware wallets! That means never type it up, store it online, or take a photo of the card. Store your key on hard device.

[Read More](https://digitalguardian.com/blog/what-operational-security-five-step-process-best-practices-and-more)

---

#### Problem 6

Offline back-ups. Store them in a safe. Can be written on paper, but recommended to be etched or laser-printed into metal. Always be sure to have a backup stored somewhere safe if your threat model allows for that. Ask yourself, what happens if my house catches on fire? What temperature is my safe rated to? Some individuals find a safety deposit box handy.

[Read More]([https://www.gocivilairpatrol.com/programs/emergency-services/operations-support/operational-security-opsec](https://unchained.com/blog/how-to-store-bitcoin-seed-phrase-backups/))

---

#### Problem 7

Never do anything you do not understand. Always check which token you approve, transaction you sign, assets you send, etc - be extremely accurate while making any financial operation. Keep in mind that one of possible attack vectors is to put you in a situation that will encourage you to do smth (login or anything like that). You can install malwarebytes or Comodo or DrWeb antivirus but it won't help you if you do not understand them. Keep up your basic set of defending tools up to date. 

[Read More](https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817)

---

#### Problem 8

Be careful about using your real home address online for delivery purposes. Data breaches are now a daily occurrence, and many breaches include customer names and addresses. Your physical address is not as easily changeable as a phone number or email address, so be especially mindful about where you use it on the Internet. If you’re ordering pizza with crypto, order it for pickup instead of delivery. When online shopping, use a different (and publicly available) address for package delivery. Options here include your workplace or drop boxes at delivery service providers like FedEx and your local postal service.

[Read More](https://www.cnbc.com/2017/11/02/heres-how-to-protect-your-bitcoin-and-ethereum-from-hacking.html)

---

#### Problem 9

Remember: You Could Be a Target! We are a natural target for all sorts of attacks — from garden-variety cybercriminals to competitive spying (sounds dramatic, but it’s real!). That said, it doesn’t really matter what industry you’re in. If you have any sensitive, proprietary information at all (and let’s face it, most people in crypto do), then you could very well be a target. This is a good thing to always keep in mind.

[Read More](https://www.cnbc.com/2021/06/11/tips-to-help-keep-your-crypto-wallet-secure.html)

[Read More](https://www.usenix.org/system/files/1401_08-12_mickens.pdf)


---

#### Problem 10

Remain Vigilant -  Create a culture of skepticism where they feel comfortable checking twice before clicking a link or responding to a request for sensitive information, and you’ll have a much more secure organization overall. 

[Read More](https://www.ledger.com/academy/security/hack-wifi)

[Read More](https://anonymousplanet.org/guide.html)


---

#### Problem 11

OpSec often comes into play in public settings. For example, if members of your team are discussing work-related matters at a nearby lunch spot, during a conference, or over a beer, odds are that someone could overhear. As they say, loose lips can sink ships, so make sure you don’t discuss any sensitive company information while out in public.  Many OpSec missteps can be avoided by being more aware of your surroundings and the context in which you are speaking: what you’re saying, where you are, who you’re speaking to, and who might overhear. It’s a good idea to go over the “no-no’s” for your specific company during onboarding and to remind employees of them periodically. 

[Watch More](https://www.youtube.com/watch?v=hxHqE2W8scQy)

---

#### Problem 12

Identify your sensitive data, including your product research, intellectual property, financial statements, customer information, and employee information. This will be the data you will need to focus your resources on protecting.


[Watch More](https://www.youtube.com/watch?v=0aSQMeoz9ow)

---

#### Problem 13

Identify possible threats. For each category of information that you deem sensitive, you should identify what kinds of threats are present. While you should be wary of third parties trying to steal your information, you should also watch out for insider threats, such as negligent employees and disgruntled workers.

[Read More](https://datatracker.ietf.org/wg/opsec/documents/)

---

#### Problem 14

Analyze security holes and other vulnerabilities. Assess your current safeguards and determine what, if any, loopholes or weaknesses exist that may be exploited to gain access to your sensitive data.

[Read More](https://www.lopp.net/bitcoin-information/security.html)

---

#### Problem 15

Appraise the level of risk associated with each vulnerability. Rank your vulnerabilities using factors such as the likelihood of an attack happening, the extent of damage that you would suffer, and the amount of work and time you would need to recover. The more likely and damaging an attack is, the more you should prioritize mitigating the associated risk.

[Read More](https://www.reddit.com/r/opsec/)

---

#### Problem 16

Get countermeasures in place. The last step of operational security is to create and implement a plan to eliminate threats and mitigate risks. This could include updating your hardware, creating new policies regarding sensitive data, or training employees on sound security practices and company policies. Countermeasures should be straightforward and simple. Employees should be able to implement the measures required on their part with or without additional training.

[Read More](https://hackernoon.com/5-tips-to-prevent-hackers-from-stealing-your-crypto-assets-e2243zig)

---

#### Problem 17

Implement separation of duties. Make sure that those who work on your network are not the same people in charge of security.

[Read More](https://arxiv.org/abs/2106.10740)

---

#### Problem 18

Automate tasks to reduce the need for human intervention. Humans are the weakest link in any organization’s operational security initiatives because they make mistakes, overlook details, forget things, and bypass processes.

[Read More](https://web.mit.edu/smadnick/www/wp/2019-05.pdf)

[Read More](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2v)


---

#### Problem 19

Incident response and disaster recovery planning are always crucial components of a sound security posture. Even when operational security measures are robust, you must have a plan to identify risks, respond to them, and mitigate potential damages.

[Read More on Incident Response Plans](https://www.crowdstrike.com/cybersecurity-101/incident-response/)

[Read More](https://trustwallet.com/blog/how-to-stay-safe-on-the-internet-crypto-guide)


---

#### Problem 20

Risk management: The process of identifying, assessing and controlling threats to an organization's capital and earnings. These risks stem from a variety of sources including financial uncertainties, legal liabilities, technology issues, strategic management errors, accidents and natural disasters.

Many individuals from an organization can be in charge of different parts of the risk management process. Through this process, they can discover potential areas for a data breach or other threats. Understanding potential threat vectors is central to this process, as it allows them to be seen before they can be exploited. 

For example:
A hacker delivered a RAT (remote access trojan) onto the computer of an employee. If the RAT has a variety of capabilities, it could steal the cookies from the web browser, sift through files on the computer, and then exfiltrate that data to be sold on a darkweb market at a later date. The operational security steps mentioned in problems 1 through 10 should help prevent this from happening.

Another potential attack is called "DNS Poisoning". It is a "highly deceptive cyber attack in which hackers redirect web traffic toward fake web servers and phishing websites". A web page could appear that looks like a normal login page for a business like GMail, Kraken, etc., but in reality it could be a phishing site made to steal your login information (email/username/password). Separate machines on the same network will not prevent this, as the traffic passes through the router for both machines, so the solution is to have separate networks and to verify website certificates. Some VPN providers use their own DNS servers through the software pakcage they provide, so this could prevent this type of attack as well.

Malware can also have the functionality to "attack" a computer's clipboard. The malware could check the clipboard at a set interval to see if any cryptocurrency addresses are detected in it. If they are, it would then replace the one in the clipboard with one of the hacker's cryptocurrency addresses, which means the cryptocurrency would then be sent to the hacker. The beginning and end may match, but this requires extra functionality on the part of the malware, as it would need to generate wallets on the fly and exfiltrate the keys to the hacker.

[Watch More](https://www.youtube.com/watch?v=pGcerfVqYyU)

[Read More](https://medium.com/@cryptochatjoe/remaining-anonymous-in-todays-crypto-market-a-101-guide-for-the-badass-not-so-techies-7091edffa9aa)

---

#### Problem 21

Your level of opsec usually depends on your threat model and which adversary you're up against. So it's hard to define how good your opsec is. But I'd say it sounds pretty okay. I recommend watching: 

[Watch More](https://www.youtube.com/watch?v=9XaYdCdwiWU)

[Watch More](https://www.youtube.com/watch?v=ixLuRvYlrlw)


---

#### Problem 22

If you use smartphone be extremely aware.

[Read More](https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817)

---

#### Problem 23

Only Interact with DeFi Protocols You Trust - Take your time to read up on some previous concepts we’ve covered such as staking, yield farming, NFT farming, and research any other new terms you may come across before depositing crypto into a DApp that deploys any of these investment strategies. 

[Read More](https://github.com/OffcierCia/ultimate-defi-research-base)

[Read More](https://assets.website-files.com/5ffef4c69be53b44bd10b438/6012f54022181b0d0a3a948c_CryptoCurrency%20Security%20Standards%20Checklist.pdf)


---

#### Problem 24

Use trusted services. Using a secure, easy-to-use crypto wallet to interact with DeFi applications is essential to a safe and user-friendly DeFi experience. Interacting with smart contracts can be tricky for first-time users, so using a beginner-friendly crypto wallet with DApp support is a smart way to mitigate risks stemming from accidental errors on the side of the user.

[Read More](https://github.com/OffcierCia/DeFi-Developer-Road-Map)

[Read More](https://blog.eduonix.com/cryptocurrency/cryptocurrency-security-checklist-investors-adopt/)


---

#### Problem 25

Be aware of most common attacks. Follow hacker websites, latest security standarts, check out what [Nitrokey](https://www.nitrokey.com/) and [YubiKey](https://www.yubico.com) do and why. As a conclusion - read what is OSINT and counterOSINT so possible criminals wont be able to collect needed data.

[Read More](https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md)

[Read More](https://cryptosec.info/checklist/)

#

**My Articles:**

- [OpSec Going Smart](https://officercia.mirror.xyz/fsRT9NC29GzeQAl-zvAMJ9L-hYUYvX1CPUkt97Vuuwo)
- [OpSec Going Smarter](https://officercia.mirror.xyz/B9hBom4jGhkV0C-47E4YBz8tBJkb0a7zVwQR0jITIyM)
- [OpSec Going Smarter: Secure Smartphones](https://officercia.mirror.xyz/0tlSSF2LDTOnnMN41R5Uc1kTpo-G-kXljn8pT0a1YLY)
- [Choosing a Reliable VPN Provider for Life & Work](https://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg)
- [Innovative Trio in Smart Contract Security: Monitoring, Prevention, Defense](https://officercia.mirror.xyz/W-SUbkTf18b3RuPL9DykXQmpexWBZxbp4P1xfCfXo4Y)
- [The Only Safe Way to Store Crypto](https://officercia.mirror.xyz/p1ieZdxQWH4yHCNOXNPHyT8So1cY0X_wMGKwdmavi7s)
- [How Cross-Chain Bridges are Hacked?](https://officercia.mirror.xyz/AFkEUuxid1egNm4XdqYEzWEwosPNbz2CNghlNrq7LZQ)
- [What you should do if you think someone has stolen your crypto-assets](https://officercia.mirror.xyz/wSvKI5p91-GYcun1aAyMMjNbpkgKnp7qIxVIqc1sXZk)
- [What to do when your Web3 project Discord server is hacked & how security audit may prevent it from happening](https://officercia.mirror.xyz/x4nGX6YwhhmHj8TaQ53kBR5b5M1Ei_Y9_l1Vpext-Hk)
- [Violent Attack Vectors in Web3: A Detailed Review](https://officercia.mirror.xyz/qfhQ_ocTPKnO5EqMlZ2ixIX7oBIfz5Tznid82EucbYk)
- [What is ARP spoofing and how to protect against it?](https://officercia.mirror.xyz/fYQegsuZkdLPlhW9xopFzwnLmQWjaaWBjnR2qX9UixY)
- [An ultimate list of rules any on-chain survivor should follow to stay safe!](https://officercia.mirror.xyz/_nD1Rtxe1PplK-NQzIq9sl-KNtajQG0aKqYsV36RTjA)
- [QR Code: An Underestimated Danger](https://officercia.mirror.xyz/aN6giRkUsNd0o0bmjZVeZb2htkO_Ve16gMsARU6RBfM)
- [The most significant milestones in the development of communications](https://officercia.mirror.xyz/G4782jMUpA_kkIpwakphbd6djX85cxRGS-pjBipc8Yk)
- [Someone overheard me! Why it's important to think about all attack vectors, even if they seem unlikely to happen?](https://officercia.mirror.xyz/Gc4msiSq4HkKrrsKcL5tDF613iUtX4vWUAb5DYdDPC0)
- [Laplace's Demon Speaks: Is there a life in blockchain?](https://officercia.mirror.xyz/OWdu4NkAeygp2dh-AXr82gM_fWD95WuFSP3WzMnpddc)
- [MacOS + IOS + Crypto + OpSec = ?](https://officercia.mirror.xyz/0uiAGM50rkQSvHbptcrVkCkyxsnewpAFIdu3oyga42Y)
- [How to win the war, trick the KGB and protect your crypto-assets from theft by Steganography](https://officercia.mirror.xyz/8ecJG-s_5E6J1t-h8gUNGqV3hbX8If-E5NnrFrOJHUA)
- [Master of OpSec Masters: A View Through the Prism of Time](https://officercia.mirror.xyz/4x2-M4R2cSnID1wpsTO4CQNrMQ5JUFouR-rZ_N4xO-Q)
- [OpSec in Crypto: Thoughts](https://officercia.mirror.xyz/VCUaozkvMw1CSaNm3VnafrDLX4dwEjDIQo6qSOIbO8o)
- [Attacks via a Representative Sample : Myths and Reality](https://officercia.mirror.xyz/WeAilwJ9V4GIVUkYa7WwBwV2II9dYwpdPTp3fNsPFjo)
- [How can you become a one-man-army OSINT specialist?](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Key principles of storing cryptocurrency securely](https://officercia.mirror.xyz/GtKNkmRDR_hhCqrnSENjqfPDHHb0W1M2SVeXDp4swCQ)

**Also check out:**

- [Anon Guide](hackmd.io/YKjhguQES_KeKYs-v1YC1w?both)
- [anonymousplanet.org](https://anonymousplanet.org)
- [My Works](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [How to use an ipad as a secure calling and messaging device](https://yawnbox.com/blog/how-to-use-an-ipad-as-a-secure-calling-and-messaging-device)
- [Stylometric fingerprinting redux](https://seirdy.one/posts/2022/07/09/stylometric-fingerprinting-redux)
- [privacyguides.org](https://privacyguides.org)
- [OpSec](www.usenix.org/system/files/1401_08-12_mickens.pdf)
- [DeepWeb OpSec](https://telegra.ph/Deepweb-OpSec-Link-08-20)
- [privacytools.io](https://www.privacytools.io/)
- [Start.me RabbitHole](https://cia.start.me/p/dlaxD0/ciaofficerv2)

#


### Table of contents

| Watch                                        |
|----------------------------------------------|
| https://www.youtube.com/watch?v=hxHqE2W8scQy |
| https://www.youtube.com/watch?v=0aSQMeoz9ow  |
| https://www.youtube.com/watch?v=pGcerfVqYyU  |
| https://www.youtube.com/watch?v=9XaYdCdwiWU  |
| https://www.youtube.com/watch?v=ixLuRvYlrlw  |

| Read                                                                                                                                     |
|------------------------------------------------------------------------------------------------------------------------------------------|
| https://blog.keys.casa/7-ways-to-level-up-your-bitcoin-opsec                                                                             |
| https://medium.com/the-business-of-crypto/fundamentals-of-opsec-in-crypto-7844ba701b1d                                                   |
| https://www.threatstack.com/blog/five-opsec-best-practices-to-live-by                                                                    |
| https://digitalguardian.com/blog/what-operational-security-five-step-process-best-practices-and-more                                     |
| https://www.gocivilairpatrol.com/programs/emergency-services/operations-support/operational-security-opsec                               |
| https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817                                                 |
| https://www.cnbc.com/2017/11/02/heres-how-to-protect-your-bitcoin-and-ethereum-from-hacking.html                                         |
| https://www.cnbc.com/2021/06/11/tips-to-help-keep-your-crypto-wallet-secure.html                                                         |
| https://www.ledger.com/academy/security/hack-wifi                                                                                        |
| https://datatracker.ietf.org/wg/opsec/documents/                                                                                         |
| https://www.lopp.net/bitcoin-information/security.html                                                                                   |
| https://www.reddit.com/r/opsec/                                                                                                          |
| https://hackernoon.com/5-tips-to-prevent-hackers-from-stealing-your-crypto-assets-e2243zig                                               |
| https://arxiv.org/abs/2106.10740                                                                                                         |
| https://web.mit.edu/smadnick/www/wp/2019-05.pdf                                                                                          |
| https://airgapcomputer.com                                                                                                               |
| https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817                                                 |
| https://assets.website-files.com/5ffef4c69be53b44bd10b438/6012f54022181b0d0a3a948c_CryptoCurrency%20Security%20Standards%20Checklist.pdf |
| https://blog.eduonix.com/cryptocurrency/cryptocurrency-security-checklist-investors-adopt/                                               |
| https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md                                                                  |
| https://cryptosec.info/checklist/                                                                                                        |

#

## Support Me:

Support is **very** important to me, with it I can do what I love - educating DeFi & Crypto users :sparkling_heart:  First, a few words, dear friends... I want to thank everyone who sent me donations! Much much thanks to you, I was able to bear the loss of my last job, found new meaning of life, and finally started writing a lot!

The best thing is to support me directly by donating to my address on Ethereum Main-net or any of the compatible networks or to any address from the list below:

[![Supported by GitCoin](https://img.shields.io/badge/Support%20via-GitCoin-yellowgreen)](https://gitcoin.co/grants/3150/defi-developer-roadmap)


If you want to support my work, you can also send me a donation to the address:

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

- **4AhpUrDtfVSWZMJcRMJkZoPwDSdVG6puYBE3ajQABQo6T533cVvx5vJRc5fX7sktJe67mXu1CcDmr7orn1CrGrqsT3ptfds** - Monero XMR 

- **BLyXANAw7ciS2Abd8SsN1Rc8J4QZZiJdBzkoyqEuvPAB** - Solana

- **t1Tixh34p5FK9pMV4VYKzggP6qPbUwUabxx** - ZenCash ZEC 

- **DQhux6WzyWb9MWWNTXKbHKAxBnAwDWa3iD** - Doge 

- **TYWJoRenGB9JFD2QsdPSdrJtaT6CDoFQBN** - USDT TRX

- **LebuhjAPJLnLULAKsMgQEZC5E5q9TdvurJ** - LiteCoin

- You can also support me by minting one of my [Mirror articles NFTs](https://officercia.mirror.xyz/)!

#

User donations have been and still are my main source of income. It helps to avoid affiliations and engagements. I really care about what I do and I'm glad you like it! You can also buy the works of my good friend and artist - all proceeds will go to create a book about blockchain with a unique design:

- [opensea.io/collection/regullion-collection](https://opensea.io/collection/regullion-collection)

I hope my tips have helped you make and save a lot of money! In our world of ruling Entropy, information means a lot and I give it to you for free. Also I want to remind all my enemies and haters that I'm just a writer and my nickname is just an attempt to make people aware of the safety issue. Call it a swan song or a cry from the heart, but I like what I do.

I would like to let you know that I also do private orders for onchain investigations of hacks and incidents! Most of related cases ended successfully! For a small % of the returned funds or donation I will conduct an investigation for you, advise you on what further steps to take and send you to the right route! 

Thank you very much. I am very happy and excited to help each and every one of you! Thank you so much for your support!


#

- [Check out my Telegram Channel](https://t.me/officer_cia)
- [Follow my Twitter](https://twitter.com/officer_cia)
- [Track all my activities](https://t.me/officer_cia/296)
- [All my Socials](https://t.me/officer_cia/296)

##

(👍 ͡❛ ͜ʖ ͡❛)👍 Thank you! 

