# Contributing

This repository is being used for work in the **W3C Sustainable Web Design Community Group**, governed by the [W3C Community License
Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/). To make substantive contributions,
you must join the [CG](https://www.w3.org/community/sustyweb/).

## Overview

This repository is used to develop content for the Web Sustainability Guidelines (WSGs), as well as any supplementary documents.

## File Structure

The structure of the repository has been created to ensure ease of maintenance. The base directory contains all of the compiled files that are public facing such as the specification, supplementary documents, the JSON API, and other materials. The "drafts" folder contains all of the pre-exported W3C ReSpec sources including the living [specification](https://w3c.github.io/sustyweb/), [at-a-glance](https://w3c.github.io/sustyweb/glance.html), [quick reference](https://w3c.github.io/sustyweb/quickref.html), [introduction](https://w3c.github.io/sustyweb/intro.html), [JSON API](https://w3c.github.io/sustyweb/guidelines.json) and other supplements.

```

/wg/charter.html			-  	    - Working Group Draft Charter
/drafts/checklist.pages			-  	    - PDF Checklist (Source)
/drafts/glance.html			-  	    - At-A-Glance (Source)
/drafts/guidelines.json			-  	    - WSG JSON API (Source)
/drafts/index.html			-  	    - WSG Specification (Source)
/drafts/intro.html			-  	    - Introduction (Source)
/drafts/quickref.html			-  	    - Quick Reference (Source)

checklist.pdf				- READ ONLY - PDF Checklist (Public)
glance.html				- READ ONLY - At-A-Glance (Public)
guidelines.json				- READ ONLY - WSG JSON API (Public)
index.html				- READ ONLY - WSG Specification (Public)
intro.html				- READ ONLY - Introduction (Public)
quickref.html				- READ ONLY - Quick Reference (Public)
TPAC_Slides.pdf				- READ ONLY - W3C TPAC Slides
Web_Sustainability_GRI_Impact_est.ipynb	- READ ONLY - GRI Impact Calculator
```

When you contribute to our repo, you **MUST** only make changes to documents within the "drafts" or "wg" folders (the sources). Once a PR submission has been reviewed by our group (for quality control purposes), it will either be accepted, or rejected, or further discussion will be required (an issue can be raised for example). Once a PR has been accepted it will be visible within the living draft documents immediately. When enough issues have been collated to warrant a release publication, the necessary documents will be exported through ReSpec into their final form and will be versioned as the next public release.

You will notice duplication within the content of our work (as the JSON API for example must reflect the specification). This work is not auto-generated so while we appreciate it if individuals choose to make adjustments to all affected files as required, time commitments may not allow for everyone to do so. As such, if you can only update a single document, as part of the approval process, a moderator (lead or chair) will update all necessary documents to ensure parity with your change.

## Pull Requests

If you would like to contribute towards this specification, our primary method is through Pull Requests (PRs).

If you are not the sole contributor to a contribution (pull request), please identify all
contributors in the pull request comment.

To add a contributor (other than yourself, that's automatic), mark them one per line as follows:

```
+@github_username
```

If you added a contributor by mistake, you can remove them in a comment with:

```
-@github_username
```

If you are making a pull request on behalf of someone else but you had no part in designing the
feature, you can remove yourself with the above syntax.

## Issues

If you cannot submit a pull request, or if you cannot provide a direct solution, the preferred method is to create a [new issue](https://github.com/w3c/sustyweb/issues) with your comments. You could provide comments on technical errors (bugs) you have uncovered, new guidelines or success criteria you believe should be added, questions you have about existing or future content or an idea for a direction or feature we could utilize.

Please check that your question hasn't already been posted first, and provide as much detail as possible (if you have a solution or content to add, it would be very helpful). We're all volunteers so please keep this in mind and try to be civil when commenting about our work.

If filing issues in GitHub is not feasible, email our open discussion group [public-sustyweb@w3.org](public-sustyweb@w3.org) ([comment archive](https://lists.w3.org/Archives/Public/public-sustyweb/)).

## Credit

All contributors will receive credit (in the specification and our GitHub release notes) if their feedback and ideas make it into the document. Certain exclusions will apply such as those who do not provide their full names or those whose feedback is deemed as invalid, duplicate, or general questions that don't add to the specification or its supplements.
