---
title: rockyou2021.txt - A Compilation of 8.4 billion passwords being leaked on the dark web !
layout: post
category: Linux Security, Hacked 8.4 billion passwords.
date: 13th Sept. 2021 - 12:21 pm IST
---

## Is rockyou2021.txt useful?
Maybe.

It’s definitely not useful as a “password list” or “breached password list,” and it’d be a mistake to think of it as one, despite many news sites suggesting that it’s the largest password breach ever. Troy Hunt tweeted about rockyou2021.txt about as quickly as it was released, and said the following:

Unlike the original 2009 RockYou data breach and consequent word list, these are not “pwned passwords”; it’s not a list of real world passwords compromised in data breaches, it’s just a list of words and the vast majority have never been passwords. Just do the maths: about 4.7B people use the internet. They reuse passwords like crazy not just across the services each individual uses, but different people use the same passwords. Then, only a small portion of all the services out there have been breached. … This list is about 14 times larger than what’s in Pwned Passwords because the vast, vast majority of it isn’t passwords. Word lists used for cracking passwords, sure, but not real world passwords so they won’t be going into Have I Been Pwned.

Despite not being a password list, could it be useful when cracking passwords? I’d wager “in certain situations.” kys234 (the author of the list) made a couple tradeoffs to put this into one mega list, and these might be bad for the utility of the list:

ASCII-only: kys234 explicitly removed any non-ASCII characters, and limited password length to 20 characters. This makes for a very clean list, in stark contrast to other password breaches or dictionaries which are often very messy or unformatted, and can take time to clean before being usable. However, this also makes the list substantially less useful for international targets - any non-English speaker may prefer to use Unicode characters, and those passwords or dictionary items have been removed.
Massive combo list: kys234 also elected to make this a single file instead of multiple files sorted by type. Many of the lists that kys234 pulled from are explicitly separated into their sources - dictionaries such as those derived from Wikipedia and Project Gutenberg are kept separate from breached passwords. This is because password crackers may want to use them separately or applying different permutations to them. For example, checking known passwords first, or only applying permutations to English-language words when attacking an English-language target.
So while it might be a list worth keeping in a password cracker’s arsenal, it’s not suddenly going to become their default. But if you do want it in your arsenal, or just want to have a look for yourself …

## Download
Thanks to a Redditor who wishes to remain anonymous, I have obtained a copy of rockyou2021.txt and have prepared it for redistribution via torrent. The torrent contains rockyou.txt, 7z compressed into a split archive, for a total compressed size of ~12.8 GB. The uncompressed size of rockyou2021.txt is a whopping ~92 GB, so be sure you have enough space. The torrent is currently being seeded at 20 Gbps, but please help maintain a healthy seed swarm.

A torrent file is available here(https://chris.partridge.tech/2021/rockyou2021.txt-a-short-summary/rockyou2021.torrent), or you can use this magnet link(magnet:?xt=urn:btih:JEQMEEFTBXT35RJ3GUTGXU7HP3HBU5P6&dn=rockyou2021.txt%20dictionary%20from%20kys234%20on%20RaidForums&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce).

After downloading, you can uncompress these with the command 7z x rockyou2021.txt.7z.001, or on Windows simply right-click the first file (rockyou2021.txt.7z.001) and hit “Extract” - 7zip will be aware of the other split file and will extract the entire wordlist without problem.

## TL;DR
rockyou2021.txt is not: a breach, a list of breached passwords, anything substantively new, or a sufficient reason to change your passwords (on its own).

rockyou2021.txt is: a wordlist which includes mostly English-language words, possible passwords, and known breached passwords. All of which was known & publicly available prior to this point.

You should: take this time to identify news sources which used fearmongering to draw readers in on this subject in instead of facts, and unfavorite/unsubscribe from/block those sources.
