# Computer Science for JavaScript: Regex Tutorial

## GIST LINK
[RegEx_Tutorial_By_DNB.md](https://gist.github.com/DionneNoellaBarretto/881ee7f86ebf69d6caab8762e757fef9) <br>
[Repo ReadMe](https://dionnenoellabarretto.github.io/16-Regex_Tutorial_Gist/)

## Task

Developers write code, but they also *write about code*. Our assignment this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. We'll use the template provided in the starter code to create our walkthrough.

## User Story

```md
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```

## Acceptance Criteria

```
GIVEN a regex tutorial
✓ WHEN I open the tutorial THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile

✓ WHEN I click on the links in the table of contents THEN I am taken to the corresponding sections of the tutorial

✓ WHEN I read through each section of the tutorial THEN I find a detailed explanation of what a specific component of the regex does

✓ WHEN I reach the end of the tutorial THEN I find a section about the author and a link to the author’s GitHub profile
```

## Getting Started

Instead of creating a repository, a GitHub gist was published. GitHub describes a **gist** as a simple way to share code snippets with others. It’s also an ideal way to demonstrate a technique, teach a principle, or show off a solution. It functions just like a repository, and you’ll use Markdown to create it, just as you do with your READMEs. Gists can include code, images, links, and anything else you can include in a README.

## Useful Links:
👉[how to create a gist](https://help.github.com/en/github/writing-on-github/creating-gists)

👉[video on how to use gists](https://www.youtube.com/watch?v=wc2NlcWjQHw).

The starter code is a template with a title, introductory paragraph, summary, and table of contents. The table of contents should link to sections of the tutorial that describe the functionality of each component in the regex. Be sure to rename the template to a unique name that describes your tutorial.

## What Is a Regex?

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. 

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.


👉 Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

👉 Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

👉 Matching a URL: `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

👉 Matching an HTML Tag: `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`


## Grading Requirements

This homework is graded based on the following criteria:

### Deliverables: 30%
```
✅ A valid URL of your GitHub gist.
✅ Your GitHub gist that contains the tutorial Markdown.
```
### Technical Acceptance Criteria: 50%

Satisfies all of the above acceptance criteria plus the following:
```
✅ Revisions to the tutorial must be made in the GitHub gist UI so that graders have access to your revision history.
✅ The tutorial must cover one of the regex examples listed above or another of your choice. You may NOT use the regex covered in the [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial).
✅ The tutorial must include sections that correspond to each of the components that make up the regex. You may not need to use all of the sections included in the starter code, but you should include all of the sections that correspond to the different components of the regex you chose.
✅ Each section that describes a component must include more than just one sentence explaining what it does. It’s okay to use online resources for assistance, but do not copy and paste; explain each component in your own words and be thorough.
✅ Each section that describes a component must include a code snippet of that particular component. Use backticks to display your code snippets in Markdown.
✅ Each section that describes a component must include at least one example that meets the requirements of that component.
```
### Tutorial Clarity and Quality: 20%
```
✅ Tutorial provides a clear explanation of how the regex works. Be as concise as possible.
✅ Tutorial describes each regex component in a separate section.
```
