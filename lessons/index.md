---
path: "/intro"
title: "Introduction"
order: 0
---

## Welcome!

Design systems have been a passion of mine for the last couple of years so I'm thrilled to teach you this course.

You will learn many skills, some of which may be new and some of which you may have prior experience with. I will cover the pieces of each technology you need to know to complete this course, but this course will not be an in-depth tutorial for any one technology.

We will be coding in React, so it's recommended you have React knowledge prior to taking this course, but the rest of the skills we'll learn don't require prior experience.
`
Some of the topics and technologies we'll cover include:

- [Foundations of design systems](foundations-of-design-systems.md)
- [Foundations of design](foundations-of-design.md)
- [Designing with Figma](designing-with-figma.md)
- [Developing styled components](developing-styled-components.md)
- [Animating components with react-spring](animating-components.md)
- [Documenting components with Storybook](documenting-components-with-storybook.md)
- [Tooling & resources](tools-and-resources.md)

You should create an account on [Figma](https://www.figma.com/). This is where we'll be designing our color palette, typography, and components.

## About Me

I'm Emma Bostian, a Software Engineer at LogMeIn in Karlsruhe, Germany. Born and raised in Upstate New York, I graduated from Siena College in 2015 with a B.S. in Computer Science and moved down to Austin, Texas where I began my first full-time software job at IBM.

After three years with IBM I sold everything and moved to Germany where I've lived for the past two years.

In my spare time I do a multitude of fun activities. I am a co-host of the [Ladybug Podcast](https://www.ladybug.dev/) and panelist on [JS Party](https://changelog.com/jsparty). I write blogs for Ultimate Courses, Stack Overflow, and Dev. I create courses for LinkedIn Learning, Frontend Masters, and Egghead.io. And I speak at conferences!

If you have any questions during or after this course, feel free to contact me on Twitter @emmabostian.

## What This Course Is

This course is a high-level introduction to design systems. It will teach you the foundational skills your team needs to build a set of reusable components and standards.

## What This Course Is Not

This course is not a comprehensive overview to design systems. There is no industry-standard for what a design system truly is, and as a result it can be interpreted differently at different companies.

## Course Updates

If you find any mistakes, feel free to open a PR on the [course repository](https://github.com/emmabostian/fem-design-systems).

## Getting Started

If you'd like to view the working app, follow the steps below.

### Running the development server

1. Clone this repo `git clone https://github.com/emmabostian/fem-design-systems.git`
2. Install dependencies with `npm i`
3. Start the development server `npm start`

   \_If you hit a "path argument must be of type string" error during build, make sure `react-scripts` is version `3.4.0`, delete node_modules, and re-install dependencies with `npm i`. You can read more abou this error [here](https://github.com/facebook/create-react-app/issues/8490).

### Viewing the Storybook

To view the Storybook, you can run it locally with the following steps.

1. Clone this repo `git clone https://github.com/emmabostian/fem-design-systems.git`
2. Install dependencies with `npm i`
3. Start Storybook with `npm run storybook`.

You can also visit the Netlify site [here](https://fem-design-systems-storybook.netlify.com/?path=/story/buttons--primary).
