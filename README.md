## Thaliance: Most. Scalable. Cryptocurrency. Ever.

_“Don't try to invent the future. Just get to work making real solutions to real problems. The future will invent itself.”_ – Pieter Hintjens.

### What's different about Thaliance?
A collective work has two extreme outcomes. Either it's a failure, in which case every sane person walks away without a fight. Or, it's a success, in which case we see jockeying for power, control, and money. Left unchecked, this can destroy a community and an open source project, turning it into a toxic and unfriendly place. 

It doesn’t have to be this way. In fact, there’s a realiable and tested method proving that this is the case. Using this method also means the entire project becomes a hill-climbing algorithm, relentessly solving any problem it encounters cheaply and accurately. Development, and the resulting product, are infinitely scalable.

Thaliance is a _living system_, as opposed to a _centrally planned_ system. No central planning means no central leadership or control of the _development_ process – keen observers will note that Thaliance is an entirely unique cryptocurrency in this regard, in stark contrast to every other open source cryptocurrency (or cryptocontract) project that currently exists. But how can this possibly work without leadership? Who will make the decisions? How will people know what to do? The answer is: the [C4.1.](http://rfc.zeromq.org/spec:22/), and a more detailed explanation is [here](https://hintjens.gitbooks.io/social-architecture/content/chapter4.html). 

The C4.1 is a protocol for contributing to open source projects. It was originally created for the ZeroMQ project and has been refined over the past decade. It has been demonstrated [over and over again](https://hintjens.gitbooks.io/social-architecture/content/chapter3.html) to allow communities to work together at scale without the need for central planning. Under the C4.1, the _same_ rules apply _equally_ to _everyone_, without distinction, from the founder to the newest contributor, no one is above the law. You can read more about the C4.1 and its history [here](http://zguide.zeromq.org/page:all#Chapter-The-ZeroMQ-Community), but here’s a brief and incomplete summary of what it means for developers:

-	There is no scope for personal or value judgments over your pull requests. If your pull request follows the C4.1 protocol, it will be merged.
-	Trolls and bad actors expose themselves, there’s nowhere to hide.
-	You own the copyright to your contributions, not the project founder (or whoever comes later to pretend to be the project founder).
-	Your code can never be locked up under a corporate license and used against you in competition to your own work.

### Contributing
1. Fork the repository
2. Produce a minimal and accurate answer to exactly one identified and agreed problem. 
    * Check the [issue tracker] for a problem someone else has found, or [submit your own issue]. 
    * A problem can be a bug, or it can be something you need that doesn’t exist, or something that exists but you want it to be better. A feature that people want but doesn’t yet exist is a problem, as is a bug.
    * Avoid solving something you think is a problem without first posting the problem to the [issue tracker] to seek the advice of others who may know something you are unaware of.
    * Try as hard as you can to ensure your code adheres to the [style guidelines]. Everyone makes mistakes, but submitting pull requests with messy styling is considered rude.
    * If you are working on API changes, make sure your work adheres to the [Evolution of Public Contracts] guidelines.
    * Do not include nontrivial code from other projects unless you are the original author of that code.
    * Make sure your code builds cleanly and without issues, at least on your own system.
3.	Submit a pull request.
    * Your pull request must contain a short (<50 chars) description of the problem being solved (“Problem: …), followed by a blank line and then the proposed solution (Solution: …).
    * If you are submitting a pull request in response to your own or someone else’s problem in the issue tracker, put the issue tracking reference number at the end of the message. Github will then automatically link your pull request to the issue.

### License
Thaliance is released under the [MPLv2 license](https://www.mozilla.org/en-US/MPL/2.0/). This ensures that contributions cannot be closed up under a corporate license. Furthermore, as it is a share-alike license, any forks of this project or anywhere this code is used must also be released under the same (or very similar) license, which means any improvements made by anyone outside of this project can be merged back into Thaliance. This project or the code therein may not be forked or used under a BSD style license (MIT etc) as these licenses allow code to be used in closed-source applications which are not remixable. 
