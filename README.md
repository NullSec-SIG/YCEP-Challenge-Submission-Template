# YCEP 2024 Challenge Submission Template

## Table of Contents
- [Flag Format](#flag-format)
- [Template](#template)
- [Samples](#samples)
- [Submission Guide](#submission-guide)
- [FAQ](#faq)

## Flag Format
The flag format for YCEP 2024 is `YCEP24{...}` (RegEx: `YCEP24\{[a-zA-Z0-9_]+\}`)

## Template
```
challenge_name/
    |
    ├─ dist/
    │       ├─ challenge_file(s)
    |
    ├─ service/
    │       ├─ container-name/
    │           ├─ Dockerfile
    │           ├─ files_to_host_challenge
    |
    ├─ solution/
    │       ├─ writeup.md
    │       ├─ solution_file(s)
    |
    ├─ chall.yaml
    ├─ README.md
```

## Samples

This repository contains two sample challenges from LagNCrash 2024, `Mockingjay Embeds` (static) and `Orwells Firewall` (requires service). You can refer to them to understand how to structure your challenge. 

In the same directory, there is a template which you can use to create your challenge.

Note: The difficulty level for the challenges in the sample should not be the gauge for the difficulty level of this YCEP CTF!

## Submission Guide

1. Fork the [challenge repository](https://github.com/NullSec-SIG/YCEP2024-Challenge-Repo) to your account. (Note: Contact Kairos for access if you do not have access)
2. Work on the challenge in your forked repository.
3. Create a pull request to the main repository once you are done with the challenge.
4. Wait for review!

## FAQ
- **Q**: If I am creating a static challenge, do I need to create a Dockerfile?  
  **A**: No, you do not need to create a Dockerfile for static challenges. You can directly dump the files in the `dist/` directory.