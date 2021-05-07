---
title: Kitchen Dash
summary: A community based meal planning app made in 24 hours.
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: source code
  url: https://github.com/Zeyu-Li/Kitchen-Dash
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# # Slides (optional).
# #   Associate this project with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example

---
## Project Description
Kitchen Dash is in its core, intended to be used to as a meal planning app but it is much more than that. Users are able upload their recipes and view other users' recipes. This app was made in 24 hours for a hackathon so it is very unpolished and has a lot of missing features.

## Accomplishments
- Used the React-Native framework to use a single make the app run on both iOS and Android using a single codebase.
- Used the Google Firebase API to implement realtime database functionality for the app.
- Practiced agile scrum practices and incorporated a "what did I do today?" session to ensure team members stay on top of tasks.

## Challenges
The main challenge we faced while developing Kitchen-Dash was due to us using few system specific frontend APIs to make styling easier but this ended up backfiring when the app showed visual glitches on one operating system while behaving completely fine on the other. To remedy this problem, we ended up refactoring the code to remove all calls to the API in question and this took a major chunk of the 24 hours we had for creating the app. However, we did learn a few things like to always read documentation for whatever API we are planning to use to ensure it works on almost all devices.

## Tools Used
- {{< icon name="react" pack="fab" >}} React-Native
- {{< icon name="cloud" pack="fas" >}} Firebase   

## To-Do
- User authentication :white_check_mark:
- App layout :white_check_mark:
- Homepage redesign :white_large_square:
- Recipe querying :white_large_square:
- Add recipe function :white_large_square:
- Weakly meal planner :white_large_square:

## Media

{{< figure src="plan.png" caption="App layout created by Zeyu Li" >}}