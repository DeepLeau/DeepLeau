<div align="center">
  <img width="702" height="396" alt="header_github" src="https://github.com/user-attachments/assets/3d5b1193-11ec-47ec-adee-17d08c4a1bc3" />
</div>

![](https://komarev.com/ghpvc/?username=DeepLeau)

<h2>From the electron to the idea</h2>
<sub><i>or: why I never really stopped taking things apart</i></sub>

<br>

What fascinates me about computing isn't really the code, it's the stack.

A transistor that opens or closes the path of a current. Assembled, transistors become logic gates: AND, OR, NOT, Boolean logic taking shape in silicon. Stacked, those gates become a processor, able to count, compare, decide. Above that, a compiler turns a human intention into binary instructions. Above that again, a language lets me write `if user.is_authenticated` without ever thinking about the voltage across a transistor.

Every layer hides the one below it and answers for it at the same time. But a compiler stays deterministic, documented, with a stable contract: I can always go back down and check what it produced. It's the same gesture as taking an appliance apart to see what's inside, except nothing breaks when you open it. Understanding a system all the way down, then deliberately choosing which floor to build on, that's what has always driven me.

AI changes the picture. It's a fantastic accelerator of knowledge; it compresses years of learning into a handful of well-posed prompts. But a language model is a probabilistic layer, with no stable interface and no guarantee of reproducibility. What it produces is still verifiable, of course: code can be read, tested, run. The trap is elsewhere. That verification demands exactly the judgment that comfortable use of the tool excuses you from acquiring. The more you delegate, the less you build of what it takes to read back what you delegated. So the problem isn't abstraction itself, it's abstraction without a contract, resting on a skill that quietly atrophies.

Commoditizing intelligence won't make engineers disappear, though. Electricity became a commodity too: today there are millions of electricians, and a handful of people who design the grids, the transformers and the standards that make their trade possible. Both are useful; they're simply not the same job. The second one is what interests me: the one where you still have to know why it works, and not only that it works. We can already see what the alternative costs, giants of clay that crumble a little further with every model improvement. No layer of their own, just a shortcut to someone else's.

I could be wrong. If these models end up offering contracts as stable and verifiable as a compiler's, the distinction collapses, and there'll be one more layer to get comfortable with, like all the others.

## What I'm building with it

**Kurtel**, a darwinian memory for AI coding agents (Claude Code, Codex).

Darwinian in the strict sense: the agent produces attempts that diverge, what proves useful survives and is passed on, the rest dies. Kurtel forgets on purpose. What matters is selection, not accumulation.

The agent I have in mind has no disk: its context window behaves like RAM wiped at every restart. Giving it a selective memory means giving it a disk that sorts rather than a disk that piles up.

And since I spend the text above warning against opaque layers: the memory is readable, and you can always go back down and see why one memory survived and another didn't.

## Let's dig into it together

Open-source backend tools, infrastructure for AI agents, or any conversation about why things work the way they do.

Contact

<a href="mailto:thomas.bodenan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"></a> <a href="https://www.linkedin.com/in/thomas-bodénan"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"></a> <a href="https://portfolio-thomas-iota.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white"></a>
