---
title: Real-Time Monitoring and Messaging
due_date: &deadline 2020-10-01
preview: true
goals:
  - The first goal.
  - The second goal.
  - The third goal.
requirements:
  -
deliverables:
  - action:
    description: Deliverable one.
    details:
      -
    deadline: 2020-01-15
  - action:
    description: Deliverable two.
    details:
      -
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

Full project description to be posted by August 31.
