---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio
active: true
# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  # filter_button:
  # - name: All
  #   tag: '*'
  # - name: Machine Learning
  #   tag: Machine Learning
  # - name: Data Visualization
  #   tag: Data Visualization
  # - name: Programming
  #   tag: Programming

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

### Machine Learning and Deep Learning

- I created [Indoor Scene Detector](https://github.com/nicovandenhooff/indoor-scene-detector) with my classmate Melissa Liow.  Indoor Scene Detector is a full stack computer vision application built with PyTorch, Captum, Flask, React, Docker, Heroku and GitHub Pages.  It is capable of classifying images of an indoor scene, such as a bedroom or a kitchen.  You can use one of four convolutional neural networks to classify the image within the application.
- I participated in the [WiDS Datathon 2022 Kaggle Competition](https://www.kaggle.com/c/widsdatathon2022) as a team with three of my classmates from UBC.  The goal of the project was to use weather data, climate data, and building characteristics to build a Machine Learning model to accurately predict a building's energy consumption.  Our [final solution](https://www.kaggle.com/nicojv/wids-datathon-2022-ensemble-learning-top-10) implemented an ensemble of gradient boosted models, and ended up in the top 10% of all solutions on Kaggle.

### Programming

- I wrote and maintain the Python package [Reddit Data Collector](https://github.com/nicovandenhooff/reddit-data-collector) ("RDC").  RDC is a tool that integrates with Reddit's API and allows a user to collect post and comment data for further analysis.
- I participated in Advent of Code 2021 ("AOC").  AOC is a yearly challenge that tests participants data structures and algorithms skills.  My [solutions](https://github.com/nicovandenhooff/advent-of-code-2021) are written in Python with an emphasis on the use of vectorization via NumPy.

### Data Visualization

- I collected, analyzed, and visualized data on thousands of Machine Learning and Deep Learning GitHub repositories.  I wrote [an article](https://towardsdatascience.com/exploring-the-most-popular-machine-learning-and-deep-learning-github-repositories-90b9ecf12be7) about this project that was published in Towards Data Science and selected as an "Editors Pick".
