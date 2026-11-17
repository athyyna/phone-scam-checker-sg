# Phone Scam Checker — Singapore

A light, mobile-first scam check for unknown phone numbers and WhatsApp messages.

Paste a number to see what country it is from and whether it carries common scam warning signs, with Singapore rules built in — +65 3 is VoIP, 8/9 is mobile, +422 is unassigned, +1 Caribbean codes are a common Wangiri trap, and 1900 is premium-rate.

## What it does

- Number checker: country and Singapore range, with a caution level — not a safe/unsafe verdict, because caller ID can be spoofed.
- Big links to ScamShield and tap-to-call 1799, the ScamShield helpline (24/7 in Singapore).
- A 5-step routine: Stop, Look, Listen, Verify, Block.
- A compact Singapore number guide.

Everything runs in the browser. Nothing you type leaves your phone.

## What it does not do

It does not intercept live calls, and it does not read WhatsApp. No app can do that reliably on iPhone, and WhatsApp messages are end-to-end encrypted. For a live check, use the ScamShield app — it can check numbers, messages, links and screenshots — and call 1799 if you are unsure.

## Use it

Open the site, paste the number, read the result, and if anything asks for an OTP, Singpass, password, or a money transfer, stop and verify through a different channel.

## Publish it

This is a static site — one HTML file, no server needed.

To serve it from GitHub Pages: Settings > Pages, Deploy from a branch, main, / root. The site will then be at https://athyyna.github.io/phone-scam-checker-sg/

## Sources

- ScamShield: https://www.scamshield.gov.sg/
- ScamShield helpline: 1799
- Country codes: Google libphonenumber
