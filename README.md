# CS492: Program Reasoning

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
- Assignments: 45%
- Final Exam: 45%
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

## Academic Integrity Violation
Students who violate academic integrity will get F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)||
|1|[Introduction](slides/lecture1.pdf)||HW0: OCaml Programming||
| |[Introduction to Program Verification](slides/lecture8.pdf)|||
|2|Operational Semantics||HW1: SmaLLVM Interpreter|
|3|[Propositional Logic](slides/lecture9.pdf)|COC Ch1|
|4|[First-order Logic](slides/lecture10.pdf)|COC Ch2|
|5|[First-order Theory](slides/lecture11.pdf)|COC Ch3|
|6|[Hoare Logic](slides/lecture12.pdf)|COC Ch5, [CACM'21](https://cacm.acm.org/magazines/2021/7/253452-formal-software-verification-measures-up/fulltext)||
|7|[Automatic Verification using Contrained Horn Clauses](slides/lecture13.pdf)||HW2: Program Verifier|
|8|No class|||
|9|[Introduction to Program Synthesis](slides/lecture2.pdf)|PS Ch1-2, IPS Lec1, [Wired](https://www.wired.com/story/ai-write-code-like-humans-bugs/)||
|10|[Inductive Synthesis and Enumerative Search](slides/lecture3.pdf)|PS Ch4.1, IPS Lec2-4||
|11|[Search Space Pruning](slides/lecture4.pdf)||HW3: Enumerative Synthesizer|
|12|[Search Space Prioritization](slides/lecture5.pdf)|[CACM'18](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext)||
|13|[Representation-based Search](slides/lecture6.pdf)|||
|14|[Program Synthesis and Verification](slides/lecture7.pdf)|||
|15||||
|16|No class|||


## Acknowlegement
A large part of the slides is based on the lecture notes of similar courses by
- [Nadia Polikarpova](https://github.com/nadia-polikarpova/cse291-program-synthesis)
- [Woosuk Lee](http://psl.hanyang.ac.kr/courses/cse9116_2022s/)
- [Hakjoo Oh](http://prl.korea.ac.kr/~pronto/home/courses/aaa528/2018/)
- [Isil Dillig](https://www.cs.utexas.edu/~isil/cs389L/)
