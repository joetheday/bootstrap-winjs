# Winstrap
Winstrap is the Bootstrap theme for Microsoft Design Language

Winstrap is an open source expression of the Bootstrap web framework, which has been re-skinned to match Microsoft's design language. Created by Microsoft’s Web Services design developers, Winstrap’s vision is to provide key components themed for use across Microsoft sites while preserving the Bootstrap foundation as much as possible.

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
* Include one space after `:` for each declaration.
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

#### Comments
The liberal use of comments is appreciated. Good comments should give the reader context and an understanding of why code is written in a certain way. Don’t just repeat the class name or explain things that are obvious from looking at the code. Follow these formatting guidelines for comments:
* Understand the difference between `/* CSS style comments */` and `// SASS style comments`.
```
/* Use CSS style comments like this, only if you want the comment to appear in the compiled CSS */
// Otherwise use SASS style that will not appear in the compiled CSS
```
* Separate your code into sections with comments in this style
```
//
// Color Themes
//
```
* For very long comments, it’s acceptable to break the comment onto multiple lines.
```
// This is a very long comment that gives a lot of important
// details about the nuances of this code
```