[![ReadMe Twitter_Post Jonathan_Leitschuh DevStory](https://user-images.githubusercontent.com/1323708/182200035-c5885761-4760-4dc2-8644-508683eea53b.jpg)](https://github.com/readme/stories/jonathan-leitschuh)

Hi There!

My name is Jonathan Leitschuh and I'm a Senior Software Security Researcher. I'm a [GitHub Star](https://stars.github.com/profiles/jlleitschuh/), former GitHub Security Ambassador, & was the inagural [Dan Kaminsky Fellow](https://www.darkreading.com/edge-articles/spotlight-on-first-dan-kaminsky-fellow-jonathan-leitschuh) @ [HUMAN Security](https://www.humansecurity.com/learn/blog/our-first-dan-kaminsky-fellow). I previously worked for the Open Source Security Foundation (OpenSSF) [Project Alpha Omega](https://openssf.org/community/alpha-omega/) focused on finding and reporting OSS vulnerabilities. As a public speaker, I've spoken at conferences like ShmooCon, BSidses CT, BSides LV, Black Hat, & DEFCON. I'm fortunate to have been featured by [GitHub's README project](https://github.com/readme/stories/jonathan-leitschuh)!

If you'd like to get in touch, the best way is to DM me on X [@JLLeitschuh](https://twitter.com/jlleitschuh) or direct message me in the [Open Source Security Foundation](https://openssf.org/getinvolved/) Slack Channel.

---
<p align="center">
  <img src="https://github.com/JLLeitschuh/JLLeitschuh/raw/main/GitHub_README_Animation.gif" alt="Hi, I'm Jonathan Leitschuh">
</p>

---

<!--
How to make your own version of this GIF?
It was made with: https://codesandbox.io/s/github-profile-forked-xo3b7m
Then i recorded my screen with this browser app: https://gifcap.dev/
-->

## Public Vulnerability Research

Note: Any recording with a ⭐ next to it is what I believe to be the best version of any given talk or story.

### Scaling the Security Researcher to Eliminate OSS Vulnerabilities Once and For All

#### Abstract

Imagine a world where a security researcher becomes aware of a security vulnerability, impacting thousands of Open Source Software (OSS) projects, and is enabled to both identify and fix them all at once. Now imagine a world where a vulnerability is introduced into your production code and a few moments later you receive an automated pull request to fix it. Hundreds of thousands of human hours are invested every year in finding common security vulnerabilities with relatively simple fixes. These vulnerabilities aren't sexy, cool, or new, we've known about them for years, but they're everywhere!

The scale of GitHub and tools like CodeQL (GitHub's code query language) enable one to scan for vulnerabilities across hundreds of thousands of OSS projects, but the challenge is how to scale the triaging, reporting, and fixing. Simply automating the creation of thousands of bug reports by itself isn't useful, and would be even more of a burden on volunteer maintainers of OSS projects. Ideally, the maintainers would be provided with not only information about the vulnerability, but also a fix in the form of an easily actionable pull request.

When facing a problem of this scale, what is the most efficient way to leverage researcher knowledge to fix the most vulnerabilities across OSS? This talk will cover a highly scalable solution - automated bulk pull request generation. We'll discuss the practical applications of this technique on real world OSS projects. We'll also cover technologies like CodeQL and OpenRewrite (a style-preserving refactoring tool created at Netflix and now developed by Moderne). Let's not just talk about vulnerabilities, let's actually fix them at scale.

This work is sponsored by the new Dan Kaminsky Fellowship; a fellowship created to celebrate Dan's memory and legacy by funding open-source work that makes the world a better (and more secure) place.

#### Recordings

- BSides LV - August 2022 - [BG - Scaling the Security Researcher to Eliminate OSS Vulnerabilities Once and For All](https://youtu.be/VMGeZd66qnE) 
- Black Hat - August 2022 - [Scaling the Security Researcher to Eliminate OSS Vulnerabilities Once and For All ](https://youtu.be/zTtbVxGEq8A)
- DEF CON - August 2022 - [DEF CON 30 - Jonathan Leitschuh - Scaling the Security Researcher to Eliminate OSS Vulnerabilities](https://youtu.be/UgGhEfdUSvQ)
- SEC-T Stockholm - September 2022  - [SEC-T 0x0E: Jonathan Leitschuh - Scaling the Security Researcher to Eliminate OSS Vulnerabilities](https://youtu.be/WkdzWiNKzt8) 
- ⭐ No Hat - Bergamo Italy - October 2022 - [No Hat 2022 - Jonathan Leitschuh - Scaling the Security Researcher to Eliminate OSS Vulnerabilities](https://youtu.be/W_7ZmKMFvXo) ⭐
- Code Blue, Tokyo Japan - October 2022
- GitHub Universe - November 2022 - [Scaling the security researcher to eliminate OSS vulnerabilities once and for all  - Universe 2022](https://youtu.be/zj-25JfGkYY)

#### News Coverage
 - [Spotlight on First Dan Kaminsky Fellow: Jonathan Leitschuh](https://www.darkreading.com/cyber-risk/spotlight-on-first-dan-kaminsky-fellow-jonathan-leitschuh)
 - [Patching common vulnerabilities at scale: project promises bulk pull requests](https://portswigger.net/daily-swig/patching-common-vulnerabilities-at-scale-project-promises-bulk-pull-requests)

### Zoom 0-Day: How not to handle a Security Vulnerability Report

#### Abstract

Come hear the hilarious story of Zoom’s biggest security scandal, a bombshell 0-Day vulnerability, from the one who dropped it.

On July 8th, 2019, a 0-Day vulnerability was dropped on Zoom that disclosed how anyone could join a victim’s Mac to a video call simply by visiting a malicious website. As if that wasn’t enough, Zoom left behind a hidden daemon that would re-install the Zoom client after it had been uninstalled. The icing on the cake? A full blown RCE vulnerability.

From Zoom’s original claims that it was “not a vulnerability”, what happened behind the scenes, to their eventual fix, join to hear what we as security professionals can learn from this debacle. The press might have covered the disclosure, but the post-disclosure story is even more astonishing than anyone would ever expect.

#### Animations

 - ⭐ ZeroToOne: [~4 Million Computers Compromised: Zoom's Biggest Security Scandal Explained](https://www.youtube.com/watch?v=K7hIrw1BUck) ⭐

#### Recordings

 - BSides CT - November 2019 - [Zoom 0-Day: How not to handle a vuln report - Jonathan Leitschuh - BSides CT 2019](https://www.youtube.com/watch?v=ypU5IPJKlXg)
 - ShmooCon - February 2020 - [Zoom 0-Day: How Not to Handle a Vulnerability Report - Jonathan Leitschuh (Shmoocon 2020)](https://youtu.be/FismZ6ZDKXU)
 - Mac Admins - July 25, 2019 - [Episode 130: Zoom’s Bad Day with Jonathan Leitschuh](https://podcast.macadmins.org/2019/07/25/episode-130-zooms-bad-day-with-jonathan-leitschuh/)

#### News Coverage

This kinda got out of hand. 😆

 - [Time: A Flaw in Teleconferencing App Zoom Could Have Let Hackers Access Your Webcam. Here’s How to Fix it](https://time.com/5622782/zoom-security-flaw-hackers-webcam-fix/)
 - [The Verge: Serious Zoom security flaw could let websites hijack Mac cameras](https://www.theverge.com/2019/7/8/20687014/zoom-security-flaw-video-conference-websites-hijack-mac-cameras)
 - [USA Today: Zoom flaw could leave Mac cameras vulnerable, says researcher](https://www.usatoday.com/story/tech/2019/07/09/zoom-camera-flaw-could-leave-macs-vulnerable/1683413001/)
 - [Forbes: Confirmed: Zoom Security Flaw Exposes Webcam Hijack Risk, Change Settings Now](https://www.forbes.com/sites/zakdoffman/2019/07/09/warning-as-millions-of-zoom-users-risk-webcam-hijack-change-your-settings-now/?sh=175a4ec642d9)
 - [Google News: Ect...](https://www.google.com/search?q=%22jonathan+leitschuh%22+zoom)

## Other Stuff
 
 - The Developers' Bakery - [#35 - ktlint-gradle with Jonathan Leitschuh and Yahor Berdnikau](https://thebakery.dev/35/)
 - Hacker History - [The history of Jonathan Leitschuh](https://hackerhistory.com/podcast/the-history-of-jonathan-leitschuh/)
