# Hi, I'm Lennox

Software engineer. BA in Computer Science and a Minor in Data Analytics, May 2026. Based in Moorhead, MN; open to relocation.

I build systems that hold up under real-world pressure: simulations of safety-critical systems, full-stack web apps for real client organizations and statistical analyses. My instinct is to make the test pass, then make the system explain itself to the next person who reads it.

## What draws me

I gravitate to problems where correctness is not optional: systems that fail loudly and expensively when they are wrong. That runs from safety-critical and embedded software through distributed systems, security, and the cryptography-and-money problems in DeFi. What ties them together is the engineering discipline they all demand.

## How I work

I write tests as design specifications. The Star Wars project has 16 JUnit tests that document not just what the code does, but what it refuses to do.

I read failure modes before I write code. On the RailGuard railway-crossing simulation I produced a Fault Tree Analysis on the "Gate Open" failure mode and used it to drive requirements, well before any state machine took shape.

I write code that explains itself, and documentation that points to the code's actual behavior. Two of my data-analysis repos render their full findings as live GitHub Pages so a reader can read the work without cloning anything.

I cite the numbers I claim. When I say a regression model explains 49.6% of state-level variance in fatality risk, that exact figure is in the rendered notebook one click away.

## Featured Work

### [project-railguard](https://github.com/Lennox7384/project-railguard)
Safety-critical railway-crossing simulation. Boolean state machine, Fault Tree Analysis driving the requirements, React 19 + Vite + vitest. Built as a team project; I owned the hazard-analysis track end to end.

### [entrepreneurship-club-website](https://github.com/Lennox7384/entrepreneurship-club-website)
Full-stack PHP/MySQL website I built with a four-person team for a real student-run client organization. Public pages plus a back-of-house admin panel for event and member management. I owned the Schedule (events) feature end to end.

### [data318-modeling](https://github.com/Lennox7384/data318-modeling)
Predicting county-level small-business formation rates across all 3,069 US counties from six ACS demographic and economic predictors. R + Rmarkdown, three model families compared on a held-out test split, full report rendered to [GitHub Pages](https://lennox7384.github.io/data318-modeling/03_report.html).

### [motor-vehicle-fatality-analysis](https://github.com/Lennox7384/motor-vehicle-fatality-analysis)
A Python port of a 2023 state-level statistical analysis on what predicts motor-vehicle fatality risk across US states. pandas, statsmodels, matplotlib, scipy. Joint OLS regression hits R² = 0.4959. Full rendered analysis at [GitHub Pages](https://lennox7384.github.io/motor-vehicle-fatality-analysis/analysis.html).

### [nlp-module](https://github.com/Lennox7384/nlp-module)
A natural-language-processing component designed as the text-handling bridge in a multi-module AI pipeline. Four public functions, NLTK VADER under the hood, JSON envelope as the stable contract between this module and three downstream consumers. Pytest suite covers eight scenarios.

### [star-wars-characters-simulation](https://github.com/Lennox7384/star-wars-characters-simulation)
Java OOP exercise built around two domain classes with a 16-test JUnit suite. Boundary-validation tests pin the contract on `Force.setStrength` (1 to 100); fight outcomes are verified through stream-redirected console output.

## Stack

**Languages:** Java, JavaScript, Python, PHP, R, SQL  
**Web:** React 19, Vite, vanilla HTML/CSS/JS, Bootstrap Icons  
**Data:** pandas, statsmodels, scipy, matplotlib, Rmarkdown, tidyverse  
**Java tooling:** Maven, JUnit 4, Swing  
**Testing:** JUnit, pytest, vitest  
**Practice:** Fault Tree Analysis, Waterfall + iterative lifecycles, MariaDB / MySQL administration, reproducible analysis pipelines

## Get in touch

- LinkedIn: [linkedin.com/in/lennox-m-638b0a237](https://www.linkedin.com/in/lennox-m-638b0a237)
- Email: lennox49magak@outlook.com

I respond fast. If you're hiring for a role where engineering rigor matters more than the language on the JD, send a note.
