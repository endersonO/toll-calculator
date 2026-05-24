# 1. Project overview

This repository is a **technical assessment exercise** (code kata / take-home)
for an interview. The `README.md` describes an urban toll-fee calculator
for an unnamed city. The only locale signal in the assignment statement
is the currency: **fees in SEK**. The reference Java / C# code hard-codes
a 2013-specific holiday list whose dates match Swedish public holidays
(though the code never names a country or city).

## What the candidate must deliver

The candidate is expected to deliver an implementation — in the language of
their choice — via a fork + pull request. The existing C# and Java code is
provided as a **deliberately flawed reference**: the README hints at this
explicitly ("the last city-developer quit, claiming this solution is
production-ready").

## What the exercise really measures

This is not a clean starting base — it is a **critical-reading test**. The
interviewer is looking for the candidate's ability to:

- Detect the bugs that are obviously planted in the code.
- Restate the business rules in a clean implementation.
- Add tests that would have caught the bugs.
- Justify design decisions in the PR description.

## Headline numbers

| Metric                | Value                                    |
| --------------------- | ---------------------------------------- |
| Source files          | 9 (`.java` + `.cs`)                      |
| Lines of useful code  | ~210                                     |
| Test files            | 0                                        |
| Build files           | 0 (no `pom.xml`, `.csproj`, `Makefile`)  |
| Functional bugs found | At least 6 (see [04-bugs.md](04-bugs.md))|
