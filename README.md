# PRG • PRG Reading Group

- **When and where?** We meet on Wednesday 10:00, (roughly) every three weeks, alternating between MFF and FIT
- **Email updates** Sign up [here to receive email updates about meetings](https://forms.gle/ZBNJS5QdCa7CvAxV7).
- **What paper?** Post ideas and vote [using Github issues](https://github.com/prgprg-org/reading-group/issues)!

## :alarm_clock: Next Meeting

### Wednesday, 21 January 2026, 10:00 (FIT) 

- **What:** Capturing Types, by Aleksander Boruch-Gruszecki, Martin Odersky, Edward Lee, Ondřej Lhoták, and Jonathan Brachthäuser
- **Paper:** [https://dl.acm.org/doi/pdf/10.1145/3618003](https://dl.acm.org/doi/pdf/10.1145/3618003)
- **Where:** Room TH:A-1435, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Filip Říha
- **Comment:** Capabilities are an alternative for denoting effects like mutability, exceptions or resource management. They are an alternative to the other popular methods, like checked exceptions or monads. The greatest benefit is it that capabilities can be expressed with plain arguments and handle polymorphism "for free".
The paper describes a capture calculus, a type system that allows reasoning about scoped capabilities, even in presence of capturing closures and objects.
For the meeting focus on sections 1 and 2, describing the overall idea of capturing types, and section 5 providing some more motivating examples. Sections 3 is the definition of the calculus, we can go through it at the meeting, but it would be good to be familiar with its syntax. A related talk about the current state of capabilities: [Where Are We With Scala's Capabilities?, Martin Odersky](https://www.youtube.com/watch?v=AyGnDm_TwsY).

## :calendar: Future Meeting

### Wednesday, 4 February 2026, 10:00 (MFF) 

- **What:** TBA
- **Paper:** TBA
- **Where:** Room S4 (2nd floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Who:** TBA
- **Comment:** TBA
  
## :books: Past Meetings

### Wednesday, 17 December 2025, 10:00 (FIT) 

- **What:** egg: Fast and extensible equality saturation by  Max Willsey, Chandrakana Nandi, Yisu Remy Wang, Oliver Flatt, Zachary Tatlock, Pavel Panchekha
- **Paper:** [https://dl.acm.org/doi/pdf/10.1145/3434304](https://dl.acm.org/doi/pdf/10.1145/3434304)
- **Where:** Room TH:A-951, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Volodymyr Plita
- **Comment:** The paper introduces practical improvements to e-graphs—such as the rebuilding algorithm and e-class analyses—that make equality saturation efficient and extensible. The work made e-graphs popular again, and connects well-established theoretical ideas with a clean, usable implementation, supported by an [open-source library](https://egraphs-good.github.io/) that has been applied in multiple PL and optimization contexts for compilers. In the end I will also briefly mention [slotted e-graphs](https://steuwer.info/files/publications/2025/PLDI-Slotted-E-Graphs.pdf) that extend the original e-graph approach by adding first-class support for bound variables, allowing α-equivalent terms to be represented and rewritten uniformly. This makes equality saturation applicable and more efficient for languages and optimizations that involve binding, something traditional e-graphs and egg handle only awkwardly or inefficiently. The main parts to read  are the introduction (section 1), then background of e-graphs (section 2) and sections 3 and 4 with the two core innovations.

### Wednesday, 26 November 2025, 10:00 (MFF) 

- **What:** Sculpin: Direct-Manipulation Transformation of JSON by Horowitz, Hayatpur, Xia and Heer
- **Paper:** [https://dl.acm.org/doi/10.1145/3746059.3747651](https://dl.acm.org/doi/10.1145/3746059.3747651) 
- **Where:** S204 (corridor in front of), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/))
- **Who:** Joel Jakubovic
- **Comment:** The paper presents a direct-manipulation environment for processing JSON data and building simple applications that have JSON as the back-end.
    The idea is that non-programmers can use the tool to complete tasks with JSON that would normally require programming. The paper is a nice implementation
    of the more general idea. The main parts to read are the sections describing Sculpin, i.e., Sections 3 and 4. It is useful to look at the related work
    (Section 2), fun to look at further examples (Section 5) and you can get an idea about HCI evaluation methods in Section 6.

### Wednesday, 5 November 2025, 10:00 (FIT) 

- **What:** Practical compilation of fexprs using partial evaluation by Nathan Braswell, Sharjeel Khan, Santosh Pande
- **Paper:** [https://arxiv.org/pdf/2303.12254](https://arxiv.org/pdf/2303.12254)
- **Where:** Room TH:A-951, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Michal Žáček
- **Comment:** F-Expressions have historically been eschewed in favour of plain macros due to their inefficiencies and difficulties they pose for optimization. Since then, they have been forgotten and are missing from most all current languages. Nonetheless, they remain a fascinating subject due to their composability and the possibility of returning first-classness to our metaprogramming if their performance concerns are addressed. The article aims at showing that fexprs are a practical replacement of macros, and formulates a small purely functional fexpr based Lisp, Kraken, with an online partial evaluation and compilation framework that supports first-class, partially-static-data environments and can completely optimize away fexprs that are used and written in the style of macros. Focus on sections 1 and 2 for an overview. Read the intro of section 4 to get a taste of partial evaluation for fexprs.
  
### Wednesday, 15 October 2025, 10:00 (MFF) 

- **What:** Restrictable Variants: A Simple and Practical Alternative to Extensible Variants
- **Paper:** [https://drops.dagstuhl.de/storage/00lipics/lipics-vol263-ecoop2023/LIPIcs.ECOOP.2023.17/LIPIcs.ECOOP.2023.17.pdf](https://drops.dagstuhl.de/storage/00lipics/lipics-vol263-ecoop2023/LIPIcs.ECOOP.2023.17/LIPIcs.ECOOP.2023.17.pdf)
- **Where:** S204 (corridor in front of), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/))
- **Who:** Tomas Petricek
- **Comment:** Restrictable variants is an interesting language feature in the Flix programming language.
    It makes it possible to annotate algebraic data types (unions) to restrict what cases it can have,
    which is useful for example when writing a multi-pass compiler. The paper describes the feature and the
    theory behind it.
    For the meeting, focus on  sections 1, 2, 5 and 6 - this provides a nice overview of the idea and the design space.
    Section 3 gets theoretical. Have a look and we can try to get through some of the formalism at the meeting!

### Wednesday, 24 September 2025, 10:00 (FIT) 

- **What:** Introduction to the reading group, then _No Silver Bullet -- Essence and Accident in Software Engineering --_ by Frederick P. Brooks, then a surprise article...
- **Paper:** [https://www.cs.unc.edu/techreports/86-020.pdf](https://www.cs.unc.edu/techreports/86-020.pdf)
- **Where:** Room TH:A-951, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Pierre Donat-Bouillud, Filip Křikava
- **Comment:** 

### Wednesday, 10 September 2025, 10:00 (MFF) 

- **What:** Covariance and Controvariance: a fresh look at an old issue, Castagna
- **Paper:** [https://www.irif.fr/~gc/papers/covcon-again.pdf](https://www.irif.fr/~gc/papers/covcon-again.pdf)
- **Where:** S8 (1st floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/))
- **Who:** Mickael Laurent
- **Comment:** The goal is to have a tutorial about set-theoretical types. The article is a good introduction to set-theoretic types, which focuses on implementation while most other works only give a mathematical definition.
In particular, we may focus on section 4: Type algorithms for the language designer, which introduces the algorithm to decide subtyping using an interesting data structure (Binary Decision Diagram) that is used to represent logic formulas.
A related article about set-theoretic types: [https://www.irif.fr/~gc/papers/set-theoretic-types-2022.pdf](https://www.irif.fr/~gc/papers/set-theoretic-types-2022.pdf). 


### Wednesday, 11 June 2025, 10:00 (MFF) 

- **What:** Deegen: A JIT-Capable VM Generator for Dynamic Languages
- **Paper:** [https://arxiv.org/pdf/2411.10559](https://arxiv.org/pdf/2411.11469)
- **Where:** S204 (corridor in front of), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/))
- **Who:** Filip Křikava 
- **Comment:** Building a high-performance JIT-capable VM for a dynamic language has traditionally required a tremendous amount of time, money, and expertise. The article presents Deegen, a meta-compiler that allows users to generate a high-performance JIT-capable VM for their own language at an engineering cost similar to writing a simple interpreter. Deegen takes in the execution semantics of the bytecodes implemented as C++ functions, and automatically generates a two-tier VM execution engine with a state-of-the-art interpreter, a state-of-the-art baseline JIT, and the tier-switching logic that connects them into a self-adaptive system.  They implement LuaJIT Remake (LJR), a standard-compliant Lua 5.1 VM, using Deegen. Across 44 benchmarks, LJR's interpreter is on average 179% faster than the official PUC Lua interpreter, and 31% faster than LuaJIT's interpreter. 


### Wednesday, 21 May 2025, 10:00 (FIT) 

- **What:** Partial Evaluation, Whole-Program Compilation. Or, We have a Compiler at Home
- **Paper:** https://arxiv.org/pdf/2411.10559
- **Where:** Room T9:301, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Pierre Donat-Bouillud
- **Comment:** The article shows a quick and effective way to get a compiler from an interpreter. This is an application of the 1st Futamura projection. However, this approach does not require a heavily specialized interpreter and can reuse a nearly unmodified interpreter body from an already existing one. They show 2 case studies for
  Javascript and Lua interpreters compiled to WASM. I recommend to skim the paper, at least looking at section 3  and one of the case studies. 

### Wednesday, 23 April 2025, 10:00 (MFF) 

- **What:** MyWebstrates: Webstrates as Local-first Software
- **Paper:** https://telecom-paris.hal.science/hal-04700748v1/file/klokmose24-uist.pdf
- **Where:** S204 (corridor in front of), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/
- **Who:** Tomas Petricek
- **Comment:** Webstrates is a "computational medium" that makes it possible to create programs in a way that makes it easy to share them, modify them and collaborate around them. The paper presents an implementation of WebStrates that does not depend on a single server, but uses distributed peer-to-peer architecture based on the "local-first software" principles and is implemented based on the CRDT technology. This is a relatively light-weight paper that can be read as a whole. It is an interesting example of applying human-computer interaction research methods to a programming systems problem. I'd recommend skim-reading the whole paper - and reading parts that catch your attention in detail.
  
### Wednesday, 2 April 2025, 10:00 (FIT) 

- **What:** The Design Principles of the Elixir Type System
- **Paper:** https://arxiv.org/pdf/2306.06391
- **Where:** Room T9:301, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Thanks to Filip Říha for volunteering!
- **Comment:** This paper presents a new gradual type system for Elixir based on set-theoretic types. Elixir is a functional programming language based on the BEAM virtual machine (the VM of Erlang) used to build concurrent and fault-tolerant systems. A type system for this otherwise dynamic language aims to bring all of the static safety of types, not unlike what TypeScript is for JavaScript. However, unlike TypeScript, it is sound and does not introduce runtime checks in the code. Instead, it leverages type guards and pattern matches written by the programmer, a typical pattern in Elixir code. The paper is very practically oriented, showing why certain features were chosen for the type system and their usage, while it reserves very little space for formalization. I suggest reading section 2, an overview of the type system, and also section 3, which highlights some of the additions that the Elixir type system brings to the set-theoretical type theory (section 3.3 can be skipped, as it delves exhaustively into typing the Elixir records and maps).

### Wednesday, 12 March 2025, 10:00 (MFF)

- **What:** Stream Types
- **Paper:** https://dl.acm.org/doi/10.1145/3656434
- **Where:** Room S510 (5th floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Who:** Thanks to Vít Šefl for volunteering!
- **Comment:** The paper presents a static type system for tracking information about streams of data in stream-based programming. It can capture "both complex temporal patterns and deterministic parallel processing". Streams are common data types in various reactive systems, user interfaces and signal processing, so it is interesting to see how to exactly capture what is going on! We will probably mostly focus on sections 1-3, so try to read those. It may be interesting to also talk about examples in section 5.2.

### Wednesday, 19 February 2025, 10:00 (FIT)

- **What:** Retrofitting effect handlers onto OCaml
- **Paper:** https://arxiv.org/pdf/2104.00250
- **Where:** Room T9:301, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Thanks to Mickael Laurent for volunteering!
- **Comment:** The article describes an actual implementation of effects on a mainstream language, which did not support them before. The retrofitting approach is interesting in a PL design perspective: how do we evolve PL languages while maintaining backward and forward compatibility? 
   Read at least sections 1-3 for the context and possibly the evaluation part (section 6). I will start by an introduction to algebraic effects.

### Wednesday, 29 January 2025, 10:00 (MFF)

- **What:** Reclaiming the Unexplored in Hybrid Visual Programming
- **Paper:** https://michael.homer.nz/Publications/Onward2024/ReclaimingUnexplored-Homer2024.pdf
- **Where:** Room S6 (2nd floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Who:** Thanks to Joel Jakubovic for volunteering!
- **Comment:** The paper argues that we should do more work to explore visual representation of programs and visual programming.
   This is a short and readable paper and so I suggest looking at most of it in advance (sections 1-4). You can also
   experiment with the web-based demos available at: https://djel.org


### Wednesday, 8 January 2025, 10:00 (FIT)

- **What:** Syntax and Semantics of Dependent Types
- **Paper:** https://www.cs.uoregon.edu/research/summerschool/summer14/rwh_notes/ssdt.pdf
- **Where:** Room T9:364b, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Thanks to Ondřej Kubánek for volunteering!
- **Comment:** This is a dense paper, but we can use it as a starting point for taking the next step
  towards making sense of dependent types! Ondřej volunteered to start with a 30 minute presentation,
  so this will be more of an introduction to the topic. It is still a good idea to look at sections 1 and
  2 of the paper to know what to expect!

### Wednesday, 18 December, 10:00 (MFF)

- **What:** Copy-and-patch compilation: a fast compilation algorithm for high-level languages and bytecode
- **Paper:** [https://webspace.science.uu.nl/~swier004/publications/2023-icfp.pdf](https://arxiv.org/pdf/2011.13127)
- **Where:** S204 (corridor in front of), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Comment:** A paper about an extremely fast compilation technique that produces good quality code (and is also
  used in Python 3.13!) The core ideas are described in sections 2, 3 and 4, so make sure to read those. We
  will likely also want to look at the evaluation results in section 5 and 6 (but you can skim the text there).

### Wednesday, 27 November, 10:00 (FIT)

- **What:** Grokking the Sequent Calculus
- **Paper:** https://arxiv.org/pdf/2406.14719
- **Where:** Room T9:364b, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Thanks to Maya Mückenschnabel for volunteering!
- **Comment:** A paper that presents the sequent calculus as a compilation target for "compiler hackers". This is
   written as a tutorial paper and it is probably best to read at least sections 1 and 2 in some details.
   For the rest, look at the first few paragraphs of each section to get a sense of what it's about.

### Wednesday, 6 November, 10:00 (MFF)

- **What:** FP<sup>2</sup>: Fully in-Place Functional Programming
- **Paper:** https://webspace.science.uu.nl/~swier004/publications/2023-icfp.pdf
- **Where:** Room S510 (5th floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Who:** Thanks to Jaromír Procházka for volunteering!
- **Comment:** The paper describes a subset of a functional langauge where programs can be executed without
  any memory allocation. Read section 1, which provides a nice overview of the language. We will certainly want
  to understand the calculus and well-formedness rules in section 2.1 and 2.2. It may be also interesting to look
  briefly at some of the algorithms in section 3 and 4. 

### Wednesday, 9 October, 10:00 (FIT)

- **What:** Type-Level Computations for Ruby Libraries
- **Paper:** https://arxiv.org/abs/1904.03521
- **Where:** Room T9:364b, Thákurova 9, Praha 6 (see a [guide](https://help.fit.cvut.cz/rooms/index.html) and a [map](https://help.fit.cvut.cz/rooms/map.html#t9-3))
- **Who:** Tomas Petricek, Pierre Donat-Bouillud
- **Comment:** An interesting perspective on what "types" can mean for dynamic programming languages.
  Read at least sections 2 and 3, which are accessible and provide nice overview. We can then try to
  read some of the formalism in section 4 or try to look at the evaluation in section 5. You do not
  need to read sections 4 and 5 in detail, but try to skim them to see what to find there!

## :scroll: Paper Archives and Ideas

* In previous years, the group was organised using a [huge Google Doc](https://docs.google.com/document/d/1sz3G_62GRTERmxXcnczZqGLB1vT_W5dAUewKAMwpKT0/edit?usp=sharing) (remarkably, nobody accidentally deleted it). Check it out for papers we've read in the past.
* Please share your paper ideas (and volunteer to present a paper) [using Github Issues in this repository](https://github.com/prgprg-org/reading-group/issues).


