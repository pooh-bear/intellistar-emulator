# intellistar-emulator
A web application that displays weather information in the same visual presentation as the cable headend unit [Intellistar](https://en.wikipedia.org/wiki/IntelliStar).  

Forked from [qconrad's incredible effort](https://github.com/qconrad/intellistar-emulator) to serve as a more frequently updated, bleeding edge version of this project. (See Contributing.)

[![build-docker](https://github.com/pooh-bear/intellistar-emulator/actions/workflows/build-docker.yaml/badge.svg)](https://github.com/pooh-bear/intellistar-emulator/actions/workflows/build-docker.yaml)  

## Overview
This is a local forecast segment that airs on The Weather Channel called the "Local on the 8s". The name is because it airs at timeslots that end in "8" (9:28, 2:48, etc.). The forecast is approximately a minute long and provides information on current and forecasted weather conditions. This type of forecast started in 1982 using WeatherStar units. It was later upgraded to Intellistar in 2003 and received various graphic changes over the years. This emulator uses the style that started in 2013.

## Instructions
## Option 1 (easier)
1. Visit: <https://pooh-bear.github.io/intellistar-emulator/>.
2. Enter zip code
3. Click start
4. Press F11 for fullscreen

## Option 2 (more customizable)
1. Extract all contents into folder
2. Run index.html in Google Chrome
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

## Option 3 (Docker)
1. `docker run -p 8080:80 ghcr.io/pooh-bear/intellistar-emulator`
2. Visit: http://localhost:8080
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

## Features
Most of core animation and logic has been replicated including severe weather alerts, forecast descriptions, crawl text, and the Doppler radar map.

*Some of these features are temporarily not working due to the discontinuation of WU's API*

## Looping
To enable or disable looping, click on the TWC logo in the info-bar in the top-left corner of the emulator.

## Contributing
Whilst I pay massive respects to all [the previous contributors](https://github.com/qconrad/intellistar-emulator/graphs/contributors) of this project, things seem to be breaking faster than contributors' activeness with the project/on Github. I also think there's a lot of potential yet to be baked into this! Through this fork, I'll be adding in what I think are important fixes and features (major, QOL, or otherwise) that may not be in the target vision of the original contributors.  

I endeavor to push as much, if not all, contributions, upstream, however, this fork serves to be a more "active" repo compared to original, as I am actively working on other projects/repos on Github as a full time software engineer.  

So please feel free to contribute if you'd like to! All are welcome, no matter if it's your first or thousandth time that you're contributing to Open Source Software. Please create a PR and tag me (@pooh-bear) for review! I endeavor to initially glace/comment through on all PRs I receive within 24-48 hours, and approve/merge all good-standing PRs expediciously.

## Screenshots
![Screenshot 1](/screenshots/1.png)

![Screenshot 2](/screenshots/2.png)

![Screenshot 3](/screenshots/3.png)

![Screenshot 4](/screenshots/4.png)

![Screenshot 5](/screenshots/5.png)

![Screenshot 6](/screenshots/6.png)

![Screenshot 7](/screenshots/7.png)

![Screenshot 8](/screenshots/8.png)

![Screenshot 9](/screenshots/9.png)

![Screenshot 10](/screenshots/10.png)
