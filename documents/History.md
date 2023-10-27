# History

## 🖹 | History

With such a great engine at our disposal, you may have wondered how I created it?

It starts a whole year (or more) ago, where I simply wanted to create an engine from scratch.  
It was called **Round Engine** and it was pretty feature heavy, but eventually the project got canned.

The issue was with the same issues as most other engines have. The project was too complicated...  
and it didn't perform as well as I would have hoped. Round Engine was unfortunately bogged down by -  
compatibility, features no one could use, and bad code. As such I privated the repo.

Cut to: Early 2023, where I was thinking about optimization and was rather frustrated since no other engine -  
quite fit what I needed. Each one had it's quirks that made it unsuitable for something I could build mods on.  
So I created assorion. An engine where no expenses were spared. It's not very compatible with the base game at all,  
and things are handled far differently than the base game's however that was certainly for the better.

Assorion was originally called **MKG Engine**, but once my friend (*Byzol* / *Barzil*) proposed the name "Assorion",  
we just had to roll with the name.

## ⓘ | What Does Assorion Do differently?

<span style="font-size: 8pt">PS: This will be expanded on in it's own MD file.</span>

We're gonna skip code changes and focus more on the *philosophy* of Assorion.

> <span style="color:gold;font-weight:bold">WARNING!</span>  
> Highly opinionated stuff ahead.  
> Also rather mean stuff as-well, sorry to any one offended by this.

The reason why we call Assorion "The Linux of FNF engines", is because of the way I like to handle it.  
Assorion is not meant to be the most feature-rich engine, it's not even really suposed to be the easiest to work on.  
The goal of Assorion is to have an engine, that is tiny at it's core, a tiny engine where features can be added on later.

The issue I have with most engines is how they often include things that I consider "bloat" -  
(i.e: DiscordRPC, Cutscenes, Lua, Options that people don't need), and I didn't want something like that.  
I wanted an engine where those things could be added, but aren't in the base version.

Because...

### I don't want to water down any mods built on this engine, just because some people might use a feature!

That's basically how I'd rather do things.

Almost everything in Assorion is meant to be things that every engine should have, and features that other -  
people can use, it's not meant to be about having **ALL** of the features.

But as for the code side of things?

I try to keep it as simple as humanly possible. I try to re-use functions when I can.  
I try to use return, break, continue where-ever I can.  
And I try to consider the low-level cost of the features I implement.

It's not about sheer performance, it's about code consistency. Assorion should be easier to work with because of this.

> <span style="color:#D000FF;font-weight:bold">NOTE!</span>  
> Although Assorion's logic is essentially perfected, it might not perform ***THAT GREAT***...  
> Sadly, the engine is still bogged down by Flixel's rendering which is slow and ineffecient.  
> You will probably only notice a big difference on integrated graphics (or something), or -  
> on really bad CPUs.  
>
> Just letting you know.

Lastly, Assorion is basically opinion driven.  
You don't have to agree with me or use this engine, so don't feel too upset if you don't care enough about this.  
I just want an engine that works for me, and is small at it's core. If you don't care, or if you want to just have -  
a feature rich engine, then Psych Engine isn't a bad choice.