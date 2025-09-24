## Current status: MSc student (degree expected in Nov 2025).

# Interests and areas of work
## Current interests
The chart below shows the areas that I currently have an interest in and work on.
- Those in circles are general directions, while those in rectangles are specific sub-topics.
- Those that I primarily focus on are in red and have double borders, while all the others that I just get in contact with are in dark blue.
- One topic derives (contains) another with an arrow. The arrows in the CS area are in black, whereas those in the Math area are in blue.
- I tried many ways to place the Mathematics subgraph to the right but none worked. Thus, the current lines are a bit messy.

```mermaid
flowchart LR
	%% Primary general topic, general topic, primary subtopic, subtopic,
	%% respectively
	classDef gen-pri	shape:dbl-circ,stroke:#f00
	classDef gen		shape:circle
	classDef sub-pri	shape:subproc,stroke:#f00
	classDef sub		shape:rect

	%% Left side: CS
	subgraph "Computer Science"
		direction LR
		%% General directions
		CY(((Cybersecurity))):::gen-pri
		SE(((Software Engineering))):::gen-pri
		AI((Artificial Intelligence)):::gen

		%% Cybersecurity branches
		CY --> CR[Cryptography]:::sub
		CY --> DR[["Digital rights and privacy"]]:::sub-pri
		CY --> SS[["Secure systems (OS, Distributed)"]]:::sub-pri
		CY --> FV[["Formal verification"]]:::sub-pri
		SE --> SS
		SE --> FV
		SE --> HP["High performance & low-level programming"]:::sub
		AI --> ML["Machine learning"]:::sub -->
		LLM["LLMs"]:::sub
	end

	%% Right side: Math
	subgraph Mathematics
		direction RL
		EN((Elementary number theory)):::gen
		TT(((Type theory and Metamathematics))):::gen-pri
		AL((Analysis & Linear Algebra)):::gen

		EN --> CR
		TT --> FV
		AL --> ML
		AL --> HP
		%% Change link color
		linkStyle 9,10,11,12 stroke:#00f
	end
```

## Previous interests
- Computer graphics
- Video games design, and human-computer interaction

# Reach me
## Email addresses
For now, I usually use guanyuminghe AT proton DOT me as my primary email
address. If you are in the academia, then I might also use one of my
institution email addresses. The current one is guanyuming DOT he 24 AT 
imperial DOT ac DOT uk.

Please note that I have no intention to use any of the email addresses
permanently. The proton one is subject to change, should I find Proton unethical
and untrustworthy in the future (see the suspension of journalists' email
addresses [by Proton](https://web.archive.org/web/20250923025829/https://theintercept.com/2025/09/12/proton-mail-journalist-accounts-suspended/)). 
My institution addresses are inherently temporary unless I obtain a permanent 
position in one someday.

## My PGP key
You may find my OpenPGP public key published
[here](https://github.com/guanyuming-he/Openpgp-key) useful.  I don't know
which email address I will use in the future, but you can always (until 2035,
to be cautious) trust the signatures made by my private key, if you know me and
you are confident that this GitHub account is controlled by myself (of course,
you have to trust your browser and the certificate authorities; be mindful to
detail in security).

## Instant messaging
One significant weakness of using OpenPGP keys to encrypt emails is the lack of
forward secrecy. To avoid having to trust a server, I only plan to use one
Instant Messaging protocol, Tox, for now. My Tox ID:
BF011A0BF6AAB23526445921291C601DAA63D808BC13F8D3EC8164448007AD5276D5589D6A82
(Check the Tox protocol specification to understand it https://toktok.ltd/spec)

On the other hand, email communication encourages one to think about the
message one's drafting before sending it, as there's no way to retract it back. 
Additionally, there's much less of the expectation for instant reply in email
communication. As such, I would select the communication method by use case.


# My repositories here
## Distribution
Most of my personal projects are here. The rest personal projects could be 
belong to my other GitHub accounts, for example, the one I used during my 
MSc, which was created to follow the recommendation of the department.
For your convenience, I have negotiated to publish some of those under 
other accounts of mine here. 

I also made an organization that you can find on my homepage to contain 
some of my group projects during my undergraduate study.

## Don't trust my activity panel
The activity algorithm is biased. First, it won't count commits to 
non-default branches. I could be using many different branches heavily 
sometimes. For instance, in some lab solutions I use a dedicated branch
for one lab by design. Second, repos authored by my other accounts that
I make public here also do not count.
