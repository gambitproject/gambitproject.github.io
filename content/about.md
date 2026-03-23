---
title: About Gambit
---



The principal developers of Gambit have been:

* [Theodore Turocy](http://www.gambit-project.org/turocy),
  University of East Anglia: director.

* Richard D. McKelvey, California Institute of Technology:
  project founder.

* Andrew McLennan, University of Queensland: co-PI during main
  development, developer and maintainer of polynomial-based algorithms
  for equilibrium computation.

Much of the development of the main Gambit codebase took place in
1994-1996, under a grant from the National Science Foundation to the
California Institute of Technology and the University of Minnesota
(McKelvey and McLennan, principal investigators).

Others contributing to the development and distribution of Gambit
include:

* Bernhard von Stengel provided advice on implementation of
  sequence form code, and contributed clique code

* Eugene Grayver developed the first version of the
  graphical user interface.

* Gary Wu implemented an early scripting language interface for
  Gambit (since superseded by the Python API).

* Stephen Kunath and Alessandro Andrioni did extensive work to create
  the first release of the Python API.

* From Gambit 14, Gambit contains support for Action Graph Games
  [Jiang11]_.  This has been contributed by Navin Bhat, Albert Jiang,
  Kevin Leyton-Brown, and David Thompson, with funding support
  provided by a University Graduate Fellowship of the University
  of British Columbia, the NSERC Canada Graduate Scholarship, and a
  Google Research Award to Leyton-Brown.


The Gambit Project was founded in the mid-1980s by Richard McKelvey at
the California Institute of Technology. The original implementation
was written in BASIC, with a simple graphical interface. This code was
ported to C around 1990 with the help of Bruce Bell, and was
distributed publicly as version 0.13 in 1991 and 1992.

A major step in the evolution of Gambit took place with the awarding
of the NSF grants in 1994, with McKelvey and Andrew McLennan as
principal investigators, and [Theodore Turocy](http://www.gambit-project.org/turocy) as the head programmer.
The grants sponsored a complete rewrite of Gambit in C++. The
graphical interface was made portable across platforms through the use
of the [wxWidgets library](http://www.wxwidgets.org). Version 0.94 of Gambit was released in
the late summer of 1994, version 0.96 followed in 1999, and version
0.97 in 2002. During this time, many students at Caltech and Minnesota
contributed to the effort by programming, testing, and/or documenting.
These include, alphabetically, Bruce Bell, Anand Chelian, Matthew
Derer, Nelson Escobar, Ben Freeman, Eugene Grayver, Todd Kaplan, Geoff
Matters, Brian Trotter, Michael Vanier, Roberto Weber, and Gary Wu.

Over the same period, Bernhard von Stengel, of the London School of
Economics, made significant contributions in the implementation of the
sequence form methods for two-player extensive games, and for
contributing his "clique" code for identification of equilibrium
components in two-player strategic games, as well as other advice
regarding Gambit's implementation and architecture.

Development since the mid-2000s has focused on two objectives. First,
the graphical interface was reimplemented and modernized, with the
goal of following good interaction design principles, especially in
regards to easing the learning curve for users new to Gambit and new
to game theory.  Second, the internal architecture of Gambit was
refactored to increase interoperability between the tools provided by
Gambit and those written independently.

Gambit is proud to have participated in the Google Summer of Code
program in the summers of 2011 and 2012 as a mentoring organization.
The Python API, which became part of Gambit from Gambit 13, was
developed during these summers, thanks in particular to the work
of Stephen Kunath and Alessandro Andrioni.
