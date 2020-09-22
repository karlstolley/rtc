---
title: Real-Time Monitoring and Messaging
due_date: &deadline 2020-10-05
preview: false
goals:
  - Learn to programmatically access web-available resources, and run comparisons on the results
  - >
    Learn to command established real-time communication APIs, including Web Workers, Web Sockets,
    and Web Notifications
  - Improve your ability to work with a centralized group repository and an individual fork
  - "ITMD 545 Only: Learn to serialize data in a web-friendly format like XML or JSON"
requirements:
  - Valid, semantic HTML; valid CSS; error-free JavaScript
  - Feature detection for all JavaScript calls to Web APIs
  - >
    A centralized group repository that contains your ExpressJS app, which can be cloned and run
    locally
  - A personal fork of the group repository in your GitHub account where you do most of your work
  - Make good use of feature branches on your fork of the group repository
  - All work submitted to the group repository should be done through pull requests on GitHub
deliverables:
  - action: Organize on Basecammp into teams for Project One.
    description: >
      If you have an idea for what you’d like to build for Project One, you might share that in your
      post.
    deadline: 2020-09-03
  - action: Formally pitch your Project One idea to Basecamp.
    description: >
      Once you and your team have organized yourselves, formally pitch your Project One idea on
      Basecamp for instructor feedback and approval.
    deadline: 2020-09-10
  - action: Post your Project One progress to Basecamp.
    description: >
      Include a link to your GitHub repository. Be sure and also respond to the progress of other
      group projects.
    deadline: 2020-09-17
  - action: Post your Project One progress to Basecamp.
    description: >
      Include a link to your GitHub repository and a short video where your group talks through your
      project running in a web browser. Be sure and also respond to the progress of other group
      projects.
    deadline: 2020-09-24
  - action: Submit your final Project One.
    description: >
      Submissions should be both public on Basecamp and private to the instructor’s email. Your
      email should include:
    details:
      - Links to your group and individual repositories
      - >
        A self-critique memo, written in the body of the email, about your work on the project and
        your progress in class to this point.
      - >
        A short critique of each of your group members, also written in the body of the email.
    deadline: *deadline
---

For this project, you and a small team will leverage some combination of ExpressJS, Web
Sockets/socket.io, Web Workers, Service Workers, and the Notifications API to create a web-based
system that monitors a source for changes in data.

For example, you might periodically scrape the contents of the daily Congressional Record at
[congress.gov](https://www.congress.gov/congressional-record) and run a diff against your last
retrieved copy. Your project would then perhaps provide notifications of changes, as well as a page
highlighting the changes as they've occurred--and that would also update in real-time as changes
come in.

You can do this with any source of data that updates multiple times over the course of a *typical*
day. Just be sure you do not run afoul of the copyright laws surrounding the data you're using. (US
Government publications, for example, generally are not protected by copyright because they are in
the public domain.)
