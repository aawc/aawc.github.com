---
permalink: /
title: "$ whoami"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Varun Khaneja. I’m a Software Engineering Manager on [Google Chrome's
Security team](https://chrome.security/). I've also been leading the work on
using [LLMs to protect users](#ai--security).

# My work

Design, implement, and oversee state-of-the-art protections to keep Chrome users
safe from visiting phishing sites, downloading malware, or falling for scams.

# Expertise

Evaluating the security of an event in the web browser often requires taking
into account a number of actions that led up to that event.

One approach of doing that is to evaluate all of those actions and related
signals on the device, but that is susceptible to
["oracle attacks"](https://en.wikipedia.org/wiki/Oracle_attack) because the
attackers can try out their attacks locally and only deploy the successful ones
in a mass market campaign.

Another approach is to collect all relevant and important signals necessary to
evaluate the riskiness of the event on a trusted server, and protect the user
while respecting the users' preferences related to the sharing of that data,
including data minimization, short retention, strong access controls, and 
strictly limited use.

A majority of my work and expertise is in the latter approach of offering the
users the choices to make the tradeoff between security and privacy that suits
their needs the best, and identifying ways to bring more protections to users
within that framework.

# AI + Security

Part of my focus recently has been on identifying ways in which we can protect
users from [cloaking](https://en.wikipedia.org/wiki/Cloaking) i.e. attacks
that attempt to "hide" from Google by serving a benign page to Google's crawlers
and a malicious page to target users.

With the advent of LLMs everywhere, we found ourselves presented with a new
opportunity of being able to "understand" the page content as it is served to
end users, and use that to idenitfy pages that are trying to scam users, while
cloaking from Google. I've been leading a cross-company team to focus on this
effort, starting with the commonly seen
["Technical support scam"](https://en.wikipedia.org/wiki/Technical_support_scam)
with an aim to reduce other kinds of scams too.
