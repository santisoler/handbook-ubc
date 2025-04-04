# Handbook for Summer Research Project at UBC

## About

This handbook sets the expectations and describe the research culture and
atmosphere that I, Santiago Soler, want to create when mentoring summer research
projects in the Geophysical Inversion Facility, in the [Earth, Ocean and
Atmospheric Sciences][eoas], [UBC][ubc], under the supervision of [Lindsey
Heagy][lindsey].

The main motivation for writing this handbook comes from my personal experience
of doing a PhD as a member of the [Computer-Oriented Geoscience
Lab][compgeolab] and being exposed to its [Manual][compgeolab-manual], created
by [Leonardo Uieda][leouieda]. The benefits of having a handbook inside
research labs is also documented in scientific articles ([The WIN Handbook
Team, 2023][win-handbook-2023]) that recommend it as a best practice.

This handbook is intended to be a live document, so if you think there's
anything that should be fixed or modified, if there's anything missing you
would like to add, or if there's anything you don't agree and would like to
discuss, please don't hesitate to [open an Issue][issue-docs] or a [Pull
Request][pr-docs] to start the conversation and/or make a suggestion.

## Content

* [Code of Conduct](#code-of-conduct)
* [Expectations](#expectations)
  * [Expectations of Summer Researchers](#expectations-of-summer-researchers)
  * [What can you expect from Santi](#what-can-you-expect-from-santi)
* [Open Science](#open-science)
  * [General guidelines on openness](#general-guidelines-on-openness)
  * [Research ethics](#research-ethics)
  * [Data and code availability](#data-and-code-availability)
  * [Use of generative AI tools](#use-of-generative-ai-tools)
* [Health and well-being](#health-and-well-being)
* [Links to Resources](#links-to-resources)
  * [Learning material](#learning-material)
  * [Software tools](#software-tools)
* [Credit and terms of reuse](#credit-and-terms-of-reuse)
* [References](#references)


## Code of Conduct

Summer researchers must follow [UBC's Student code of conduct][ubc-student-coc]
and the [EOAS Code of Conduct][eoas-coc]. Any violation of these Code of
Conducts can be reported to [Santiago Soler](mailto:ssoler@eoas.ubc.ca),
[Lindsey Heagy](mailto:lheagy@eoas.ubc.ca) or using the appointed channels for
reporting unacceptable behaviours.

When interacting with open-source software communities, either in person or
online, summer researchers are required to also follow the communities' code of
conduct.
For example, when interacting with communities like [SimPEG][simpeg] or
[Fatiando a Terra][fatiando] by asking questions in their communication
channels, opening issues or pull request, etc., one needs to adhere to their
corresponding code of conducts ([SimPEG's COC][simpeg-coc], [Fatiando's
COC][fatiando-coc]).

## Expectations

We intend to create a **healthy and collegial research atmosphere** that
incentivize close collaboration, curiosity, personal and professional
development. In such atmosphere, not knowing something should be seen as an
opportunity to learn something new, or to research and generate new knowledge
that can be shared with others.

### Expectations of Summer Researchers

A large part of fostering a healthy work environment is taking care of our
mental well-being. Summer researchers are **not expected to sacrifice personal
or leisure time** in service of projects. Working long hours without
interruption can lead to burnout, exhaustion, and overall impedes the type of
atmosphere we are trying to develop.

As a summer researcher, Santi expects you to:

* Follow the [Code of Conduct](#code-of-conduct) and general [Open
  Science](#open-science) guidelines.
* **Be proactive** in communicating your needs and desires (guidance,
  equipment, personal time, career plans, etc).
* **Be present** and work regularly in your project. Such projects can offer
  certain level of flexibility, like working remotely, and organize your
  working hours. Let Santi know when you are changing your schedule, or if you
  decide to work remotely.
* **Maintain a healthy, constructive, and positive atmosphere** with the rest of
  the Group and Department.
* **Be curious** and self-motivated about your project. Find and read the
  articles you need to enlarge your knowledge, wrestle with a problem to find
  your own solution to it, write your own code.
* **Take the initiative** with your project goals and tasks. Santi will help
  you get started and accompany you during the project, but don't wait for his
  instructions to keep working on it.

### What can you expect from Santi

Mentoring is a two-way relationship. These are things that you expect from
Santi:

* **Lead** and set directions for the project directions.
* Prioritize and **support your career** progression and well-being, providing
  the required training and resources for your particular needs.
* Be willing to **listen to criticism** and suggestions for improvement.
* Adjust **the style of mentorship** to what works best for you (please let him
  know if something isn't working well).
* **Respond to your messages** and requests within a reasonable time, which can
  be within the same day or up to 4 working days, depending on urgency and
  Santi's schedule.
* **Respect your personal time** and not ask for things to be done during
  evenings, weekends, holidays, and vacation time.
  In case you receive a message from Santi within these times, you have no
  obligation to respond during your personal time.

## Open Science

Summer research projects with Santi will have an **open-by-default policy**,
meaning that we assume that software and data will be made openly available
under permissive licenses (CC-BY, MIT, BSD, etc.) unless there is a very good
reason not to (like PII or other restrictions).

### General guidelines on openness

* Work on software should be conducted in **public repositories**.
* Research repositories that are intended to be published may be held back as
  private until time of first submission, when they **must be made public for
  peer-review**.
* Because most repositories will be made publicly accessible, including their
  entire history, summer researchers are required to **behave professionally**
  in them (including commit messages, issues, pull requests, code comments,
  etc).
* Many journals consider the content of referee reports to be confidential.
  Unless the report is explicitly open, it **should not be added** to
  repositories as text, commit messages, or comments in papers.

### Research ethics

Our actions should be guided by the ethics of participating in the global
scientific community. This means:

* Provide **citations to all software** that assisted in the development of the
  scholarly work. In general it is acceptable to cite the layers of software in
  the analysis stack (e.g., NumPy, Matplotlib, IPython/Jupyter, SimPEG,
  Fatiando, etc.)
* Provide citations to data sources
  ([DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)s and
  publications) wherever possible, and where not possible, should be included
  as footnotes.
* Plagiarism is unacceptable in any form. This includes "first pass" text
  included in documents. If including text from an external source, it must be
  clearly marked as such to ensure it is not accidentally included in the final
  product.

### Data and code availability

* All **data and models** generated during the project will be made available in
  both raw and processed forms under CC0 or CC-BY licenses.
* All **software** will be made available in source form under permissive,
  MIT or BSD-style licenses, unless constrained by external copyleft licensing.
* Source code will be made publicly available on GitHub (or similar), with
  additional archives on longer-term preservation platforms like
  [figshare][figshare] or [Zenodo][zenodo].

### Use of generative AI tools

The type of research culture that Santi wants to create for this project
_"appreciates the intangible benefits of human to human, and human to natural
world(s) interaction when pursuing automated methods and artificial
intelligence"_ (adapted from [Azari Research Group's Community
Goals][abbys-research-group-goals]).

The usage of generative AI tools for producing text, code and figures is not
prohibited, although Santiago doesn't encourage it. In case these tools are
being used, one must ensure that:

* The output produced by the tool is **scientifically correct**.
* You have a strong understanding of the suggested output or solution. For
  example, if code is returned by a generative AI tool, make sure you
  understand the totality of the syntax, that you are familiar with all
  libraries, classes, functions and methods used in the code, and you
  understand not only why the suggested solution works, but also in which cases
  it doesn't.
* The output produced by a generative AI tool is not a copy that might lead to
  violation of its license.
  For example, if some code generated by a generative AI tool is significantly
  similar to a code that belongs to a third-party library.
  If it is a copy, make sure you have permission to reuse it (read its
  license), and you comply with its license (e.g provide attribution if
  required, etc.).

If any of the previous requirements isn't met, the use of the generated output
should be seriously considered, and its consequences understood (scientifically
incorrect statements, mislearning fundamental topics, plagiarism, etc.).

Usage of generative AI tools **while learning is strongly discouraged**.
Quoting [Lee et al. (2025)][lee-2025]:

> \[...\] while GenAI can improve worker efficiency, it can inhibit critical
> engagement with work and can potentially lead to long-term overreliance on
> the tool and diminished skill for independent problem-solving. Higher
> confidence in GenAI's ability to perform a task is related to less critical
> thinking effort.

Critical thinking is a fundamental part of any learning process, and a backbone
characteristic of the research culture that Santiago wants to create during the
project.

> [!TIP]
> Don't miss the opportunity of learning something new by wrestling with
> a problem on your own. If you cannot solve it, learning from someone else's
> experience will probably be the most effective way of making your way through
> the problem.


## Health and well-being

> [!IMPORTANT]
> Your first priority should always be your own health, safety, and well-being.
> No project, paper, grant, or collaboration is more important than that.

Health resources in UBC:

* [UBC's Health and wellbeing](https://students.ubc.ca/health)
* [UBC's Counselling services](https://students.ubc.ca/health/counselling-services/)

## Links to Resources

Here's a list of online resources and software tools that might come handy when
working in your project:

### Learning material

* [Software Carpentry lessons](https://software-carpentry.org/lessons/).
* [Scientific Python](https://scientific-python.org/)
* [pyOpenSci](https://www.pyopensci.org/)

### Software tools

Text editors and IDEs:

* [VSCodium](https://vscodium.com/): community-driven, freely-licensed binary
  distribution of Microsoft’s editor VS Code. All the good things about VSCode,
  but fully open source and without Microsoft telemetry.
* [Neovim](https://neovim.io/): highly customizable text editor based on Vim.

Python:

* [Miniforge](https://github.com/conda-forge/miniforge): a conda-forge
  distribution (alternative to Anaconda, useful if we don’t desire to agree
  with the [Anaconda
  TOS](https://www.anaconda.com/pricing/terms-of-service-faqs)).
* [Ruff](https://astral.sh/ruff): a fast Python
  [linter](https://en.wikipedia.org/wiki/Lint_(software)).
  [Scientific Python has a great Ruff configuration
  template](https://learn.scientific-python.org/development/guides/style/#ruff)
  that works great for most situations.

Note taking and bibliography management:

* [Zotero](https://www.zotero.org/): an excellent bibliography management
  system. Great to organize your bibliography, highlight and annotate the
  papers you read. Zotero offers sync features so you can access your database
  across devices.
* [Joplin](https://joplinapp.org/): open-source, privacy-oriented note taking
  app that uses Markdown and offers sync between devices.

Find more resources in the [Links to
resources](https://www.compgeolab.org/manual/resources.html) section in
Compgeolab's Manual.

## Credit and terms of reuse

This handbook has been created in 2025 by [Santiago Soler][santisoler] and is
available under the Creative Commons Attribution 4.0 International (CC BY 4.0)
license.

It is based on the [Compgeolab's Manual][compgeolab-manual] created
by [Leonardo Uieda][leouieda] and made it available under the Creative Commons
Attribution 4.0 International (CC BY 4.0) license, and on
[Azari Research Group's Community Goals][abbys-research-group-goals] written by
[Abby Azari][abby].

## References

- Benjamin C Tendler, Maddie Welland, Karla L. Miller, The WIN Handbook Team (2023)
  Research Culture: Why every lab needs a handbook eLife 12:e88853.
  doi: [10.7554/eLife.88853][win-handbook-2023]
- Hao-Ping (Hank) Lee, Advait Sarkar, Lev Tankelevitch, Ian Drosos, Sean
  Rintel, Richard Banks, Nicholas Wilson (2025). The Impact of Generative AI on
  Critical Thinking: Self-Reported Reductions in Cognitive Effort and
  Confidence Effects From a Survey of Knowledge Workers.
  https://www.microsoft.com/en-us/research/wp-content/uploads/2025/01/lee_2025_ai_critical_thinking_survey.pdf


[win-handbook-2023]: https://doi.org/10.7554/eLife.88853
[lee-2025]: https://www.microsoft.com/en-us/research/wp-content/uploads/2025/01/lee_2025_ai_critical_thinking_survey.pdf

[santisoler]: https://www.santisoler.com
[lindsey]: https://lindseyjh.ca
[compgeolab]: https://www.compgeolab.org
[compgeolab-manual]: https://www.compgeolab.org/manual
[eoas]: https://www.eoas.ubc.ca
[ubc]: https://www.ubc.ca
[abby]: https://abbyazari.github.io
[abbys-research-group-goals]: https://abbyazari.github.io/goals
[leouieda]: https://www.leouieda.com
[issue-docs]: https://docs.github.com/en/issues/tracking-your-work-with-issues/configuring-issues/quickstart
[pr-docs]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request
[ubc-student-coc]: https://students.ubc.ca/campus-life/student-code-conduct/
[eoas-coc]: https://www.eoas.ubc.ca/edi-and-safety/eoas-code-of-conduct
[fatiando]: https://www.fatiando.org
[simpeg]: https://simpeg.xyz
[fatiando-coc]: https://github.com/fatiando/community/blob/main/CODE_OF_CONDUCT.md
[simpeg-coc]: https://github.com/simpeg/simpeg/blob/main/CODE_OF_CONDUCT.md
[figshare]: https://figshare.com
[zenodo]: https://zenodo.org
