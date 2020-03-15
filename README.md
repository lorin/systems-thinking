# Systems thinking

Some notes on the different types of systems thinking.

“In systems thinking, increases in understanding are believed to be obtainable
by expanding the systems to be understood, not by reducing them to their
elements.” Russell L. Ackoff (quoted by [Steven
Shorrock](https://humanisticsystems.com/2019/11/25/four-kinds-of-thinking-2-systems-thinking/))

## Schools

I call these different *schools* of systems thinking, but it's just my own categorization.

### Signals and systems (EE)

If you say *systems* to an electrical engineering major, they will likely think
back to a course they took called *signals and systems*.

In this terminology, a *signal* is a function of time and a *system* is a black
box that takes a signal as input and produces a signal as output.

![System](system.png)

A system, denoted *H*, which takes a signal, x(t), as input and produces a
signal, y(t), as output. *H* is sometimes referred to as the *transfer
function*.

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

The mathematician Norbert Wiener coined the term *cybernetics* in the 1940s and it has since become something of a buzzword.

* Norbert Wiener
* W. Ross Ashby
* Stafford Beer (management cybernetics)
* Magoroh Maruyama
* Gordon Pask

#### References

* [Cybernetics: Or Control and Communication in the Animal and the Machine](https://en.wikipedia.org/wiki/Cybernetics:_Or_Control_and_Communication_in_the_Animal_and_the_Machine) by Norbert Wiener
* [Introduction to Cybernetics](http://pespmc1.vub.ac.be/ASHBBOOK.html) by W. Ross Ashby
* [An Approach to Cybernetics](https://www.pangaro.com/pask/pask%20approach%20to%20cybernetics.pdf) by Gordon Pask
* [The Second Cybernetics: Deviation-Amplifying Mutual Causal Processes](http://pespmc1.vub.ac.be/books/Maruyama-SecondCybernetics.pdf) by Magoroh Maruyama


### Stocks and flows / system dynamics

* Donella Meadows
* Jay Wright Forrester


#### Places to intervene in a systems

In increasing order of effectiveness:

1. Constants, parameters, numbers (such as subsidies, taxes, standards).
1. The sizes of buffers and other stabilizing stocks, relative to their flows.
1. The structure of material stocks and flows (such as transport networks, population age structures).
1. The lengths of delays, relative to the rate of system change.
1. The strength of negative feedback loops, relative to the impacts they are trying to correct against.
1. The gain around driving positive feedback loops.
1. The structure of information flows (who does and does not have access to information).
1. The rules of the system (such as incentives, punishments, constraints).
1. The power to add, change, evolve, or self-organize system structure.
1. The goals of the system.
1. The mindset or paradigm out of which the system — its goals, structure, rules, delays, parameters — arises.
1. The power to transcend paradigms.


#### Terms

stocks, flows, feedback loops, delays, buffers, dynamic equilibrium, archetypes, resilience, rules, goals, paradigms,
information flow, system traps


#### References

* [Leverage Points: Places to Intervene in a System](http://donellameadows.org/archives/leverage-points-places-to-intervene-in-a-system/) by Donella Meadows
* [Thinking in Systems: A Primer](https://www.amazon.com/Thinking-Systems-Donella-H-Meadows/dp/1603580557) by Donella Meadows ([my notes](https://github.com/lorin/booknotes/blob/master/Thinking-In-Systems.md))

### State-based

* Gerald M. Weinberg

#### Terms

law, system, functional notation, observer, observations, interpretation, state, set, categorization, properties, black-box, white box, structure, behavior, boundary, port, membrane, symmetry, composition, transitivity, diachronic, synchronicm dimensional reduction, open system, closed system, connections, partitions, state space, stability, identity, regulation, adaptation, black box, white box

#### References

* [Introduction to General Systems Thinking](https://www.amazon.com/Introduction-General-Systems-Thinking-Anniversary/dp/0932633498) by Gerald M. Weinberg ([my notes](https://github.com/lorin/booknotes/blob/master/Introduction-To-General-Systems-Thinking.md))


### Systemantics

*Systemantics* is John Gall's term for the pathological behaviors that systems invariably exhibit. 

* John Gall

#### Terms

systems, complex, exceptions, failures, bugs, problems, feedback, bypass, exploit, reality, malfunction, delusion, fallacy, anergy, expand, unexpected, behaves, law, goals, specialization, competition, selection, grow, evolve, anergy


#### References

[The Systems Bible](https://www.amazon.com/Systems-Bible-Beginners-Guide-Large/dp/0961825170) by John Gall ([my notes](https://github.com/lorin/booknotes/blob/master/Systemantics.md))


### Management

The following people applied systems thinking to management issues:

* Russell L. Ackoff
* Stafford Beer
* W. Edward Deming
* Peter M. Senge


#### References

* [Out of the crisis](https://www.amazon.com/Out-Crisis-Press-Edwards-Deming/dp/0262541157) by W. Edward Deming ([my notes](https://github.com/lorin/booknotes/blob/master/Out-Of-The-Crisis.md))
* [The fifth discipline](https://www.amazon.com/Fifth-Discipline-Practice-Learning-Organization/dp/0385517254) by Peter M. Senge 
* [The future of operational research is past](https://www.jstor.org/stable/25060027?seq=1) by Russell L. Ackoff


## People

* Russell L. Ackoff
* W. Ross Ashby
* Ludwig von Bertalanffy
* Stafford Beer
* [C. West Churchman](https://en.wikipedia.org/wiki/C._West_Churchman) ([The Systems Approach](https://www.amazon.com/Systems-Approach-C-West-Churchman/dp/0440384079))
* W. Edward Deming
* [Frederick Edmund Emery](https://en.wikipedia.org/wiki/Fred_Emery) ([Systems Thinking](https://www.goodreads.com/book/show/4528628-systems-thinking))

* Jay Wright Forrester
* John Gall
* Peter Senge (The Fifth Discipline)
* Herbert A. Simon
* Norbert Wiener (Cybernetics)
* Donella Meadows (Thinking In Systems)
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
