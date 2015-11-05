# Winstrap
Winstrap is the Bootstrap theme for Microsoft Design Language

The vision of Winstrap is to offer an official expression of the Microsoft Design Language for Bootstrap. In general we seek to  theme Bootstrap, rather than add to it things that it doesn't already contain. In some few exceptions we may add things that Bootstrap doesn't have (like our Progress ring, for example) in order to provide important components that would be used on any Microsoft site on the internet. The vision is to remain as close to Bootstrap as possible.

## How to contribute
There are many ways that you can contribute to the Winstrap project:
* Submit a bug
* Verify fixes for bugs
* Submit a code fix for a bug
* Submit a feature request
* Tell others about the Winstrap project
* Tell the developers how much you appreciate the project

#### Contributing Code
Note that all code submissions will be rigorously reviewed and tested by the team, and only those that meet a high bar for both quality, code standards (see below), and vision appropriateness will be merged into the source.

##### Keep it positive!
In short, be helpful and don't be mean! Have a sense of humor and don't take yourself too seriously. We want to promote an environment of inclusiveness and fun. When offering feedback, keep your comments positive, to the point, and instructional. Here's a great example of [what not to do](http://lkml.iu.edu/hypermail/linux/kernel/1510.3/02866.html) and [how it could have been done better](http://catcode.com/comments/2015/cf20151101.html).

#### Pull Requests
You will need to sign a [Contribution License Agreement](https://cla.microsoft.com/) ([CLA](https://cla.microsoft.com/)) before submitting your pull request be it a feature or a bug fix. To complete the CLA, you will need to submit the request via the form and then electronically sign the CLA when you receive the email containing the link to the document.

This needs to only be done once for any Microsoft open source project.

#### Feature Requests
Before submitting a feature or substantial code contribution please discuss it with the team and ensure it aligns with the project's vision.

#### Contributing to README and Wiki
You do not need to sign a Contribution License Agreement if you are just contributing to the README or the Wiki. By submitting a contribution to the README or the Wiki, you are cntributing it under the [Creative Commons CC0 1.0 Universal Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/).

## Code standards
These are adapted from [@mdo](http://twitter.com/mdo)'s [codeguide.co](http://codeguide.co/) and tweaked to suit our project.

#### General Guidelines
* Be clear and as concise as possible
* Avoid unnecessary or unclear abbreviations
* Opt-in is better than opt-out. Most often this means using classes instead of styling HTML tags, but will apply in other scenarios as well. Give the user control, don't make them do gymnastics to opt-out if they need to.

#### HTML
* Use soft tabs with four spaces
* Nested elements should be indented once (four spaces).
* Always use double quotes, never single quotes, on attributes.
* Don't include a trailing slash in self-closing elements—the HTML5 spec says they're optional.
* Don’t omit optional closing tags (e.g. `</li>` or `</body>`).

#### CSS
* Use soft tabs with four spaces
* When grouping selectors, use one line for each.
* Include one space before the opening brace of declaration blocks for legibility.
* Place closing braces of declaration blocks on a new line.
* Include one space after : for each declaration.
* Each declaration should appear on its own line for more accurate error reporting.
* End all declarations with a semi-colon. The last declaration's is optional, but your code is more error prone without it.
* Comma-separated property values should include a space after each comma (e.g., `box-shadow`).
* Don't include spaces after commas within `rgb()`, `rgba()`, `hsl()`, `hsla()`, or `rect()` values. This helps differentiate multiple color values (comma, no space) from multiple property values (comma with space).
* Don't prefix property values or color parameters with a leading zero (e.g., .5 instead of 0.5 and -.5px instead of -0.5px).
* Lowercase all hex values, e.g., `#fff`. Lowercase letters are much easier to discern when scanning a document as they tend to have more unique shapes.
* Use shorthand hex values where available, e.g., `#fff` instead of `#ffffff`.
* Quote attribute values in selectors, e.g., `input[type="text"]`. They’re only optional in some cases, and it’s a good practice for consistency.
* Avoid specifying units for zero values, e.g., `margin: 0;` instead of `margin: 0px;`
* Use unitless line-height, e.g., `line-height: 1.2;` istead of `line-height: 1.2px;`
