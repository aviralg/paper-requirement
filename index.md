---
layout: default
---

# Research Paper

## **[On the Design, Implementation and Use of Laziness in R](assets/pdf/paper.pdf)** 
[Accepted](https://2019.splashcon.org/details/splash-2019-oopsla/37/On-the-Design-Implementation-and-Use-of-Laziness-in-R) @ [SPLASH 2019, OOPSLA](https://2019.splashcon.org/track/splash-2019-oopsla).

### Abstract

The R programming language has been lazy for over twenty five years. This paper presents a review of the
design and implementation of call-by-need in R, and a data-driven study of how generations of programmers
have put laziness to use in their code. We analyze 16,707 libraries and observe the creation of 270.9 B promises.
Our data suggests that there is little supporting evidence to assert that programmers use laziness to avoid
unnecessary computation or to operate over infinite data structures. For the most part R code appears to have
been written without reliance on, and in many cases even knowledge of, delayed argument evaluation. The
only significant exception is a small number of packages and core libraries which leverage call-by-need for
meta-programming.


# Advisor's Statement

> Aviral was the sole author of the research presented in this paper, my role was limited to helping write up.

<p style="text-align: right">—<a href="http://janvitek.org/">Jan Vitek</a></p>
