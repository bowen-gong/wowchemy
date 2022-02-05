---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Android Game Development"
summary: "Developed an android game"
authors: []
tags: [Software Development]
categories: []
date: 2022-02-04T13:29:45-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## 1 Design Considerations

### 1.1 Assumptions

* The software is designed to allow a player to create cryptograms, solve cryptograms, view unsolved/completed cryptograms, and overview the statistics.
* The user can log in the system with no password.
* A user can create many players.
* There will be only one player at a time.
* A player can create many cryptograms.
* The software will run locally and require no Internet service.
* There will be a well-designed user iterface to allow the player to perform all related operations. The user interface will be intuitive and responsive.
* The operational environment is android operating system.
* The performance of the game will be such that the player will not experience any lag.

### 1.2 Constraints

* The user can only create players with unique username.
* The player can only create cryptogram with unique puzzlename.
* The software is only designed to run on android operating system.
* The software will be written in Java version 1.7 or 1.8 and the development will be majorly conducted in Android Studio.
* The player is only allowed to solve a cryptogram from the unsolved cryptogram list.
* The player is allowed to solve a cryptogram with limited attempts.

### 1.3 System Environment

* The software should be run on a cellphone with android operating system and a touch screen.
* The minimum CPU is Intel core i3 processor with 2 GHz, but i5 or i7 is recommended for better experience.
* The minimum Ram is 2 Gb, but 4 Gb or more is suggested.

## 2 Architectural Design

### 2.1 Component Diagram

![Image](ComponentDiagram.png)

### 2.2 Deployment Diagram

We are developing a very simple software, so only one component is shown.

![Image](DeploymentDiagram.png)

## 3 Low-Level Design

### 3.1 Class Diagram

![Image](design-team.png)

### 3.2 Other Diagram

Sequence diagram is added below.

![Image](SequenceDiagram.png)

## 4 User Interface Design

|  |  |
:-------------------------:|:-------------------------:
|![](screenshot1.png)|![](screenshot2.png)|
|![](screenshot3.png)|![](screenshot4.png)|
|![](screenshot5.png)|![](screenshot6.png)|
|![](screenshot7.png)|![](screenshot8.png)|
|![](screenshot9.png)|![](screenshot10.png)|
|![](screenshot11.png)|![](screenshot12.png)|
|![](screenshot13.png)|![](screenshot14.png)|
|![](screenshot15.png)|![](screenshot16.png)|


