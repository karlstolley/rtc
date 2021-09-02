---
title: A Basic WebRTC Application
due_date: &deadline 2021-10-07
preview: false
goals:
  - Gain experience working with the fundamental WebRTC objects and APIs
  - Learn to set up and use a namespaced signaling channel for establishing WebRTC connections
  - Learn to write WebRTC connection code according to the perfect-negotiation pattern
  - >
    **ITMD 545 only**: learn about and implement a Web API that complements or extends your work
    with WebRTC
requirements:
  - >
    Valid, semantic HTML; valid, custom CSS; error-free vanilla JavaScript (no client-side
    libraries)
  - Intelligent use of feature detection for WebRTC and any Web APIs you use
  - >
    A signaling server written in Socket.IO or pure WebSockets, powered by ExpressJS or another
    Node.js-based framework (discuss with instructor)
  - An intelligently written `package.json` file including all server-side dependencies
  - Ability for two peers to connect to each other over a local network
  - >
    Use of the perfect-negotiation pattern, with necessary fallbacks for browsers with older or
    incomplete implementations of `RTCPeerConnection`
  - >
    A meticulously organized Git repository with frequent atomic commits and meaningful commit
    messages that accurately reflect each set of changes that you make
  - >
    Ability for instructor and others to easily clone, set up, and run your project over HTTPS on a
    local network
deliverables:
  - action: Pitch your Project One idea to the [Project Showcase Basecamp](https://3.basecamp.com/3058761/projects/23668414).
    description: >
      Post a brief pitch of your Project One idea on Basecamp for peer and instructor feedback and
      instructor approval.
    deadline: 2021-09-16
  - action: Schedule a one-on-one conference with the instructor (see Basecamp).
    description: >
      Sometime during the week of September 20, you will meet individually with the instructor to
      discuss your Project One idea.
    deadline: 2021-09-16
  - action: Post your Project One progress to Basecamp.
    description: >
      Include a link to your GitHub repository. Be sure and also respond to the progress of other
      projects.
    deadline: 2021-09-30
  - action: Submit your final Project One.
    description: >
      Submissions should be both public on Basecamp and private to the instructor’s email. Your
      email should include:
    details:
      - The link to your project’s repository
      - >
        A self-critique memo, written in the body of the email, about your work on the project and
        your progress in class to this point.
      - >
        **ITMD 545 only**: a short write-up of the Web API you included, and what you learned about
        it.
    deadline: *deadline
---

For this project, you will work individually to build a small app that is powered by WebRTC.

**ITMD 469 students** will build an app that allows students to seek help from an instructor or TA
in real time, something like virtual office hours. The app must include both audio and video, and
make some worthwhile use of a data channel.

**ITMD 545 students** will build an app that includes some combination of streaming audio, video,
and data.
