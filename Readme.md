# A programmer’s reasoning flow

Now we are staring at some problem description. We may first look for small-scale input-output examples to understand the problem:

**Induction.** We need an algorithm that can handle such examples. Now you are doing induction: generalizing principles from experience.

**Deduction.** How do we know if it works for other unknown input? We do deduction to prove the correctness of our algorithm.

**Ontology**. We have to maintain data in computer memory. The goal is to make them efficient for the computers to process. In order words, what data structure can best capture the dynamic flow of my information?

**Induction again**. Then comes the very final stage: debugging. We induce the buggy part of the program from analyzing the unexpected outputs.
