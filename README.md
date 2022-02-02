# Website of the Software Engineering Research Group (SERG)

[![Netlify Status](https://api.netlify.com/api/v1/badges/d2db141e-55bd-44d9-a61e-95a49e6558c7/deploy-status)](https://app.netlify.com/sites/serg/deploys)
![Security Headers](https://img.shields.io/security-headers?url=https%3A%2F%2Fserg.ewi.tudelft.nl)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fserg.ewi.tudelft.nl)

> This is a WIP revamp of our existing website

This repo contains the sources of the Software Engineering Research Group (SERG) website.
The website is built on top of the popular open-source static site generator [Hugo](https://gohugo.io/) and makes use of the [Wowchemy](https://wowchemy.com/) framework.
The [Netlify](https://gohugo.io/) service is used to host the website.

## Adding material

Material can be added by anyone in any section.
For adding material, check [this documentation](https://wowchemy.com/docs/).

**Note:** Do not directly push your changes to the main branch. Instead, send a Pull Request (PR).

### Group members

Group members include current staff, alumni, and students (MSc and BSc thesis).

To add these members follow the following steps:

1. Run `hugo new --kind authors authors/<firstname-lastname>`, which copies the template from archetypes or copy one of the existing author profiles
2. Update the information about the member in **content/authors/<firstname-lastname>/_index.md**
3. Replace **avatar.{jpg,jpeg,png,webp}** with the photo of the member
4. Add something about the member below the front matter

When a member leaves the group, they will be turned into an alumni by adding the year that they left to the **member_end** property.

### Research lines

Research lines are the more general topics that the group works on.
All content (e.g., funded projects, publications, events, vacancies) links to these research lines.

To add a new research line follow the following steps:

1. Run `hugo new --kind research_line research_line/<identifier>`, which copies the template from archetypes or copy one of the existing research lines
2. Update the information about the line of research in **content/research_line/<identifier>/_index.md**
3. Add information about the research line below the front matter
4. Link all related content to the research line by using the identifier

### Projects

Projects are the funded projects, where researchers work on achieving a certain goal.

To add a new project follow the following steps:

1. Run `hugo new --kind project project/<identifier>`, which copies the template from archetypes or copy one of the existing projects
2. Update the information (e.g., the research line to which it belongs) about the project in **content/project/<identifier>/_index.md**
3. Add information about the project below the front matter

### Publications

To add a new publication follow the following steps:

1. Run `hugo new --kind publication publication/<identifier>`, which copies the template from archetypes or copy one of the existing publications
2. Update the information (e.g., the research line to which it belongs) about the publication in **content/publication/<identifier>/_index.md**
3. Add information about the publication below the front matter

### Tools

To add a new tool follow the following steps:

1. Run `hugo new --kind tool tool/<identifier>`, which copies the template from archetypes or copy one of the existing tools
2. Update the information (e.g., the research line to which it belongs) about the tool in **content/tool/<identifier>/_index.md**
3. Add information about the tool below the front matter

### Events

To add a new event follow the following steps:

1. Run `hugo new --kind event event/<identifier>`, which copies the template from archetypes or copy one of the existing events
2. Update the information (e.g., the research line to which it belongs) about the event in **content/event/<identifier>/_index.md**
3. Add information about the event below the front matter

### Vacancies

To add a new vacancy follow the following steps:

1. Run `hugo new --kind vacancy vacancy/<identifier>`, which copies the template from archetypes or copy one of the existing vacancies
2. Update the information (e.g., the research line to which it belongs) about the vacancy in **content/vacancy/<identifier>/_index.md**
3. Add information about the vacancy below the front matter

## Build and preview locally

When making changes to the website, it is useful to build and preview the website locally before committing the changes to the repository.
Before you can build the website, you first need to install the following dependencies:

1. Install Hugo using [this documentation](https://gohugo.io/getting-started/installing/).
2. Install NPM using [this documentation](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

To preview the website:

1. Run `view.sh`

When an error occurs during building, try deleting the local Hugo cache:

- MacOS/Linux: `sudo rm -rf $TMPDIR/hugo_cache/`

## Deploy website

The website is automatically deployed whenever a new commit is merged into the main branch.
To see a preview of the changes in a PR, press the details link in the deploy status check.
