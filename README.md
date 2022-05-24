# cs492-program-reasoning

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs (mailing list: cs492.ta@prosys.kr)
  - TBA
- Time: Tue/Thr 09:00 - 10:15
- Office hour: Tue 10:15 - 11:00 (by appointment)
- Location: 

## Course Description
The main theme of this course is __"the relationship between specification and program"__ for safe and reliable software.
This course will cover two topics under the theme:
1. **program verification**: how to automatically _prove_ whether a given program satisfies the specification,
2. **program synthesis**: how to automatically _generate_ a program that satisfies the specification.

Students will learn theories and practices of program verification and synthesis through lectures, assignments, and term projects.
This course will be highly interactive and involve a significant amount of academic communication including reading, writing, and presentations.

## Grading
- Assignments: 20%
- Midterm project: 30%
- Final project: 40%
- Participation: 10%

## Textbook
- Lecture slides will be provided
- [Program Synthesis](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf) (PS)
- [Introduction to Program Synthesis](https://people.csail.mit.edu/asolar/SynthesisCourse/index.htm) (IPS)
- [The Calculus of Computation](https://www.amazon.com/Calculus-Computation-Procedures-Applications-Verification/dp/3540741127) (COC)

## Homework
This course includes programming assignments through which students will learn how to design
and implement program synthesizer and program verifier.
Students will use a few tools which are described [here](TOOL.md).

All submissions will be managed using Github.
For each assignment, a unique invitation URL for Github Classroom will be posted in the [issue board](../../issues).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late

## Presentation
- Each student is required to give 4 presentations (midterm project, final project proposal, final project result, and paper presentation).
- Each student is required to give at least 1 question for each student presentation.

## Projects
- Midterm project: each student will design and implement an advanced program synthesizer.
  - Presentation: students will present their own idea to advance a naive program synthesizer.
- Final project: each student will define and solve your own problem related to program synthesis or program verification.
  - Proposal writing: students will submit their project proposal that will be reviewed by other students, TAs, and instructors.
  - Proposal presentation: students will present their plans for the project and rebut criticism from reviewers.
  - Final presentation: students will present their results.

## Academic Integrity Violation
Students who violate academic integrity will get F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)||
|1|[Introduction](slides/lecture1.pdf)||HW0: OCaml Programming||
| |[Introduction to Program Verification](slides/lecture8.pdf)|||
|2|Operational Semantics|||
| |[Propositional Logic](slides/lecture9.pdf)|COC Ch1|
|3|[First-order Logic](slides/lecture10.pdf)|COC Ch2|
| |[First-order Theory](slides/lecture11.pdf)|COC Ch3|
|4|[Hoare Logic](slides/lecture12.pdf)|COC Ch5|[HW4: Reading Critique](https://cacm.acm.org/magazines/2021/7/253452-formal-software-verification-measures-up/fulltext)|
| |[Automatic Verification using Contrained Horn Clauses](slides/lecture13.pdf)||HW5: Program Verifier|
|5|[Introduction to Program Synthesis](slides/lecture2.pdf)|PS Ch1-2, IPS Lec1|[HW1: Reading Critique](https://www.wired.com/story/ai-write-code-like-humans-bugs/)|
| |[Inductive Synthesis and Enumerative Search](slides/lecture3.pdf)|PS Ch4.1, IPS Lec2-4||
|6|[Search Space Pruning](slides/lecture4.pdf)|||
| |[Search Space Prioritization](slides/lecture5.pdf)||[HW2: Reading Critique](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext)|
|7|[Representation-based Search](slides/lecture6.pdf)||HW3: Program Synthesizer|
| |[Program Synthesis and Verification](slides/lecture7.pdf)|||


## Acknowlegement
A large part of the slides is based on the lecture notes of similar courses by
- [Nadia Polikarpova](https://github.com/nadia-polikarpova/cse291-program-synthesis)
- [Woosuk Lee](http://psl.hanyang.ac.kr/courses/cse9116_2022s/)
- [Hakjoo Oh](http://prl.korea.ac.kr/~pronto/home/courses/aaa528/2018/)
- [Isil Dillig](https://www.cs.utexas.edu/~isil/cs389L/).
