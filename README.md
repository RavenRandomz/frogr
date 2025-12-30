# Frogr
Free and Open Source Music Protection Program.

# Build Environment
This is designed for using raw command line: neovim, cmake, ninja, and rust stuff. Refer to the build
environment scripts for the C++ and rust portions.

# Devel

## Github
This is a mirror
## Gitlab
This is a mirror
## Codeberg
This is the central operations location
## Developer mailing list & IRC [WIP]
Core developers will use git mail and irc. Although it is old school, it is a rapid system that can work
without internet and forces a reviewer to read the email before applying code to their machine. This is
largely more distraction free. It also keeps the project's infrastructure from being tied to a large corporation.

For bug reports, we will use gitlab issues.

# Why two implementation and two languages?
This project is both an educational one and a community one. I am curious on the practical pros/cons of Rust vs C++.
The "competition" bewtween both sections might help both projects improve. For the community at large, this would give
greater insight on the appropriate use case from one language to another. C++ has a much more mature ecosystem albeit dependency
hell. Rust has a borrow checker which can force large-scale refactoring at the worst of times. Dependencies can be insecure in the sense
that one dependencies can include tons of other ones.


I did consider adding an experimental python section. It seems that the pros that pythong ives is that its massively out of the box,
cross-platform. Over java, it's double-edged sword of loose typing.

Given how daunting this project is, I do want to see which language suits its case. And this experiment will help both the C++
and Rust communities understand what tools suit the job better.
Perhaps is one is much more suted to the task, I will



# Dependencies
NO ABANDONWARE PERIOD. (This rule is recursively applied). If something is abandonware but looks promisnig, it must be forked
or directly included WITH CITATION and COMPLIANCE WITH LICENSING.

while anticipating the 

# Coding style

## General Style
Allman brackets :)

On a practical level, I know people with dyslexia who prefers the uniform look. We are in the era of 4k monitors.

At the end of the day, if it is user friendly for people with disabilities,
then it tends to help non-disabled people as well.

## CPP
This uses a modified form of the google coding style
# Rust
Brackets lol

# Licensing
The AGPLv3 LIcensing has been chosen mainly for the reason that a company cannot take Frogr. I will be adding a FANG_GPL_MANIFESTO.txt
detailing embrace, extend, extinguish, the enshittification of Android, how Netbsd license was usted to create a **closed source** "Wear OS"
and more. How Google made itsef the only signer of android apps, and went full private on android development (still providing the source code
but removing the broader community from participating in the project).

It is not right to take community code, benefit from it financially, and then give nothing back - even making a locked up version of it. Given
how trigger happy AI companies are, the patent provision pervents retroactively locking away open source code or preventing this code to be used
in use cases that rely upon it. Sounds stupid but it's the legal word and GNU predicted these sort of shenanigans.

# Frogr name origin
Because of the Amazon Poison Dart Frog. Frogs are known to be psychadelic and creative too.
I chose poison over venom because the point of this is not to attack AI, rather, it is to prevent getting
eaten up by AI. Although AI can be a tool, it can be misused. Imagine if a friend took all of your text messages, fed them to an LLM, and talked
to that instead of you. I even ended up charging people for talking to this FriendBot? Yeah, when we mechanize the more "human" aspects we lose faith in humanity.
Perhaps we have lost faith in our ability to entertain ourselves, but when humanity loses faith in itself, it's a darker world: https://www.youtube.com/watch?v=ngZ0K3lWKRc

Art is not just a commodity. if you want commodities, go ahead, but if you want to express and grow and share your fundamental being, then art can never
be purely a commodity.

I used to be a proponent of the MIT license - in high school; however, as I have talked wth the Godot devs, you need a really large project with large backing to
prevent corporate aggression. I love Linus, but as recently I found out the phone I paid off has a hardware locked bootloader despite using android - GPLv2 code,
GNU was right about Tivoitization.

# Content Policy
In the Linux Kernel tradition, cursing is allowed... except for slurs. You can get pretty creative. Classes and documention
should still be sanely named however!

Mee krob is only allowed once every 10000 lines. God hates it as much as Cartman does.

# Template origin
This uses: https://github.com/RavenRandomz/raves-default-cpp23-project/tree/main/src

It was not forked .
