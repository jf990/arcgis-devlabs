# ArcGIS DevLabs

ArcGIS DevLabs have turned out to be a popular way to on-board new developers to the ArcGIS platform. The simple lab-based presentation format coupled with an over-arching theme called Data, Design, Develop, has helped introduce the ArcGIS developer tools to both new audiences and existing customers who are interested in fast onboarding with an unfamiliar SDK.

DevLabs have presented the website team an unexpected challenge: new content. We are having difficulty with completing the full lab series for each SDK and keeping the content fresh. We need this to continue to attract new developers and maintain DevLabs effectiveness. We feel a good way to address this is to host a doc-a-thon where we get authors and potential authors together in a place without distractions for a defined period.

## Why DevLabs?

Why do we have DevLabs when we have Guide Doc, Samples, Tutorials, and Example Apps?

DevLabs present a well thought out format to present ArcGIS as a platform to developers and introduce specific platform concepts in a simple, easy to understand and short exercise. While the labs work together as a workflow, any lab can be started and completed on its own. The labs originated from the experiences of our GeoDev Outreach team as they introduced new developers to our SDKs.

DevLabs excel where our other documentation falls short:

- Short, time-boxed exercises (10-15 minutes)
- Provides data and solutions
- Data, Design, Develop covers ArcGIS as a platform
- A specific theme
- The labs work together to complement each other

DevLabs are not a replacement where our other documentation excels:

- Providing in-depth coverage of a topic. DevLabs lean toward lighter, introductory content designed to get the reader into a topic quickly. Guide doc, sample apps, and example apps are better suited to in-depth coverage.
- Detailing the breadth and options of a platform concept. DevLabs are designed to introduce the minimum functionality to achieve success with a given platform feature. The reader will be enticed to learn more with the SDKs documentation.
- Deep background and cross-linking. DevLabs do not overwhelm the reader with details and options. The reader is encouraged to learn more by going to the SDK documentation.

What do your need to author DevLabs?

+ macOS or Windows.
+ Text editor most comfortable with to edit markdown files.
+ Ability to run node.js. We will be using version 8 (current, latest features). Install nodejs from nodejs.org.
+ Access to the ArcGIS for Developers website.
+ Have the developer’s website repo checked out on the master branch in a working directory on your computer.

---

# Supplemental information for Esri ArcGIS DevLabs at developers.arcgis.com

[DevLabs Slides](docs/slides-devlabs/index.html): Slides from the 28-Sep-2017 DevLabs doc-a-thon.

## Additional information

  + [ArcGIS DevLabs](https://developers.arcgis.com/labs/)
  + [ArcGIS DevLabs Style Guide](https://github.com/ArcGIS/arcgis-for-developers/wiki/ArcGIS-DevLabs-Styleguide)
  + [ArcGIS for Developers website workflow](https://github.com/ArcGIS/arcgis-for-developers/wiki/Editing-the-Site-Locally)
  + [Open issues for DevLabs work](https://github.com/ArcGIS/arcgis-for-developers/issues?q=is%3Aopen+is%3Aissue+label%3ADevLabs)

## Notes For Authors (See [Slides](docs/slides-devlabs/index.html))

1. Get access to the [ArcGIS-for-Developers website](https://github.com/ArcGIS/arcgis-for-developers)
   + Sign up for a free account on GitHub or skip this if you already have an existing account. Do not use esri in your username.
   + Add your full name and "Esri" as your company to your profile.
   + Email github_admin@esri.com with your GitHub username and ask to be added to the "ArcGIS" and "Esri" organizations.
   + You should now be able to access [https://github.com/ArcGIS/arcgis-for-developers](https://github.com/ArcGIS/arcgis-for-developers) and create and manage issues, create branches, comment on existing content, and update the wiki.

2. Installing the Developers Website
   + Install Node 8 from nodejs.org
   + Install on OS-X or Windows
   + See [Installing the site](https://github.com/ArcGIS/arcgis-for-developers/wiki)

3. Get on Slack channels:
   + Runtime Team __esri-runtime.slack.com__
   + #dev-site-general - Common channel for general discussion about the developers website.
   + #dev-site-status - Channel for automated status messages from github and Jenkins.
   + #dev-site-deployment - Channel for conversation and chat around specific deployments of the developers site and deployment related issues.

4. Working with github (our process)
   + [Editing the site](https://github.com/ArcGIS/arcgis-for-developers/wiki/Editing-the-Site-Locally)

## DevLabs doc-a-thon 28-Sep-2017 Postmortem

On Thursday 28-Sep-2017 and Friday 29-Sep-2017 we held a DevLabs doc-a-thon. The event was open to anyone within the Esri developers ecosystem interested in writing a DevLab or learning the process. We saw representatives from several company organizations:
  + Runtime
  + Web development
  + Python
  + Developer outreach
  + Start-ups
  + Developers website

We had participation from several offices:
  + Redlands, CA
  + Portland, OR
  + Edinburgh, Scotland
  + Durango, CO

With representation from SDKs including:
  + Android
  + iOS
  + JavaScript
  + .NET
  + Python
  + Qt

The output from the two-day doc-a-thon includes **21** new DevLabs!

### What went right

Overall the doc-a-thon event was very successful. We met our goal getting new DevLabs across the SDKs that are most popular with our developer community and hit on the most important platform features.

  + Getting everyone in the same place at the same time.
  + Being able to work together and work out ideas in a collaborative environment.
  + Presentation of DevLabs authoring process and style guide.
  + Interactive question and answer.
  + Having clear goals and focus.

### What went wrong

  + Some issues on some individual computers with the website build process.
  + Not knowing who was attending in advance hampered communicating important pre-workshop information to participants. For a future event it would be better to use an event sign up system.
  + Some specific labs were not worked out in advance, leaving it open to interpretation how to author the lab or the specific workflow to cover. For a future event any lab to be covered should have an outline before asking authors to work on it.
  + With so much progress all at once, the follow up and lab checking process got bogged down.

## What's next for DevLabs?

The immediate challenge is reviewing the work completed and releasing the labs as they are approved and ready to release. Next, we plan to redesign the DevLabs presentation to accommodate the overflow of labs in the develop section and imbalance of labs offered between SDKs and data and design sections. Finally, we are hoping to continue authoring more labs to achieve parity across all SDK products and offer more appealing platform features.
