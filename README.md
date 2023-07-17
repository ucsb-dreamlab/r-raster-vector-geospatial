[![DOI](https://zenodo.org/badge/44772343.svg)](https://zenodo.org/badge/latestdoi/44772343)
[![01 Build and Deploy Site](https://github.com/datacarpentry/r-raster-vector-geospatial/actions/workflows/sandpaper-main.yaml/badge.svg)](https://github.com/datacarpentry/r-raster-vector-geospatial/actions/workflows/sandpaper-main.yaml)
[![Create a Slack Account with us](https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg)](https://swc-slack-invite.herokuapp.com/)
[![Slack Status](https://img.shields.io/badge/Slack_Channel-dc--geospatial-E01563.svg)](https://swcarpentry.slack.com/messages/C9ME7G5RD)

# R for Raster and Vector Data

## This is a fork of the canonical lesson for geo4Lib
Summer, 2023

### Possibilities
At Geo4lib Camp on July 24, the group will have 90 minutes to look at this geospatial Data Carpentry lesson. In the spirit of Un-Conference, we are prepared to take this discussion in 1 of these 4 directions:
- Re-outline an introduction to geospatial data from scratch. This lesson is a giant monster-- more than 11 hours! Can we outline a better way to provide an introduction to scripting-based GIS? This would be a largely white-board and sticky-note session.
- Closely read 3-4 episodes and put together detailed issues and start forks in small groups
    - Brief overview of the Carpentries Workbench / Issues
    - Small groups create issues and start writing markdown in forks of the lesson--with pull requests to happen after the conference.
    - Report back on issues
- An open discussion on the learning objectives for this lesson. Each episode has stated objectives at the top. Are they accurate? Are the goals achievable based on the content?
- A brief hands-on overview of using the Carpentries WorkBench demonstrating the Carpentries teaching method. 


## Contributing to lesson development

- The lesson files to be edited are in the `_episodes` folder. This repository uses the `main` branch for development.
- You can visualize the changes locally with the [sandpaper](https://github.com/carpentries/sandpaper) R package by executing either the `sandpaper::serve()` or `sandpaper::build_lesson()` commands. In the former case, the site will be rendered at [http://localhost:4321](http://localhost:4321)
- Each time you push a change to GitHub, Github Actions rebuilds the lesson, and when it's successful (look for the green badge at the top of the README file), it publishes the result at [http://www.datacarpentry.org/r-raster-vector-geospatial/](http://www.datacarpentry.org/r-raster-vector-geospatial/)
- Note: any manual commit to `gh-pages` will be erased and lost during the automated build and deploy cycle operated by Github Actions.

### Lesson Maintainers:

- [Jemma Stachelek][stachelek_jemma]
- [Ivo Arrey][arreyves]
- Drake Asberry

[stachelek_jemma]: https://carpentries.org/instructors/#jsta
[arreyves]: https://carpentries.org/instructors/#arreyves
