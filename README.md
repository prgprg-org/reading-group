# PRG • PRG Reading Group

- **When and where?** We meet on Wednesday 10:00, (roughly) every three weeks, alternating betweeb MFF and FIT
- **Email updates** Sign up [here to receive email updates about meetings](https://forms.gle/ZBNJS5QdCa7CvAxV7).
- **What paper?** Post ideas and vote [using Github issues](https://github.com/prgprg-org/reading-group/issues)!

## :alarm_clock: Next Meeting

<!-- ## :calendar: Future Meeting -->

### Wednesday, 12 March 2025, 10:00 (MFF)

- **What:** Stream Types
- **Paper:** https://arxiv.org/pdf/2104.00250
- **Where:** Room S510 (5th floor), Malostranské nám. 25 (see a [map](https://www.mff.cuni.cz/en/internal-affairs/buildings-and-campuses/mala-strana) and a [building plan](https://cs.mff.cuni.cz/cs/prakticke-informace/plan-budovy))
- **Who:** Thanks to Vít Šefl for volunteering!
- **Comment:** The paper presents a static type system for tracking information about streams of data in stream-based programming. It can capture "both complex temporal patterns and deterministic parallel processing". Streams are common data types in various reactive systems, user interfaces and signal processing, so it is interesting to see how to exactly capture what is going on! We will probably mostly focus on sections 1-3, so try to read those. It may be interesting to also talk about examples in section 5.2.

## :books: Past Meetings

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


