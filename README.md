## Current status: MSc student (degree expected in Nov 2025).

# Interests and areas of work
## Current
```mermaid
flowchart
subgraph "Current Interests"
	direction TD
	%% Primary general topic, general topic, primary subtopic, subtopic,
	%% respectively
	classDef gen-pri	shape:dbl-circ,stroke:#f00
	classDef gen		shape:circle
	classDef sub-pri	shape:subproc,stroke:#f00
	classDef sub		shape:rect

	%% Left side: CS
	subgraph "Computer Science"
		direction TD
		%% General directions
		CY((Cybersecurity)):::gen-pri
		SE((Software\n Engineering)):::gen-pri
		AI(Artificial\n Intelligence):::gen

		%% Cybersecurity branches
		CY --> CR[Cryptography]:::sub
		CY --> DR[["Digital rights\n and privacy"]]:::sub-pri
		CY --> SS[["Secure systems\n (OS, Distributed)"]]:::sub-pri
		CY --> FV[["Formal \nverification"]]:::sub-pri
		SE --> SS
		SE --> FV
		SE --> HP["High performance \n low-level programming"]:::sub
		AI --> ML["Machine learning"]:::sub -->
		LLM["LLMs"]:::sub

		SS -.- HP
		ML -.- HP
		SS -.- FV
		%% Change link color
		linkStyle 9,10,11 stroke:#0f0 
	end

	%% Right side: Math
	subgraph Mathematics
		direction BT
		EN(Elementary \nnumber theory):::gen
		TT((Type theory and\n Metamathematics)):::gen-pri
		AL(Analysis & \nLinear Algebra):::gen

		EN --> CR
		TT --> FV
		AL --> ML
		AL --> HP
	end
```

## Previous
- Computer graphics
- Video games design, and human-computer interaction

# Reach me
## Email addresses
For now, I usually use guanyuminghe AT proton DOT me as my primary email
address. If you are in the academia, then I might also use one of my
institution email addresses.

Please note that I have no intention to use any of the email addresses
permanently. The proton one is subject to change should I find Proton unethical
and untrustworthy in the future (see the suspesion of journalists' email
addresses by Proton, as of Sept 2025). The institution addresses are
inherently temporary unless I obtain a permanent position in one someday.

## My PGP key
You may find my OpenPGP public key published
[here](https://github.com/guanyuming-he/Openpgp-key) useful.  I don't know
which email address I will use in the future, but you can always (until 2035,
to be cautious) trust the signatures made by my private key, if you know me and
you are confident that this GitHub account is controlled by myself (of course,
you have to trust your browser and the certificate authorities; be mindful to
detail in security).

## Instant Messaging
One significant weakness of using OpenPGP keys to encrypt emails is the lack of
forward secrecy. To avoid having to trust a server, I only plan to use one
Instant Messaging protocol, Tox, for now. My Tox ID:
BF011A0BF6AAB23526445921291C601DAA63D808BC13F8D3EC8164448007AD5276D5589D6A82
(Check the Tox protocol specification to understand it https://toktok.ltd/spec)

On the other hand, email communication encourages one to think about the
message one's drafting before sending it, as there's no way to retract it back. 


## Don't trust GitHub activity panel
The activity algorithm is biased. First, it won't count commits to non-default branches. 
Second, private repos from my university GitHub account that I make public here also do not count, 
because the author is that account of mine.
