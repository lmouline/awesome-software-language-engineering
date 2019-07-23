<!-- Matomo -->
<script type="text/javascript">
  var _paq = _paq || [];
  /* tracker methods like "setCustomDimension" should be called before "trackPageView" */
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="//matomo.mleduc.xyz/matomo/";
    _paq.push(['setTrackerUrl', u+'piwik.php']);
    _paq.push(['setSiteId', '2']);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.type='text/javascript'; g.async=true; g.defer=true; g.src=u+'piwik.js'; s.parentNode.insertBefore(g,s);
  })();
</script>
<!-- End Matomo Code -->

 ![Logo](awesome.png)

> SLE is defined as the application of systematic, disciplined, and measurable approaches to the development, deployment, use, and maintenance of software languages — [SLEBoK (Software Language Engineering Body of Knowledge)](https://slebok.github.io/)

This is a collection of software language engineering (SLE) tools, frameworks and books.  
With a focus on maintained and open-source projects.  
Pull requests are very welcome!

**Table of content**

[TOC]

# Language Workbench

> A language workbench is a software development tool designed to define, reuse and compose domain-specific languages together with their integrated development environment. Language workbenches support language-oriented programming. Language workbenches were introduced and popularized by Martin Fowler in 2005. - [Wikipedia](https://en.wikipedia.org/wiki/Language_workbench)

- **The GEMOC Studio:** [http://gemoc.org/studio.html](http://gemoc.org/studio.html)
- **Monticore:** [http://www.monticore.de/](http://www.monticore.de/)
- **MPS:** [https://www.jetbrains.com/mps/](https://www.jetbrains.com/mps/)
- **Neverlang:** [http://neverlang.di.unimi.it/](http://neverlang.di.unimi.it/)
- **Rascal:** [http://www.rascal-mpl.org/](http://www.rascal-mpl.org/)
- **Spoofax:** [www.metaborg.org/](https://www.metaborg.org/)
- **Xtext:** [https://www.eclipse.org/Xtext/](https://www.eclipse.org/Xtext/)
- **Racket:** [https://racket-lang.org/](https://racket-lang.org/)


# Attribute grammar

> An attribute grammar is a formal way to define attributes for the productions of a formal grammar, associating these attributes with values. The evaluation occurs in the nodes of the abstract syntax tree, when the language is processed by some parser or compiler.  - [Wikipedia](https://en.wikipedia.org/wiki/Attribute_grammar)

- **Silver:** [http://melt.cs.umn.edu/silver/](http://melt.cs.umn.edu/silver/)
- **JastAdd:** [http://jastadd.org/web/](http://jastadd.org/web/)

# Metalanguages

> Broadly, any metalanguage is language or symbols used when language itself is being discussed or examined. In logic and linguistics, a metalanguage is a language used to make statements about statements in another language (the object language). Expressions in a metalanguage are often distinguished from those in an object language by the use of italics, quotation marks, or writing on a separate line. The structure of sentences and phrases in a metalanguage can be described by a metasyntax. - [Wikipedia](https://en.wikipedia.org/wiki/Metalanguage)

## General purpose
- **Xtend:** [https://www.eclipse.org/xtend/](https://www.eclipse.org/xtend/)
- **Converge:** [https://convergepl.org/](https://convergepl.org/)
- **Kiama:** [https://wiki.mq.edu.au/display/plrg/Kiama](https://wiki.mq.edu.au/display/plrg/Kiama)

## Visual syntax

- **Sirius:** [https://www.eclipse.org/sirius/](https://www.eclipse.org/sirius/)

## Parser

- **Copper:** [http://melt.cs.umn.edu/copper/](http://melt.cs.umn.edu/copper/)
- **ANTLR4:** [https://www.antlr.org/](https://www.antlr.org/)

## Code Generation

- **Javapoet:** [https://github.com/square/javapoet](https://github.com/square/javapoet)
- **Epsilon EGL:** [https://www.eclipse.org/epsilon/doc/egl/](https://www.eclipse.org/epsilon/doc/egl/)
- **Acceleo:** [https://www.eclipse.org/acceleo/](https://www.eclipse.org/acceleo/)
 
## Syntax

- **Eclipse Modeling Framework (EMF):** [https://www.eclipse.org/modeling/emf/](https://www.eclipse.org/modeling/emf/)
- **Spoofax SDF3:** [http://www.metaborg.org/en/latest/source/langdev/meta/lang/sdf3/](http://www.metaborg.org/en/latest/source/langdev/meta/lang/sdf3/).

## Semantics

- **ALE:** [http://gemoc.org/ale-lang/](http://gemoc.org/ale-lang/)
- **Kermeta 3:** [http://diverse-project.github.io/k3/](http://diverse-project.github.io/k3/)
- **Spoofax DynSem:** [http://www.metaborg.org/en/latest/source/langdev/meta/lang/dynsem/index.html](http://www.metaborg.org/en/latest/source/langdev/meta/lang/dynsem/index.html) 
- **CBS (omponent-based specification of programming languages):** [https://plancomps.github.io/CBS-beta/](https://plancomps.github.io/CBS-beta/)


## Static semantics

- **Epsilon EVL:** [https://www.eclipse.org/epsilon/doc/evl/](https://www.eclipse.org/epsilon/doc/evl/)

## Model transformation

- **ALT:** [https://www.eclipse.org/atl/](https://www.eclipse.org/atl/)
- **ETL:** [https://www.eclipse.org/epsilon/doc/etl/](https://www.eclipse.org/epsilon/doc/etl/)

## Type system

- **Xsemantics:** [http://xsemantics.sourceforge.net/](http://xsemantics.sourceforge.net/)


# Books

- **The Software Languages Book - _Syntax, semantics, and metaprogramming_:**  [http://www.softlang.org/book](http://www.softlang.org/book)
- **Engineering Modeling Languages - _Turning Domain Knowledge Into Tools_**: [http://mdebook.irisa.fr/](http://mdebook.irisa.fr/)
- **DSL Engineering:** [http://dslbook.org/](http://dslbook.org/)
- **Language Implementation Patterns: Create Your Own Domain-Specific and General Programming Languages (Pragmatic Programmers)**
- **Compilers: Principles, Techniques, and Tools (2nd Edition)**
- **Principles of Software Language Design for Model-Driven Software Engineering**, Andrzej Wasowski and Thorsten Berger, *[Coming soon]* [https://mdsebook.bitbucket.io/](https://mdsebook.bitbucket.io/)
- **Compilers: Principles, Techniques, and Tools**, aka the Dragon book, Alfred V. Aho, Monica S. Lam, Ravi Sethi, and Jeffrey D. Ullman, [PDF](http://ce.sharif.edu/courses/94-95/1/ce414-2/resources/root/Text%20Books/Compiler%20Design/Alfred%20V.%20Aho,%20Monica%20S.%20Lam,%20Ravi%20Sethi,%20Jeffrey%20D.%20Ullman-Compilers%20-%20Principles,%20Techniques,%20and%20Tools-Pearson_Addison%20Wesley%20(2006).pdf)

# Blogs

- [https://languageengineering.io/](https://languageengineering.io/)
- [https://modeling-languages.com/](https://modeling-languages.com/)

# Talks

- [Domain Specific Languages in SPLE, Why and How?](http://www.voelter.de/data/presentations/splc2018-keynote.pdf), by [M. Völter](http://www.voelter.de/) at [SPLC'18](http://splc2018.net/)

**License**

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Manuel Leduc](///mleduc.xyz) has waived all copyright and related or neighboring rights to this work.
Title image [Designed by Freepik](http://www.freepik.com).
