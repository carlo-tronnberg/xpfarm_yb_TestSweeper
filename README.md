# xpfarm_yb_TestSweeper 
Testing integration with tracking tools in GitHub

---

# Deploy status Badge Service

![Run Tests](https://github.com/carlo-tronnberg/xpfarm_yb_TestSweeper/actions/workflows/main.yml/badge.svg)
[![Build Status](coverage/badge-branches.svg)](coverage/badge-branches.svg)
[![Build Status](coverage/badge-functions.svg)](coverage/badge-functions.svg)
[![Build Status](coverage/badge-lines.svg)](coverage/badge-lines.svg)
[![Build Status](coverage/badge-statements.svg)](coverage/badge-statements.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=bugs)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=carlo-tronnberg_xpfarm_yb_TestSweeper&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=carlo-tronnberg_xpfarm_yb_TestSweeper)
[![Open Issues](https://img.shields.io/github/issues/carlo-tronnberg/badge.svg)](https://github.com/carlo-tronnberg/xpfarm_yb_TestSweeper/issues)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![CodeScene Code Health](https://codescene.io/projects/20959/status-badges/code-health)](https://codescene.io/projects/20959)
[![CodeScene System Mastery](https://codescene.io/projects/20959/status-badges/system-mastery)](https://codescene.io/projects/20959)
[![CodeScene Missed Goals](https://codescene.io/projects/20959/status-badges/missed-goals)](https://codescene.io/projects/20959)

# Installation

To set up the project, you need node installed.

To install dependencies, run the following:

```sh
npm install
```

# Run the tests

To run the tests, there is a script in the project root called `test`. It calculates code coverage, incorporates
watch mode, and prints in verbose mode, so all test file's test report will be visible. Alternatively, you
can achieve the same with the command the script contains:

```sh
npm test -- --watchAll --collect-coverage --verbose
```

# Stories with few scenarios

# UAT Scenario

UAT description (what the user would accept)
The given name will be converted to a greeting format

## User story #1 - <Short description>

As a ... [context, who is the user, whom this story provides value for ]
I want to ... [steps]
So that ... [motivation, value]

- Scenario #1
  Given ...
  When ... (action you want to do)
  Then ...

- Scenario #2
  Given ...
  When ... (action you want to do)
  Then ...

