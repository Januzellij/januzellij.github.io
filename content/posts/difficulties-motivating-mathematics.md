---
title: "Difficulties Motivating Mathematics"
date: 2018-08-03T20:15:00-06:00
draft: false
math: true
---

K-12 math education has major issues. Teaching is extremely formulaic, little time is spent on proofs of basic results, and creativity is rarely encouraged. But this is a solvable problem, since the barriers to fixing these problems are bureaucratic: we know how to teach math well, it's getting people to do it widespread at the K-12 level that's difficult.

I’d like to instead talk about a difficulty that arises when motivating math at a higher level (graduate level or research level). Mathematicians today are still somewhat motivated by classical questions. Number theorists want to study solutions of Diophantine equations, algebraic geometers want to study algebraic curves, analysts want to solve partial differential equations, etc. But the rub here is that over the years mathematicians have built this giant collection of machinery and definitions to better attack these classical questions. and so may spend the vast majority of their time and energy in this world of higher machinery. Sure, you have instances where you get an explicit connection; the most famous being the proof of Fermat’s Last Theorem, which came about via advances in showing modularity lifting theorems for certain Galois representations. However, this is an exception, which causes a curious expositional problem.

We want to say we’re motivated by these classical questions when in fact the immediate object of our eye is often only tangentially related. Furthermore, it may be the case that we don’t care about the classical questions at all! While machinery may be introduced to solve classical questions, it can be sufficiently interesting to study independently. As an example, consider the class group of a number field. This is a (finite) group that contains information regarding how ideals factor in the ring of integers of a number field. Computing these groups is helpful in solving classical questions: for example, if I want to solve \\( xy = z^3 \\) over the ring of integers of a number field, and I know \\( x \\) and \\( y \\) are coprime, I can use the class group to narrow down what \\( x \\) and \\( y \\) can be (in the best case of course, they’re third powers).

However, once we have these class groups, we can ask questions about them. One fertile source of questions is the following:  it’s a well known theorem that there are finitely many number fields of discriminant \\( d \\) and degree \\( n \\). We can then order number fields of a fixed degree by discriminant and do some counting. Let \\( R_n(d) \\) be the number of number fields of discriminant less than \\( d \\), of a fixed degree \\( n \\) whose class group has some property: nontrivial \\( k \\)-torsion, generated by \\( k \\) elements, equal to some fixed group \\( G \\) etc. Now we can ask about the asymptotics of \\( R_n(d) \\) as \\( d \\) gets large compared to \\( C_n(d) \\): the number of number fields of discriminant less than \\( d \\), of a fixed degree \\( n \\). This has been the subject of a lot of recent work (buzzwords: Cohen-Lenstra heuristics, arithmetic statistics). But how related to classical questions are these new questions? If I was a number theorist working on these distribution questions, how easily can I motivate them, given that they have little connection to the original impetus for defining class groups?

This isn't a general academia problem, but a math-specific problem. A molecular biologist working on gene editing doesn’t have to define 'gene' to a layman, and can explain the direction of their research. Physicists may find this a bit harder, but still doable: a cosmologist can say they study the formation of galaxies, or black holes, or what the early universe looked like. This is, once again, simultaneously **accessible** and **correct** in giving the broad idea of their research. But what on earth is someone working in derived algebraic geometry or the Langlands program supposed to say? Merely to define the objects they study would take hours. These objects certainly grew out of the study of classical questions, but outlining that connection isn’t something that is worth it in a short, expositional setting. There are some exceptions (a knot theorist, cryptographer or combinatorialist has a better chance) but plenty of thorny areas.

I’m not saying that we’ve gotten our heads lost in the clouds of abstraction: this mass of higher machinery is important and beautiful and structured and has every right to be considered and studied as mathematics. However, this is a uniquely challenging expositional situation for mathematicians.