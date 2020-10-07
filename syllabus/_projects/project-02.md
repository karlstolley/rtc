---
title: Chat Plus
due_date: &deadline 2020-11-19
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
  - action: Submit final deliverables.
    description: Deliverable two.
    details:
      -
    deadline: *deadline
---

For this project, you and your chosen team will build a chat application leveraging WebRTC that
supports some kind of shared activity: playing a game, listening to music or watching videos, or
collaborating on a document or some other piece of intellectual work.

While you will almost certainly have need of WebSockets/socket.io for certain messaging tasks, your
app should leverage WebRTC to ensure that the bulk of peer-to-peer communication and data sharing
takes place browser to browser, rather than through a third-party server. For example, if you build
a game that two users can play together, various moves and states of game play should be transferred
from player to player over WebRTC. You may, however, opt to additionally store game-state
information on a server for the purposes of game recover, score keeping, etc.
