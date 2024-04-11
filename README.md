# Web Sustainability Guidelines (WSGs)

Welcome to the repository for the [Sustainable Web Design Community Group](https://www.w3.org/community/sustyweb/).

In this hub, you will find the draft specification for our [Web Sustainability Guidelines](https://w3c.github.io/sustyweb/) and any supplementary documentation, including [Sustainable Tooling And Reporting (STAR)](https://w3c.github.io/sustyweb/star.html), our [at-a-glance](https://w3c.github.io/sustyweb/glance.html) overview, our [introduction](https://w3c.github.io/sustyweb/intro.html) to Web Sustainability, our sustainability [laws & policies](https://w3c.github.io/sustyweb/drafts/policies.html) guide, our [quick reference](https://w3c.github.io/sustyweb/quickref.html) sheet, our [PDF checklist](https://w3c.github.io/sustyweb/checklist.pdf), our [JSON API](https://w3c.github.io/sustyweb/guidelines.json), and our [Test Suite](https://github.com/w3c/sustyweb/tree/main/test-suite). We also have a living implementation of the specification under active development called [Sustainable Web Design](https://sustainablewebdesign.org/).

If you would like a brief introduction to both our group and our specification, you may find [the slides](https://w3c.github.io/sustyweb/TPAC_Slides.pdf) from the presentation we gave at [TPAC 2023](https://www.w3.org/2023/09/breakouts/recording-32.html) useful. To learn more about our group, its goals, and our progress, check out our [wiki](https://www.w3.org/community/sustyweb/wiki/Main_Page), and [frequently asked questions](https://www.w3.org/community/sustyweb/wiki/Frequently_Asked_Questions) page. You may also find our draft [Working Group charter](https://w3c.github.io/sustyweb/wg/charter.html) of interest.

---

## Contributing

If you would like to contribute towards this specification, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) document for details. It contains detailed information on pull requests (PRs), submitting issues, and other methods of feedback in relation to this repository.

**Note:** Please make your pull requests (including any changes or edits) against files **ONLY** located within the "drafts" or "wg" folders.

---

## Living Drafts

Our publishing process has two channels.

The first channel is the **stable** specification which is versioned with all changes documented in the [release notes](https://github.com/w3c/sustyweb/releases). Links to the stable specification and its supplements can be found above (at the top of this README document).

The second channel is the **unstable** or living edition specification in which issue resolutions, pull requests, new supplements, and community edits are immediately available before that version is finalized. The "drafts" folder contains all of the living editions of the [specification](https://w3c.github.io/sustyweb/drafts/), [STAR](https://w3c.github.io/sustyweb/drafts/star.html), [at-a-glance](https://w3c.github.io/sustyweb/drafts/glance.html), [introduction](https://w3c.github.io/sustyweb/drafts/intro.html), [laws & policies](https://w3c.github.io/sustyweb/drafts/policies.html), [quick reference](https://w3c.github.io/sustyweb/drafts/quickref.html), [JSON API](https://w3c.github.io/sustyweb/drafts/guidelines.json), [Test Suite](https://github.com/w3c/sustyweb/tree/main/drafts/test-suite), and other supplements.

---

## JSON API

We have a [JSON API](https://w3c.github.io/sustyweb/guidelines.json) which is kept in sync with the changes occurring within our specification.

This document is reachable via GitHub pages and can be queried using JavaScript to embed our data within your client of choice.

The structure of the API is identical to that of the specification in its numbering scheme:

`category[1][0].guideline = "Undertake Systemic Impacts Mapping"`

---

## Test Suite

We have a [Test Suite](https://github.com/w3c/sustyweb/tree/main/test-suite) which is used to showcase machine testability (as denoted in [STAR](https://w3c.github.io/sustyweb/star.html)) for the Web Sustainability Guidelines (WSGs). The template structure for the file uses common W3C conventions for test cases to maintain interoperability for tooling that wishes to align our work with their own.

Key concepts of note include:
- Each title element contains a short identifier for the test.
- The rel="author" link element contains details of who created that test.
- The rel="help" link element links to the WSG guideline it relates to.
- The name="flags" meta element identifies any requirements the test may have such as an external file (**asset**), scripting (**JavaScript**), user-involvement (**interaction**), or if it's trying to disprove something (**invalid**).
- The name="assert" meta tag explains which **STAR** technique it relates to by title.
- The conditions of passing are what requirements are necessary to pass the technique (and thus the success criteria).