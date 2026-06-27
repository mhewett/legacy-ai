# Legacy AI papers and books

## AI & Software Engineering papers 1985-1992

Starting in the 1950s, the phrase "Automatic Programming" was used to described methods of automating the job of a programmer. 
The first automatic programming systems were what we now call _compilers_.  They did indeed automate the task of writing
assembly language or machine code, but the maxim "_If it works, and we understand how it works, it's not AI_" was applicable and compilers
are no longer considered to be AI systems.  (One could argue that modern compilers that handle operations such as branch prediction, 
out-of-order execution, hardware pre-fetchers, heterogeneous cores, and GPUs are much closer to AI systems than not. There aren't
many people who can compile a C program for a multicore CPU by hand!)

In the 1960s Automatic Programming evolved to address generating code in a high-level
language like COBOL or FORTRAN from an even higher-level design.  As the software industry matured in the 1970s and 1980s, 
the descriptor "Automated Software Engineering" replaced the original phrase.

One branch of Automated Software Engineering research was based on specifying programs in formal logic, or by strictly specifying inputs and outputs of functions.
After a number of years researchers realized that the complexity and scale of real-world software programs (e.g. airline ticketing systems) overwhelmed the ability
of programmers to specify complete systems using logical constructs.

The field then went in several directions:
- Using very high-level languages like [SETL](https://en.wikipedia.org/wiki/SETL) or [UML](https://en.wikipedia.org/wiki/Unified_Modeling_Language) to specify programs.  This was especially popular in government applications.
- Using [Domain-Specific languages](https://en.wikipedia.org/wiki/Domain-specific_language) to specify programs in a specific domain such as scientific computation.  There was extensive work at Schlumberger Labs in this area.
- Transformational techniques that start with a high-level specification or a simple program and apply formal transformations to produce a program that meets the goal specifications.
- [Programming by example](https://en.wikipedia.org/wiki/Programming_by_example): supply desired input-output pairs and derive a program that produces them.
- [Visual programming](https://en.wikipedia.org/wiki/Visual_programming_language): the programmer uses a GUI to specify the data flow and operations in a program.  The visual programming system then generates the code or just executes it directly from the programmer-specified flow.
  - National Instruments produces [**LabView**](https://www.ni.com/en/shop/labview?srsltid=AfmBOorzoCCZWFsYRfj1vCQj_j_KWeZ3hnC4N9rne3R9A1DXq2cMNzLi), a very popular visual system for designing programs.  It is still available as of 2026.
  - There are also several visual programming environments for children, such as [Scratch](https://scratch.mit.edu/), [MakeCode](https://www.microsoft.com/en-us/makecode), [Snap!](https://snap.berkeley.edu/), and [Alice](https://www.alice.org/).
- [Genetic programming](https://en.wikipedia.org/wiki/Genetic_programming): evolving a program using techniques similar to evolution in nature.
  - The programming language [LISP](https://en.wikipedia.org/wiki/Lisp_(programming_language\)) is particularly suited for this technique. 

As of 2026, AI-based programming environments such as [Claude Code](https://code.claude.com/docs/en/overview) have revolutionized
software development.  They generate programs from descriptions written in a high-level, _informal_ specification language 
(e.g. English) using a neural net model trained on millions of lines of code.  Early AI programming systems did not have access to a
large dataset of programs so they had to resort to derivation and induction techniques that ultimately did not have
widespread applicability.

### Archive of published material from this period


### Other magazines, journals, and workshops (not scanned)
1. _IEEE Intelligent Systems (formerly IEEE Expert)_, Winter **1988** Special Issue on _AI/Software Engineering_.  
   1. Available online at [computer.org](https://www.computer.org/csdl/magazine/ex/1988/04).
   2. One good paper is _Interactive Problem Solving_ by [Elaine Kant](https://en.wikipedia.org/wiki/Elaine_Kant) pp. 36-49, which discusses issues that are still relevant to modern LLM-based AIs. 
2. _AI Magazine Vol.11, No. 4_, Winter **1990**.  Special issue on AI and Design.
   1. Available online at [Wiley](https://onlinelibrary.wiley.com/toc/23719621/1990/11/4). 
   2. Don't miss the workshop overview _Creating a Scientific Community at the Interface Between Engineering Design and AI_ by David Steier, pp. 18-22 which is only briefly mentioned in the Table of Contents. 
3. _AI Magazine Vol. 5, No. 1_, Spring **1984**.  Special issue on Automatic Programming.
   1. Available online at [Wiley](https://onlinelibrary.wiley.com/toc/23719621/1984/5/1).
   2. This issue contains a number of articles by important Automatic Programming researchers in the 1970s and 1980s.
4. _Software Engineering in the Twenty-First Century_, Michael R. Lowry, _AI Magazine September **1992**, Vol. 13, No. 3_, pp. 71-87.
   1. Available online at [Wiley](https://onlinelibrary.wiley.com/doi/epdf/10.1609/aimag.v13i3.1012) (free).
   2. How accurate was he?
5. _The Sixth Annual Knowledge-Based Software Engineering Conference (Summary)_, Peter G. Selfridge, **1992**.
   1. Available online at [Wiley](https://onlinelibrary.wiley.com/doi/epdf/10.1609/aimag.v13i1.984). 
6. _Proceedings of the Fifth Conference on Knowledge-Based Software Assistant_. September **1990**.
   1. A Summary is online at [acm.org](https://dl.acm.org/doi/10.1145/122388.122390).
   2. Full proceedings (486 pages) are available at [dtic.mil](https://apps.dtic.mil/sti/tr/pdf/ADA236327.pdf).
7. _AAAI Workshop on Automating Software Design: Domain-Specific Software Design_, July **1992**.
   1. A PDF is available online at [NASA](https://ntrs.nasa.gov/api/citations/19930008310/downloads/19930008310.pdf).
   2. Here is a link to the [main page](https://ntrs.nasa.gov/citations/19930008310).
8. _AAAI Workshop on Software Tools for Developing Agents_, **1998**.  Available online at [AAAI](https://aaai.org/proceeding/ws98-10/). 
9. _Automated Software Engineering Journal_, 33 volumes as of 2026.  Available online at [acm.org](https://dl.acm.org/journal/klu-ause).
10. _IEEE Software Magazine_.  43 volumes as of 2026.  Available online at [computer.org](https://www.computer.org/csdl/magazine/so).
    1. I particularly like Volume 1, Number 2 from April 1984.  An article by the Turing Award winner [Sir Tony Hoare](https://en.wikipedia.org/wiki/Tony_Hoare) titled _Programming: Sorcery or Science?_ states that professional programming practice should be based on underlying mathematical theories.  Read the article, then compare and contrast with current AI-based software development.


### Books about Automating Software Development
These were important books about AI-assisted programming and related topics in the 1980s and 1990s.  They are listed in chronological order.
1. Gries, David. ***The Science of Programming***. New York: Springer-Verlag, 1981. ISBNs `0-387-96480-0` and `3-540-96480-0`.
2. Barstow, David R., Howard E. Shrobe, and Erik Sandewall, eds. ***Interactive Programming Environments***. New York: McGraw-Hill, 1984. ISBN `0-07-003885-6`.
   - One of my favorite books to browse.
3. Rich, Charles, and Richard C. Waters, eds. ***Readings in Artificial Intelligence and Software Engineering***. Los Altos, CA: Morgan Kaufmann Publishers, 1986. ISBN `0-934613-12-5`.
4. Schwartz, J. T., Dewar, R., Dubinski, E., and Schonberg, E. ***Programming with Sets: An Introduction to SETL***.  New York: Springer-verlag, 1986.  ISBN `978-0387963990`.
   - The high-level language SETL was used in the 1980s and 1990s to specify program requirements for input to AI software generators.
5. Shu, Nan C. ***Visual Programming***. New York: Van Nostrand Reinhold, 1988. ISBN `0-442-28014-9`.
6. Biggerstaff, Ted J., and Alan J. Perlis, eds. ***Software Reusability, Volume 1: Concepts and Models***. New York: ACM Press; Reading, MA: Addison-Wesley, 1989. ISBN `0-201-08017-6`.
   - This is not really about Automatic Programming, but the concepts are related.
7. Dijkstra, Edsger W., ed. ***Formal Development of Programs and Proofs***. Reading, MA: Addison-Wesley, 1990. ISBN `0-201-17237-2`.
8. Lowry, Michael R., and Robert D. McCartney, eds. ***Automating Software Design***. Menlo Park, CA: AAAI Press; Cambridge, MA: MIT Press, 1991. ISBN `0-262-62080-4`.
9. Lieberman, Henry, ed. ***Your Wish Is My Command: Programming by Example***. San Francisco: Morgan Kaufmann, 2001. ISBN `1-55860-688-2`.
   - This is a later book, but shows how the field was transforming away from formal specifications.

## AI Agents
There was considerable work in the past on AI agents and cooperating systems of agents, sometimes called Distributed Artificial Intelligence.
Past systems were based on logic or knowledge-based systems rather than LLMs, but the concepts were similar.  While browsing the literature
one sees a focus on communication between agents; it was thought that agents would need special-purpose languages rather than human language.
Below are some historical books on topics related to AI Agents, presented in chronological order:

1. Agha, Gul. ***Actors: A Model of Concurrent Computation in Distributed Systems***. Cambridge, MA: MIT Press, 1986. ISBN `0-262-01092-5`.
2. Bradshaw, Jeffrey M., ed. ***Software Agents***. Menlo Park, CA: AAAI Press; Cambridge, MA: MIT Press, 1997. ISBN `0-262-52234-9`.
   - This book has a particular focus on human interaction with agents that is probably still useful today.  
3. Ferber, Jacques. ***Multi-Agent Systems: An Introduction to Distributed Artificial Intelligence***. Harlow, England: Addison-Wesley Longman, 1999. ISBN `0-201-36048-9`.
4. Weiss, Gerhard, ed. ***Multiagent Systems: A Modern Approach to Distributed Artificial Intelligence***. Cambridge, MA: MIT Press, 1999. ISBN `0-262-23203-0`.
5. Kaschek, Roland H., ed. ***Intelligent Assistant Systems: Concepts, Techniques and Technologies***. Hershey, PA: Idea Group Publishing, 2007. ISBN `978-1-59140-878-4`.  The ISBN is sometimes listed as ending with `-9`.

## Miscellaneous AI-related Books

Anyone wanting to understand the state of AI in the 1980s should consult the _Handbook of Artificial Intelligence_.
- Barr, Avron; Edward A. Feigenbaum; and Paul R. Cohen, eds. ***The Handbook of Artificial Intelligence***. 4 vols. Stanford, CA: HeurisTech Press; Los Altos, CA: William Kaufmann; Reading, MA: Addison-Wesley, 1981–1990. ISBNs `0-86576-004-7` and `0-201-51819-8`.

_MYCIN_ was a very successful medical expert system based on rules - a _rule-based expert system_.  This book collects all 
the important writings about MYCIN and related systems.
- Buchanan, Bruce G., and Edward H. Shortliffe, eds. ***Rule-Based Expert Systems: The MYCIN Experiments of the Stanford Heuristic Programming Project***. Reading, MA: Addison-Wesley, 1984. ISBN `0-201-10172-6`.

One of my favorite books is _The Architecture of Symbolic Computers_ which has a plethora of treasures for LISP aficionados.
- Kogge, Peter M. ***The Architecture of Symbolic Computers***. New York: McGraw-Hill, 1991. ISBN `0-07-035596-7`.

Another of my favorite books is _Associative Networks_ which has the added benefit of being printed on beautiful acid-free paper.
- Findler, Nicholas V., ed. ***Associative Networks: The Representation and Use of Knowledge by Computers***. New York: Academic Press, 1979. ISBN `0-12-256380-8`.

## Doug Lenat thesis and other papers
