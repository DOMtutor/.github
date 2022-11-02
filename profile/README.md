# DOMtutor

DOMtutor is a set of scripts used to leverage the competitive programming platform [DOMjudge](https://www.domjudge.org/).

## What is DOMjudge

In essence, DOMjudge allows participants to submit code solving specified problems.
Problems are formal descriptions of the desired output together with a time limit.
DOMjudge compiles submitted code and runs the executable in a sandboxed environment, checking only its input/output behaviour (and time/memory consumption).
As such, DOMjudge supports practically any programming language and thus typically evaluates efficiency and correctness, not soft constraints such as code style.

## What is DOMtutor

DOMtutor provides a lot of utilities around the DOMjudge system to ease usage in e.g. courses.
The scripts allow declarative definitions of users, courses, etc. and preparing all necessary data for a lecture (lecture slides, problem descriptions & solutions, DOMjudge contest, solution statistics, etc.) are "push button".
For example, after an initial setup, synchronizing the list of participants from moodle, creating and uploading all problems used for a lecture week, exporting grades of all participants to moodle, or even generating nice statistics for presentation can be done in an instant.

## How to Use DOMtutor

There is a dedicated [documentation repository](https://github.com/DOMtutor/documentation) that helps you get started and contains some samples.
