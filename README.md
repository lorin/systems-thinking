# Systems thinking

Some notes on the different types of systems thinking.

“In systems thinking, increases in understanding are believed to be obtainable
by expanding the systems to be understood, not by reducing them to their
elements.” Russell L. Ackoff (quoted by [Steven
Shorrock](https://humanisticsystems.com/2019/11/25/four-kinds-of-thinking-2-systems-thinking/))

## Schools

### Signals and systems (EE)

If you say *systems* to an electrical engineering major, they will likely think
back to a course they took called *signals and systems*.

In this terminology, a *signal* is a function of time and a *system* is a black
box that takes a signal as input and produces a signal as output.

![System](system.png)

A system, denoted *H*, which takes a signal, x(t), as input and produces a signal, y(t), as output.

Concepts in a signals and systems course constitute foundational mathematical tools for
communications theory and control theory. Communications engineers talk about
communicating over *channels*, and control engineers talk about controlling
*plants*: both channels and plants are modeled as systems.

Linear time-invariant (LTI) systems are an important class of systems, because such systems
can characterized entirely by what is called an *impulse response*: which is the output
when the input is a special signal called an impulse. LTI systems are also amenable to analysis
using mathematical tools called transforms (including Fourier, Laplace, and Z transforms).

Of particular interest to students of systems thinking, there are various mathematical tools
for studying feedback and stability of systems. These Include root locus plots, the Nyquist stability
criterion, and gain/phase margin using Bode plots.

Notably: Claude Shannon, Harry Nyquist, and Hendrik Wade Bode all worked at Bell Labs.

### Terms

signals, systems, linear time-invariant (LTI), transfer function, impulse response,
frequency response, magnitude response, phase response, bounded input bounded
output (BIBO) stability, Fourier transform, Laplace transform, Z transform, poles, zeros,
root-locus plot, Bode plot, Nyquist stability criterion, gain margin, phase margin

#### References

* [Signals and Systems](https://www.amazon.com/Signals-Systems-2nd-Alan-Oppenheim/dp/0138147574/) by Oppenheim and Willsky


### Cybernetics

Norbert Wiener

#### References

* [Cybernetics: Or Control and Communication in the Animal and the Machine](https://en.wikipedia.org/wiki/Cybernetics:_Or_Control_and_Communication_in_the_Animal_and_the_Machine) by Norbert Wiener
* [Introduction to Cybernetics](http://pespmc1.vub.ac.be/ASHBBOOK.html) by W. Ross Ashby


### Stocks and flows 

Donella Meadows


#### Places to intervene in a systems

In increasing order of effectiveness:

12. Constants, parameters, numbers (such as subsidies, taxes, standards).
11. The sizes of buffers and other stabilizing stocks, relative to their flows.
10. The structure of material stocks and flows (such as transport networks, population age structures).
9. The lengths of delays, relative to the rate of system change.
8. The strength of negative feedback loops, relative to the impacts they are trying to correct against.
7. The gain around driving positive feedback loops.
6. The structure of information flows (who does and does not have access to information).
5. The rules of the system (such as incentives, punishments, constraints).
4. The power to add, change, evolve, or self-organize system structure.
3. The goals of the system.
2. The mindset or paradigm out of which the system — its goals, structure, rules, delays, parameters — arises.
1. The power to transcend paradigms.



#### References

* [Leverage Points: Places to Intervene in a System](http://donellameadows.org/archives/leverage-points-places-to-intervene-in-a-system/) by Donella Meadows
* [Thinking in Systems: A Primer](https://www.amazon.com/Thinking-Systems-Donella-H-Meadows/dp/1603580557) by Donella Meadows

### State-based

Weinberg

### Systemantics

Gall

### System dynamics

Forrester

## People

* Russell L. Ackoff
* W. Ross Ashby
* Ludwig von Bertalanffy
* Stafford Beer
* W. Edward Deming
* Jay Wright Forrester
* John Gall
* Peter Senge
* Norbert Wiener
* Donella Meadows
* Virginia Satir
* Gerald M. Weinberg

### Russell L. Ackoff

#### [The Future of Operational Research is Past](https://ackoffcenter.blogs.com/files/the-future-of-operational-research-is-past.pdf)
The Journal of the Operational Research Society, Vol. 30, No. 2 (Feb., 1979), pp. 93-104

This paper is a criticism of the state of operations research. Notably, this is where Ackoff introduces his idea of *messes*:

> Managers are not confronted with problems that are independent of each other, but with dynamic situations that consist of complex systems of changing problems that interact with each other. I call such situations messes.

##### Summary

(Taken directly from the last section of the paper).

1. There is a greater need for decision-making systems that can learn and adapt effectively than there is for optimizing systems that cannot.
2. In decision making, account should be taken of aesthetic values - stylistic preferences and progress towards ideals - because they are relevant to quality of life.
3. Problems are abstracted from systems of problems, messes. Messes require holistic treatment. They cannot be treated effectively by decomposing them analytically into separate problems to which optimal solutions are sought.
4. OR's analytic problem-solving paradigm, "predict and prepare," involves internal contradictions and should be replaced by a synthesizing planning paradigm such as "design a desirable future and invent ways of bringing it about."
5. Effective treatment of messes requires interaction of a wide variety of disciplines, a requirement that OR no longer meets.
6. All those who can be affected by the output of decision making should either be involved in it so they can bring their interests to bear on it, or their interests should be well represented by researchers who serve as their advocates.

##### Terms

contextually naive, Machine Age, analysis, elements, reductionism, determinism, cause and effect, producer-product, self-control, humanization, environmentalization, synthetic, systems thinking, holism, expansionism, control, automation, optimization, objectivity, aesthetics, rationality, meands, ends, intrinsic, extrinsic, traits, style, messes, predicting the future, preparing for the future, design, invention, stakeholders

##### Quotes

First, practitioners decreasingly took problematic situations as they came, but increasingly sought, selected, and disorted them so that favoured techniques could be applied to them. 

Now, the nature of the situations [OR] faces is dictated by the techniques it has at its command.

[T]here is a greater need for decision-making systems that can learn and adapt quickly and effectively in rapidly changing situations than there is for systems that produce optimal solutions that deteriorate with change.

Because messes are systems of problems, the sum of the optimal solution to each component problem taken separately is *not* an optimal solution to the mess.

Managers do not solve problems: they manage messes.

Nature and the world are not organized as science and universities are. There are no physical, chemical, biological, psychological, sociological or even Operational Research problems. These are names of different points-of-view, different aspects of the same reality, not different kinds of reality. Any problematic situation can be looked at from the point-of-view of any discipline, but not necessarily with equal fruitfulness.

Progress in handling messes, as well as problems, derives at least as mmuch from creative reorganization of the way we pursue knowledge and the knowledge we already have as it does from new discoveries.


### W. Ross Ashby

#### [An introduction to cybernetics](http://documents.irevues.inist.fr/bitstream/handle/2042/30159/XX_CNE-LIPSOR_000704.pdf?sequence=1**

This book introduces Ashby's *law of requisite variety*.

## Other links

* [LOOPY: a tool for thinking in systems](https://ncase.me/loopy/)
* [Systems Thinking for Global Problems](http://www.cs.toronto.edu/~sme/SystemsThinking/) course by Steve Easterbrook at U.Toronto
