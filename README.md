## Current status: MSc student.

## My PGP key
You may find my OpenPGP public key published [here](https://github.com/guanyuming-he/Openpgp-key) useful. 
I don't know which email address I will use in the future, but you can always (in the next 10 years, to be cautious) trust the signatures made by my private key,
if you know me and you are confident that this GitHub account is controlled by myself (of course, you have to trust your browser and the certificate authorities; be mindful to detail in security).

## Current Interests
```mermaid
graph LR
  %% Core areas
  CS[Cybersecurity]
  SE[Software Engineering]
  AI[Artificial Intelligence]

  %% Cybersecurity branches
  CS --> CR[Cryptography]
  CR --> NT["Number Theory & Probability"]
  CS --> SD["Secure System Design: OS + Distributed"]
  CS --> FV["Formal Verification"]

  %% Software engineering connections
  SD <--> SE
  SE --> FV

  %% Formal verification branch
  FV --> TT["Type Theory & Metamathematics"]

  %% AI branch
  AI --> ML["Machine Learning"]
  ML --> APP["Applications to Security, SE, Verification"]

  %% Applications loop back
  APP --> CS
  APP --> SE
  APP --> FV
```

## Previous Interests
- Computer graphics
- Video games design, and human-computer interaction

## Don't trust GitHub activity panel
The activity algorithm is biased. First, it won't count commits to non-default branches. 
Second, private repos from my university GitHub account that I make public here also do not count, 
because the author is that account of mine.
