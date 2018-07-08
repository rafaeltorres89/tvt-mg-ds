# Life Design | Mongeral Aegon

[![GitHub forks](https://img.shields.io/github/forks/rafaeltorres89/tvt-mg-ds.svg)](https://github.com/rafaeltorres89/tvt-mg-ds/network)
[![npm](https://img.shields.io/npm/v/npm.svg)](https://github.com/rafaeltorres89/tvt-mg-ds/npm)

-------

<h3 align="center">
  <img src="https://madstyle.mongeralaegon.com.br/assets/app/css/img/site/global/mongeral-aegon-logo-site.png" alt="Mongeral Aegon" />
</h3>

<p align="center">
    <a href="#about">About</a> &bull;
    <a href="#features">Features</a> &bull;
    <a href="#organization">Organization</a> &bull;
    <a href="#installation">Installation</a>
</p>

## About

The Life Design of Aegon Mongeral was thought of as an enterprise desgin system. Where all development and creation content is presented directly on the website (http://lifedesign-mongeral.com).

The goal since git directory, is to store the developed and created structure as a backup. In addition, you are thinking of contributing to the development of Life Design, you will be able to learn in an easy and effective way what and how we work in our team.

Welcome, and good luck!



## Features

Write



## Organization

Creating a Marvel iOS App from scratch..

```
carbon-components/
├── html
├── css
│   ├── carbon-components.css
│   └── carbon-components.min.css
├── scripts
│   ├── carbon-components.js
│   └── carbon-components.min.js
├── scss
│   └── components
│       └── modal
│           └── _modal.scss
├── umd
│   └── index.js
├── es
│   └── index.js
└── src
```



## Installation

This project uses [Bundler](http://bundler.io) and [CocoaPods](https://cocoapods.org). All you need to setup it properly is:
```
<dependency>
	<groupId>com.github.sarxos</groupId>
	<artifactId>webcam-capture</artifactId>
	<version>0.3.13-SNAPSHOT</version>
</dependency>
```

## Tests And Coverage

You can run the tests any time. All your need to do is:
```
bundle exec fastlane test
```

## Hello World

Code below will capture image from your default webcam and save it in ```hello-world.png``` file:

```java
Webcam webcam = Webcam.getDefault();
webcam.open();
ImageIO.write(webcam.getImage(), "PNG", new File("hello-world.png"));
```

## More Examples!

Below are the very pretty basic examples demonstrating of how Webcam Capture API can be used in the Java code. All can be found in the project source code. Please note that some of those examples may use the newest API which has not yet been released to maven Central. In such a case please make sure you are using the newest Webcam Capture API SNAPSHOT.

* [How to detect webcam](https://github.com/sarxos/webcam-capture/blob/master/webcam-capture/src/example/java/DetectWebcamExample.java)

List of additional capture drivers includes:

| Driver Name     | Stable | Central | Description                             |
|-----------------|--------|---------|-----------------------------------------|
| [ipcam][]       | yes    | yes     | Driver for IP / network camera          |
| [fswebcam][]    | yes    | yes     | Driver for [FSWebcam][] [CLI][] tool    |
| [gstreamer][]   | yes    | yes     | Driver for [GStreamer][] framework      |
| [openimaj][]    | yes    | yes     | Driver for [OpenIMAJ][] framework       |
| [v4l4j][]       | yes    | no      | Driver for [V4L4j][] library            |
| [jmf][]         | yes    | yes     | Driver for [JMF][] / [FMJ][] frameworks |
| [lti-civil][]   | yes    | yes     | Driver for [LTI-CIVIL][] library        |
| [vlcj][]        | yes    | yes     | Driver for [vlcj][] library             |
| [javacv][]      | yes    | yes     | Driver for [JavaCV][] library           |
| [ffmpeg-cli][]  | poc    | no      | Driver for [FFmpeg][] [CLI][] tool      |

## License
This project is licensed under the terms of the MIT license. See the LICENSE file.
