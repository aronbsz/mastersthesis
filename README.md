Github repository of my Bachelor's thesis. PDF version can be found [here](src/bachelors_thesis.pdf).

Abstract:

The design and development of technological systems can be made more efficient using model-based technologies. A formal model of the system under design makes it possible to automate tasks such as verification, code generation and qualitative, quantitative system-analysis.

Reactive components of a system model (e.g. communication protocols) are typically modeled using state-based formalisms. However, the construction of such a system-model is often difficult, since these protocols are more straightforward to design using example runs. To the best of my knowledge, there is no tool in the literature capable of creating  a state based model of a system (component) from a set of runs and then performing the desired analysis on the output.

The objective of my work is to ease the process of system design by creating a software, which makes it possible to model a system based on example runs. The core of this framework is provided by automaton learning algorithms, whose strength lies in the creation of state-based models using behavioral information.

To attain the above goal, I present a modular, extensible and easily integrable framework in this thesis. During my work, I've implemented two algorithms capable of handling arbitrary formalisms. I have evaluated the efficiency and applicability of these algorithms both theoretically, and by measurements.

The presented framework, while capable of supporting system design, also enables the development, comparison and application of automaton learning algorithms.
