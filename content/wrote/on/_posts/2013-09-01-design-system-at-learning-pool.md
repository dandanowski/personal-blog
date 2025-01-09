---
layout: post
title: Wrangling 300+ themes for an LMS
subtitle: Design system at Learning Pool
permalink: /s/case-study/design-system-at-learning-pool
className: case-study
tags:
    - Case study
    - Design system
---

Theme deployment and maintenance was drastically improved by moving theme settings to an indepedent repository. Further process automations provided reduced bug and feature request times.

When I started at [Learning Pool](https://learningpool.com), there were roughly over 200 [Moodle](https://moodle.org/) instances, one for each of our customers. Each instance was a separate code structure and each were manually maintained, core codebase, custom features and themes alike. I lead the initiative to automate the maintenance and deployment of themes across all instances. This opportunity was made possible during an effort by the developer to dramatically reduce the number of instances that were being supported by serving multiple sites off of the same codebase.

The process evolved into a dedicated database that stored the theme settings, precursor to design tokens, for all our brands as well as custom scripts that was able to spin up a local instance of the latest Moodle code with our customizations, the preivous day's data backup as well as the theme data from the theme database. This was necessary to both create and deploy new themes as well as address any theme related bugs quickly and confidently.

Advanced themes were also supported by injecting custom CSS and images into the same Moodle theme layer.

When I finished up at Learning Pool in 2013, the number of supported instances had grown to over 300.

![Moodle themes settings page](/assets/case-study/moodle-theme-settings-general.png)