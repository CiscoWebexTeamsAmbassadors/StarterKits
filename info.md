---
layout: page
title: Info
permalink: /info/
group: "navigation"
---

# FAQ
#### Are Cisco Spark PowerUps a Cisco Product?
* This is not a product, it is a community powered listing  of Open Source contributions for Cisco Spark. These are primarily developed by third parties but Cisco may also make a contribution.

#### How do I get Support?
* These Open Source projects are provided  as is, there is no warranty, support is best efforts and provided by the entity that published the integration. See the support section for more. 

#### Is there a Security guarantee with the PowerUps?
* It is the responsibility of the customer to  validate that the Open Source application meets their internal security policies. Cisco does not offer any level of security certification for these Open Source projects.

#### Can I make changes to PowerUps?
* Everything is published under the MIT license which is down to the interpretation of the individual customer however it is generally accepted that MIT licensed software can  be used, modified and sold with  minimal restrictions.

#### Id like to share a project with the Community as a PowerUp, how do I do it?
* We are excited to list new contributions from the community, check out the contributing section to understand the process and requirements in order to be listed on the PowerUps listing. 

#### I like the PowerUps but need some support with custom development or customisation, are there developers that can help?
* There is a community of developers that have expertise building on Cisco Spark, some of those have contributed to the PowerUps and some have not. Any software development shop is able to build on Cisco Spark but if you like the quality of the projects provided by contributors you can reach out directly.

# Contributing
Contributions to Cisco Spark Ambassador PowerUps are welcomed and encouraged. To ensure that quality is maintained we ask that you ensure that the project that you are submitting meets the quality standards.

New PowerUps are welcomed in any programming language or framework. (Node.js/Botkit is currently the most popular stack)

#### Prerequisites for Listing
- [ ] A clean and well written codebase however we do not mandate any particular style. Just make sure that its written in a way where other people can understand and modify it
- [ ] Licensed under a permissive Open Source license (MIT preferred)
- [ ] A clear and well documented README.md
- [ ] Ensure that you have a repository owner to monitor issues and respond to any PR’s
- [ ] A precomposed Dockerfile (a Deploy to Heroku button is recommended but not mandatory)

#### Directions to Submit a new PowerUp
The Cisco Spark Ambassador PowerUps website is powered by GitHub pages. In order to add a new listing submit a Pull Request to the PowerUps repository. 

This Pull Request needs to consist of a new markdown file that carries the name of your project submission as an addition to the /bots folder,  my-application.md as an example. The file should be in the following format:

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

# Support
The Open Source PowerUps are not a Cisco Product and as such all support is offered on a best efforts basis directly by the contributors of the PowerUps directly. 

Please do not raise a support request with Cisco or Cisco Spark for Developers for any issues relating to the PowerUps as they will be unable to assist.

To request support raise an issue against the repository for the respective PowerUp.

