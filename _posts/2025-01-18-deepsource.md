---
layout: post
title:  DeepSource to the Rescue! (And How to Fix That Pesky Permissions Error)
date:   2025-01-18 22:03:00 -0500
categories: ansible automation tools
---
So, I was trying to set up this a linter + PR flow for my homelab Ansible repo, and BAM! I hit this error:
``` [remote rejected] lint-fixes -> lint-fixes (refusing to allow a GitHub App to create or update workflow .github/workflows/badge.yml without workflows permission)```
I was wrestling with this error to try to get any linter to generate auto-PRs (specifically prettier) when I came across deepmind. I took a look and it seems like it was made for exactly this - lint, scan, access and offer up a PR!
Easy peasy, right?
## DeepSource: My Ansible's New Best Friend
Now that DeepSource has the right permissions, let me tell you why I'm loving this tool. It's like having a super-powered linter that dives deep into my Ansible code, finding not just syntax errors but also potential security issues and those annoying inconsistencies that drive me crazy.
But the best part? **Autofix!** DeepSource actually fixes many of the problems it finds and creates a pull request with the changes. No more wasting time on minor fixes – DeepSource takes care of it.  
## DeepSource in My Homelab
I've been using DeepSource to scan my Ansible roles, and it's been a game-changer. It recently found a security vulnerability in one of my roles that I had completely missed.  It also helps me keep my YAML files clean and consistent, which is a big deal for me.
## Ready to give DeepSource a try?
Head over to [DeepSource](https://deepsource.io/) and create a free account. You won't regret it!
**P.S.** If you're having any trouble setting up DeepSource, check out their documentation for more help.