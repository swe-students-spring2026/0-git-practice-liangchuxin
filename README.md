# Git Practice

## Article

[Everyone's Installing Moltbot (Clawdbot). Here's Why I'm Not Running It in Production (Yet).](https://alirezarezvani.medium.com/everyones-installing-moltbot-clawdbot-here-s-why-i-m-not-running-it-in-production-yet-04f9ec596ef5)

by **Reza Rezvani**

## Insights

> There are two ways of constructing software - one way is to make it so simple that there are obviously no deficiencies, the other way is to make it so complicated that there are no obvious deficiencies. — Tony Hoare

This article discusses the pros and cons of Moltbot, a recently launched tool. What I find particularly interesting is that this tool reflects some of the software design principles we've explored in class. Clearly, Moltbot resembles the latter case in Hoare's quote. Built on top of already mature LLM services, it tells an almost perfect story — for just $5 a month, you can have an assistant like Jarvis from the sci-fi movies, one that can almost fully automate tasks for you. Yet behind this sci-fi fantasy lies the reality of exposing your sensitive information to an AI system full of uncertainties, while many of its configurations require no technical expertise to set up. This is a form of hidden complexity: users think they're secure when they're not.

---

## Comment by Karen Maza Delgado

It's really interesting how many developers compromised security for convenience without thinking twice. It goes to show how many of us don't really think about how our data is being used, nor do many of us care. Even using LLMs, it is known that their parent companies collect user data to train models, yet we use it to make things easy. It's a trade-off many individuals are willing to make. Obviously, in professional environments this should not be the case, but I can see why one might ignore the red flags just to simplify their workflow.
## Comments by Hollan Yuan
> I really appreciate how this cuts through the Moltbot hype. It’s a classic case of what happens when UX outpaces basic security—Celia’s point about Hoare’s quote is spot on. It’s honestly wild how many people are essentially "naked" on the public web just for the sake of a cool Telegram assistant. As someone deep in CS, it’s a huge wake-up call that "easy deployment" is often just a fancy word for a security footgun. If you don't grasp the networking layer, you're not self-hosting; you're just inviting the internet into your terminal.
