# License

With regard to the license status of 2.11 [BSD](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution), most seem to arrive at it being covered by a combination of the [Caldera license](Caldera-license.pdf), for any code born from the early Unix versions (v1 - v7) and the [BSD license](https://en.wikipedia.org/wiki/BSD_licenses), for any subsequent BSD code.

In a [post](https://retrocomputing.stackexchange.com/questions/30360/is-2-11bsd-source-code-encumbered) on the Retrocomputing StackExchange board, [Curt Sampson](https://retrocomputing.stackexchange.com/users/7208/cjs) commented:

> Terri Kennedy, who is deeply involved in software preservation for DEC/Digital systems, checked with an unnamed source "who will definitely be 'in the know.'" Here is Kennedy's [follow-up](https://forum.vcfed.org/index.php?threads/pdp-11-os-licensing-physical-machines.1248991/#post-1396403) from the Vintage Computer Foundation discussion forums.
>
> > The correct answer is "he doesn't know". So nobody does.
> >
> > Here's a quick summary. None of this should be construed as his words, just my interpretation of them up until the last paragraph, which is entirely my own musings:
> >
> > 2.8BSD was based on V7 (which is covered under the Caldera Ancient Unix License). But 2.9/10/11 collected bits and pieces of later CSRG releases, which were encumbered until 4.4BSD-Lite, well after 2BSD was no longer adding code from later CSRG releases (programs had gotten so big that they would fail to compile or link on 2BSD without heroic efforts).
> >
> > There are no extant revision control logs for 2BSD - in fact, Warner [Losh<sup>1</sup>] had to work his way back to 2.11 patch 0 by reversing subsequent patches. So there are no import logs, etc. showing what came from where. You'd have to look at source file headers and probably start comparing code to see if it matches CSRG-developed code or encumbered code, a task that will be made substantially harder because the backporting of 4BSD code to 2BSD involved rewriting it for the very different C compiler in 2BSD.
> > 
> > Given that 2BSD will never be used as a starting point for a port to a modern platform (unlike 4BSD, which is what got USL so riled up) and with large parts written in a dialect of C no modern compiler will accept, it is hard to see who would be harmed (one prong of a legal case). Further, it's not obvious what corporate entity has standing to sue (another prong of the case). To answer a question posed by someone else, a perpetual software license issued by a defunct entity is still valid, subject to any restrictions placed on the licensee at the time of licensing. In other words, another company can't come along and say "your license is no longer valid because we bought the rights to the software".
> 
> (It's sounding as if this may be as good as we ever get on information about this.)
> 
> <sup>1</sup> [Warner Losh](https://archive.fosdem.org/2020/interviews/warner-losh/) is fairly well known for doing research into early versions of Unix.

