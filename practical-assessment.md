# Practical assessment of the state of quantum computing

### January 2020

Quantum computing is still in its infancy. IBM has been working hard to not oversell quantum capabilities. They have divided the progress into three categories:
1. Quantum Formulation - can it be done? Labs, PhDs, expensive uncertain experiments. We've pretty much passed this.
2. Quantum Ready - capacity and knowledge is growing but everything acheivable by quantum computers can also be done on classical computers. Where we are today.
3. Quantum Advantage - in specific applications and areas, quantum computing provides significant processing time or memory advantages compared to classical computing. Expect this to be a gray area, with back and forth. Research Team A may demonstrate a clear advantage using quantum computers, only to see Research Team B announce a few months later that they have discovered a speed-up in a classical algorithm that puts the classical approach back on top. Presumably this will happen several times. Some clarifications:
- In 2019 Google announced quantum supremacy on a particular math problem. This isn't in the Quantum Advantage category because the math problem was so esoteric that it wouldn't be used by a business.
- Pre-2020 many companies have announced that they are using "quantum" to solve problems. This isn't evidence of Quantum Advantage because these announcements refer to Quantum Annealing, a quantum system that can only solve one particular problem, and isn't a universal quantum system.

So, for the average developer, the takeaway is: in 2020 you aren't going to get a job in quantum computing. Also, you aren't going to get a job as a classical developer at a quantum computing company.

That being said, quantum computing is accelerating. The graph of the number of qubits in a quantum system are starting to show exponential speedup. It has moved from something far off in the distant future, to something that could break in the near term.

At some point, quantum computing will be "dumbed-down" enough that non-PhDs can contribute to it. There is no guarantee that it will be made as simple as computing today. But I think these historical points are important:

1. ENIAC - 1945, FORTRAN - 1953, C++ - 1979, Node.js - 2009 - these milestones are arbitrary, but they represent the progression in ease-of-use for classical computing. We are roughly, pre-ENIAC at the moment in computational power, but lessons have been learned about how to write computing languages, so on the language side we're much closer to Node.js (well, actually, Python). Where you jump on this progress is a matter of personal preference.

2. Even though ease-of-use will continue, there is probably no way to avoid the fact that linear algebra, matrix math, and probability theory will be required. So, the barrier of entry will drop, but not all the way to the seeming simplicity of modern programming languages.

In conclusion: probably the best strategy for quantum computing is:
1. Learn/get better at linear algebra.
2. Read up on quantum computing, probably that quantum.country website, so that you understand what is involved. Sign up for a quantum account somewhere, read the relevant language documentation and write a few "hello world" programs. At the moment the only company that is offering free access to quantum systems is IBM Q.
3. Stay informed.


