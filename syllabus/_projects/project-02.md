---
title: Real-Time Collaboration Alpha Release
due_date: &deadline 2021-11-18
preview: false
goals:
  - >
    Increase your command of real-time communication APIs, including WebRTC, Web Workers, Web
    Sockets, and Web Notifications
  - >
    Learn to build a WebRTC-based application that functions over a local-area network or a
    carefully configured wide-area network, with *temporarily* opened high-numbered ports and
    port-forwarding on your local network (if possible)
  - Improve your ability to work with a centralized group repository and an individual fork
  - >
    ITMD 545 Only: Learn to develop long-term monitoring of the performance and effects of your
    WebRTC app on the networks of individual users
requirements:
  - >
    Your app should work with the latest implementations of the WebRTC specification and its
    protocols, but you must also make use of `adapter.js` and "perfekted negotiation" fallbacks for
    older browsers
  - Your app must be able to auto-generate obfuscated, hard-to-guess namespaces for users
  - >
    You should use progressively enhanced, standards-compliant HTML, CSS, and JavaScript to build a
    satisfying mobile-first, responsive interface for your users
  - >
    You should do the appropriate feature- and constraint-detection steps necessary to ensure the
    smoothest, interoperable, platform-neutral operation of your app as possible
  - >
    The shared-activity part of your app should either be something of your group’s creation (like a
    simple game) or leverage a third-party API or service
  - >
    You must maintain a centralized group repository that contains your ExpressJS app, which can
    be cloned and run locally
  - >
    You must also maintain a personal fork of the group repository in your GitHub account where you
    do most of your work
  - You should make good use of feature branches on your fork of the group repository
  - You should **never** commit directly on the `main` branch
  - >
    All work submitted to the group repository should be done through pull requests on GitHub, which
    is how commits get onto the `main` branch
deliverables:
  - action: Organize into groups of three or four students for Project Two.
    description: >
      Use Basecamp to find team members for yourself.
    deadline: 2021-10-20
  - action: Formally pitch your Project Two idea on Basecamp.
    description: >
      Once you and your team have organized yourselves, formally pitch your Project Two idea on
      Basecamp for instructor feedback and approval.
    deadline: 2021-10-28
  - action: Weekly Project Two check-in
    description: >
      Include a link to your GitHub repository. Be sure and also respond to the progress of other
      group projects.
    deadline: 2021-11-04
  - action: Post Project Two draft and walkthrough video
    description: >
      Include a link to your GitHub repository and a short video where your group talks through your
      project running in a two web browsers. Be sure and also respond to the progress of other group
      projects.
    deadline: 2021-11-11
  - action: Submit your final Project Two.
    description: >
      Submissions should be both public on Basecamp and private to the instructor’s email. Your
      email should include:
    details:
      - Links to your group and individual repositories
      - A link to a video showing your app at work on two different browsers
      - >
        A self-critique memo, written in the body of the email, about your work on the project and
        your progress in class to this point
      - >
        A short critique of each of your group members, also written in the body of the email
    deadline: *deadline
---

For this project, you and your chosen team will create a multipeer chat-based application that
enables realtime audio, video, and text/data communication over a WebRTC connection. The signaling
portion must enable multiple users to connect to each other in a mesh network, and your app should
allow multiple separate groups of users to join calls on their own namespaces.

In addition to its chat features, your app must also enable teams of users to engage in some kind of
shared realtime activity: playing a game, listening to music or watching videos, or collaborating on
a document or some other kind of work.

The shared-activity part of your app can either be a feature that your team builds itself, or it can
leverage the open API of any service that makes itself available. For example, if you decide to
create an app for listening to music in pairs, you might have a way to share mp3 files with users as
streaming data, using the RTCDataChannel, from one user’s computer—or you might leverage something
like the Spotify API. While there may be particular use cases for something like the HTML `<iframe>`
element, the shared-activity part of your app must be more technologically sophisticated than simply
loading the same web resource in the browsers of both users.

Finally, while you will almost certainly have need of WebSockets/socket.io for certain signaling
tasks, your app should leverage WebRTC peer connections to ensure that the bulk of peer-to-peer
communication and data sharing takes place browser to browser, rather than through your app’s
third-party server. For example, if you build a game that two users can play together, various moves
and states of game play should be transferred from player to player over WebRTC. You may, however,
opt to additionally store game-state information on a server for the purposes of game recovery,
score keeping, etc.
