# CS424: Program Reasoning [🇰🇷](README.md)[🇬🇧](README.en.md)

## Logistics
- Instructor: Kihong Heo [🏠](https://kihongheo.kaist.ac.kr) [📧](mailto:kihong.heo@prosys.kaist.ac.kr)
- TAs [📧](mailto:cs424.ta@prosys.kaist.ac.kr)
  - Sujin Jang [🏠](https://sujin0529.github.io)
  - Bongjun Jang [🏠](https://bongjunj.github.io)
- Lecture time: Mon/Wed 09:00 - 10:15
- Office hours (by appointment):
  - Instructor: Mon 10:15 - 11:00
  - TAs: Mon 10:15 - 11:00
- Location: N1 102

## Course Description [<img src="icons/youtube.png" width="16" />](https://youtu.be/nlsO6Cl6ync?si=TVeigZImwT-x-OqJ)
> Can we automatically create the program I want? And can we automatically prove that the program is what I want?

The core theme of this course is the "relationship between specification and implementation" for building safe and trustworthy software.
Broadly speaking, we cover the following two subtopics:
1. **program verification**: how can we _automatically prove_ that a given implementation satisfies the specification?
2. **program synthesis**: how can we _automatically generate_ an implementation that satisfies the specification?

Students will learn the theory and practice of program verification and synthesis through lectures and homework.
And beyond that, we will together envision a future in which true artificial general intelligence, equipped with both logic and intuition, is realized.

## Grading
#### Weighting
- Homework: 30%
- Final Exam: 50%
- Participation: 20%
  - This is a reward for students who actively participate and [spontaneously express what they learned in diverse ways](hof.md).
  - I hope to see you every class. [Attendance is not quantitatively assessed](https://prosys.kaist.ac.kr/attendance/) because it is not worth quantifying.

#### Evaluation Criteria
- Absolute grading: A >= 70, B >= 50, C >= 30, D >= 20, F < 20

## Note on P/NR
This course does not allow P/NR grading.
Freshmen must receive prior approval from the instructor by email before registering.

## Textbook
- Lecture slides will be provided.
- [Program Synthesis](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf) (PS)
- [Introduction to Program Synthesis](https://people.csail.mit.edu/asolar/SynthesisCourse/index.htm) (IPS)
- [The Calculus of Computation](https://www.amazon.com/Calculus-Computation-Procedures-Applications-Verification/dp/3540741127) (COC)

## Commitment to Engagement
For a class where everyone can stay fully engaged, let’s agree not to place any electronic devices (laptops, tablets, phones) on the desk.
The negative effects of using electronic devices during class are already widely known ([1](https://www.sciencedirect.com/science/article/pii/S0360131512002254?via%3Dihub),[2](https://www.nytimes.com/2025/08/21/opinion/mobile-phones-college-classrooms.html)).
They not only distract you, but also seriously interfere with the ability of those around you to focus on the class.
I hope this will be a class where, rather than everyone looking at separate monitors, we all look at the same place together and have lively discussions.
The necessary materials are in this repository, so please print them out in advance if you want.

For more details, see [this article](https://prosys.kaist.ac.kr/engagement/).

## Homework
In this course, students will learn how to design and implement program verifiers and synthesizers through a variety of programming assignments.
We will use several tools listed [here](TOOL.md).

The program used to grade program verifiers is automatically generated using [BugSynth](https://prosys.kaist.ac.kr/bugsynth/).
BugSynth is a tool that uses LLMs and program verification techniques to generate natural and trustworthy buggy programs for grading.

All homework submissions are handled through GitHub and Gradescope.
For each homework, a GitHub Classroom invitation URL for submission will be announced on the [discussion board](https://github.com/prosyslab-classroom/cs424-program-reasoning/discussions).
Once you accept the invitation, a private personal repository for your homework will be created.
You may submit to that repository as many times as you want before the deadline,
and you can submit that repository to Gradescope to check the grading results.

Late submissions are graded according to the following policy:
- 80% of the score if one day late
- 50% of the score if two days late
- 0% if three days or more late

## Academic Integrity
Students who violate academic integrity will receive an F. See the [KAIST School of Computing honor code](https://cs.kaist.ac.kr/content?menu=309).

Submitting material found everywhere in the world (for example, Google search or ChatGPT) as if it were your own work violates academic integrity.
The principle for this course is that all assignments must be completed using your own abilities.
Submitted assignments are automatically compared with existing works (other students, past students, AI-generated works, etc.), and if they are similar, the submission is judged as plagiarism.
This is a long-standing principle in academia, and it has not changed just because internet search or AI tools have appeared.

AI tools can reduce your effort, but they do not develop deep thinking.
Many experiments have repeatedly pointed this out ([1](https://cacm.acm.org/news/the-impact-of-ai-on-computer-science-education/),
[2](https://product.kyobobook.co.kr/detail/S000000600543)
[3](https://www.washingtonpost.com/technology/2026/07/07/how-stop-chatgpt-ruining-how-you-think/)).
Regardless of the AI model, [similar questions often receive similarly ordinary answers](https://arxiv.org/pdf/2510.22954).
Please do not easily give up your valuable learning opportunities.

## Schedule
|Week|Topic|Reading|Homework|
|-|------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)||<img src="icons/github-classroom.png" width="16" />HW0: Hello-world, OCaml Programming|
|1|[Introduction](slides/lecture1.pdf)|<img src="icons/youtube.png" width="16" /> Undecidability [<img src="icons/kor.png" width="16" />](https://youtu.be/oippSXvxUlw) [<img src="icons/eng.png" width="16" />](https://www.youtube.com/watch?v=HeQX2HjkcNo&t=2)||
|2|[Operational Semantics](slides/lecture2.pdf)||<img src="icons/github-classroom.png" width="16" />HW1: SmaLLVM Interpreter|
|3|[Concepts in Program Verification](slides/lecture3.pdf)|||
|4|[Propositional Logic](slides/lecture4.pdf)|COC Ch1, <img src="icons/youtube.png" width="16" /> [Curry-Howard Correspondence](https://cs3110.github.io/textbook/chapters/adv/curry-howard.html)||
|5|[First-order Logic](slides/lecture5.pdf)|COC Ch2||
|6|[First-order Theory](slides/lecture6.pdf)|COC Ch3|<img src="icons/github-classroom.png" width="16" />HW2: Automated Theorem Proving|
|7|[Hoare Logic](slides/lecture7.pdf)|COC Ch5, [CACM'21](https://cacm.acm.org/magazines/2021/7/253452-formal-software-verification-measures-up/fulltext)|<img src="icons/github-classroom.png" width="16" />HW3: Verification-aware Programming|
|8|[Automated Program Verification](slides/lecture8.pdf)||<img src="icons/github-classroom.png" width="16" />HW4: SmaLLVM Verifier|
|9|[Overview of Program Synthesis](slides/lecture9.pdf)|PS Ch1-2, IPS Lec1, [Wired](https://www.wired.com/story/ai-write-code-like-humans-bugs/), [IEEE Spectrum](https://spectrum.ieee.org/ai-code-generation-language-models), [CACM](https://cacm.acm.org/magazines/2022/10/264844-neurosymbolic-ai/fulltext)||
|10|[Inductive Synthesis and Enumerative Search](slides/lecture10.pdf)|PS Ch4.1, IPS Lec2-4|<img src="icons/github-classroom.png" width="16" />HW5: LIA Synthesizer|
|11|[Search Space Pruning](slides/lecture11.pdf)|||
|12|[Search Space Prioritization](slides/lecture12.pdf)|[CACM'18](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext)||
|13|[Representation-based Search](slides/lecture13.pdf)||<img src="icons/github-classroom.png" width="16" />HW6: SLIA Synthesizer|
|14|[Constraint-based Search](slides/lecture14.pdf)|||
|15|[Functional Synthesis](slides/lecture15.pdf)||<img src="icons/github-classroom.png" width="16" />HW7: CEGIS|
|16|[Neuro-Symbolic AI](slides/lecture16.pdf)|[Trustworthy AI](https://prosys.kaist.ac.kr/trustworthy/)|<img src="icons/github-classroom.png" width="16" />HW8: AI-based Program Synthesis|
|-|Final Exam|||

## Hall of Fame
Enjoy the wonderful works left behind by students from last semester [here](hof.md) (essays, drawings, etc.).

## Related Courses
- [CS402: Introduction to Logic for Computer Science](https://github.com/hongseok-yang/logic23), KAIST
- [CS524: Program Analysis](https://github.com/prosyslab-classroom/cs524-program-analysis), KAIST

## Acknowledgments
The course materials were prepared with reference to the materials from the courses below.

- [CS389: Automated Logical Reasoning](https://www.cs.utexas.edu/~isil/cs389L/), Univ. of Texas at Austin
- AAA528: Computational Logic, Korea Univ.
- [CSE291: Program Synthesis](https://github.com/nadia-polikarpova/cse291-program-synthesis), UCSD
- [CSE9116: Program Synthesis](http://psl.hanyang.ac.kr/courses/cse9116_2022s/), Hanyang Univ.

## References
#### Basics
- [PL Wiki](https://github.com/prosyslab/pl-wiki/wiki)
- [Gödel, Escher, Bach](https://www.aladin.co.kr/m/mproduct.aspx?ItemId=113285054)
- [Imagine the Impossible](https://www.youtube.com/watch?v=nJiw4g2ZM1E)

#### Program Verification
- [Formal Software Verification Measures Up](https://dl.acm.org/doi/10.1145/3464933), CACM 2021
- [Automated Reasoning @ Amazon](https://www.amazon.science/blog/?q=&f0=0000017d-6ba3-ddaa-a97d-efa3e2ed0000&s=0&expandedFilters=Research%2520area%2CTag%2CConference%2CAuthor%2CDate%2C)
- [Machine-assisted Proof](https://youtu.be/AayZuuDDKP0?si=H2Pl-Y-K3oysfA8W)
- [Translation Validation](https://github.com/prosyslab/pl-wiki/wiki/번역-검산(Translation-Validation))

#### Program Analysis
- [Infer](https://fbinfer.com)
- [CodeQL](https://codeql.github.com)
- [Lessons from Building Static Analysis Tools at Google](https://dl.acm.org/doi/10.1145/3188720), CACM 2018
- [Scaling Static Analysis at Facebook](https://cacm.acm.org/magazines/2019/8/238344-scaling-static-analyses-at-facebook/fulltext), CACM 2019
- [Detect Bugs Early with the Static Analyzer](https://developer.apple.com/videos/play/wwdc2021/10202/), Apple WWDC 2021

#### Program Synthesis
- [Search-based Program Synthesis](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext), CACM 2018
- [AI Can Write Code Like Humans-Bugs and All](https://www.wired.com/story/ai-write-code-like-humans-bugs/). Wired 2021
- [Coding Made AI-Now, How Will AI Unmake Coding?](https://spectrum.ieee.org/ai-code-generation-language-models), IEEE Spectrum 2022
- [Autocorrect Errors in Excel](https://www.nature.com/articles/d41586-021-02211-4), Nature 2021
- [Asleep at the Keyboard? Assessing the Security of GitHub Copilot’s Code Contributions](https://cacm.acm.org/research-highlights/asleep-at-the-keyboard-assessing-the-security-of-github-copilots-code-contributions/), CACM 2025

#### Artificial General Intelligence with Both Logic and Intuition
- [Neurosymbolic AI](https://cacm.acm.org/magazines/2022/10/264844-neurosymbolic-ai/fulltext), CACM 2022
- [Trustworthy AI](https://prosys.kaist.ac.kr/trustworthy/), KAIST Melting Pot Seminar, 2022
- [Thinking Fast and Slow](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555), [Thinking, Fast and Slow](https://product.kyobobook.co.kr/detail/S000000597589) (translated edition)
- [Safeguarding Mobile AI Agent](https://github.com/prosyslab/pl-wiki/wiki/VeriSafe-Agent)

#### Miscellaneous
- [BugSynth](https://prosys.kaist.ac.kr/bugsynth/)
- [Recursion World](https://prosys.kaist.ac.kr/recursion)
