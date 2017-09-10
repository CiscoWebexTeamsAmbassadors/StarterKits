---
layout: page
title: Contributing
permalink: /contributing/
group: "navigation"
---

# Contributing
Contributions to Cisco Spark Ambassador PowerUps are welcomed and encouraged. To ensure that quality is maintained we ask that you ensure that the project that you are submitting meets the quality standards.

New PowerUps are welcomed in any programming language or framework. (Node.js/Botkit/Redis is currently the most popular stack)

#### Prerequisites for Listing
- [X] Your submission should consist of a non trivial, Production or near to Production Ready application which is applicable to users of Cisco Spark
- [X] A clean and well written codebase however we do not mandate any particular style. Just make sure that its written in a way where other people can understand and modify it
- [X] Licensed under a permissive Open Source license (MIT preferred)
- [X] A clear and well documented README.md
- [X] Ensure that you have a repository owner to monitor issues and respond to any PR’s
- [X] A precomposed Dockerfile (a Deploy to Heroku button is recommended but not mandatory)

#### Directions to Submit a new PowerUp
The Cisco Spark Ambassador PowerUps website is powered by GitHub pages. In order to add a new listing submit a Pull Request to the PowerUps [repository](https://github.com/CiscoSparkAmbassadors/PowerUps/). 

This Pull Request needs to consist of a new markdown file that carries the name of your project submission as an addition to the /bots folder,  my-application.md as an example. The file should be in the following format ([example](https://github.com/CiscoSparkAmbassadors/PowerUps/commit/d13ef671130f7f112b28b1e39730713250179838)):

``` markdown
---
title: My Submission Name
author: My Company Name
language: e.g. Javascript
framework: e.g. Botkit
repo: My Submission Deploy to Heroku Button URL
---

My Submission Short Description

```

Once received, the PR will be reviewed by the Ambassador Community and either accepted or if there is an issue, you will contacted directly via GitHub. Once a listing has been approved, it will be live instantly thanks to GitHub pages.
